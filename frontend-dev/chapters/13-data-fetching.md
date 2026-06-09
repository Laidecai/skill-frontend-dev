---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
---

## 📡 数据获取与服务端状态

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **TanStack/query** | 44k+ | ⭐ 服务端状态管理（缓存/去重/重试/分页） | `npm i @tanstack/react-query` |
| **vercel/swr** | 31k+ | ⭐ 数据获取 Hook（stale-while-revalidate） | `npm i swr` |
| **reduxjs/react-redux** | 24k+ | RTK Query（Redux 内置数据获取） | `npm i @reduxjs/toolkit` |
| **apollographql/apollo-client** | 20k+ | GraphQL 客户端 | `npm i @apollo/client` |
| **urql-graphql/urql** | 9k+ | 轻量 GraphQL 客户端 | `npm i urql` |
| **trpc/trpc** | 38k+ | ⭐ 类型安全 API（端到端 TS） | `npm i @trpc/client` |

### TanStack Query 最佳实践
```tsx
import { useQuery, useMutation, useQueryClient } from '@tanstack/react-query'
import { api } from '@/lib/api'

// 获取数据
export function useTodos() {
  return useQuery({
    queryKey: ['todos'],
    queryFn: () => api.getTodos(),
    staleTime: 1000 * 60 * 5,     // 5 分钟内不重新获取
    gcTime: 1000 * 60 * 30,       // 30 分钟缓存
  })
}

// 修改数据
export function useAddTodo() {
  const queryClient = useQueryClient()
  return useMutation({
    mutationFn: (newTodo: Todo) => api.addTodo(newTodo),
    onSuccess: () => {
      queryClient.invalidateQueries({ queryKey: ['todos'] })
    },
  })
}

// 无限滚动/分页
export function useInfiniteTodos() {
  return useInfiniteQuery({
    queryKey: ['todos', 'infinite'],
    queryFn: ({ pageParam }) => api.getTodosPaginated(pageParam),
    initialPageParam: 0,
    getNextPageParam: (lastPage) => lastPage.nextCursor,
  })
}

// 乐观更新
export function useToggleTodo() {
  const queryClient = useQueryClient()
  return useMutation({
    mutationFn: ({ id, done }: { id: string; done: boolean }) =>
      api.toggleTodo(id, done),
    onMutate: async ({ id, done }) => {
      await queryClient.cancelQueries({ queryKey: ['todos'] })
      const previous = queryClient.getQueryData(['todos'])
      queryClient.setQueryData(['todos'], (old: Todo[]) =>
        old?.map(t => t.id === id ? { ...t, done } : t)
      )
      return { previous }
    },
    onError: (_, __, context) => {
      queryClient.setQueryData(['todos'], context?.previous)
    },
  })
}
```

### tRPC 最佳实践
```typescript
// server/router.ts
export const appRouter = router({
  user: {
    list: publicProcedure.query(() => db.user.findMany()),
    byId: publicProcedure.input(z.string()).query(({ input }) =>
      db.user.findById(input)),
    create: publicProcedure
      .input(z.object({ name: z.string(), email: z.string().email() }))
      .mutation(({ input }) => db.user.create(input)),
  },
})

// client/component.tsx
function UserList() {
  const { data, isLoading } = api.user.list.useQuery()
  const createUser = api.user.create.useMutation({
    onSuccess: () => trpcUtils.user.list.invalidate(),
  })
}
```

---



---
> [← 返回主目录](../SKILL.md)
