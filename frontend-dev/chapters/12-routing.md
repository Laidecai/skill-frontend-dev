---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
---

## 🧭 路由

| 项目 | Stars | 框架 | 用途 | 安装 |
|------|-------|------|------|------|
| **remix-run/react-router** | 54k+ | React | ⭐ React 路由（v7 数据加载） | `npm i react-router` |
| **TanStack/router** | 8k+ | React | ⭐ 类型安全路由（推荐新项目） | `npm i @tanstack/react-router` |
| **vuejs/vue-router** | 19k+ | Vue | ⭐ Vue 官方路由 | `npm i vue-router` |
| **solidjs/solid-router** | 1k+ | Solid | Solid 路由 | `npm i @solidjs/router` |
| **sveltejs/kit** | 19k+ | Svelte | 内置文件系统路由 | 内置 |
| **kripod/atomic-router** | 750+ | 通用 | 原子化路由 | `npm i atomic-router` |

### 路由最佳实践
```tsx
// TanStack Router (类型安全)
import { createRouter, createFileRoute } from '@tanstack/react-router'

const router = createRouter({
  routeTree: rootRoute,
  context: { queryClient },
})

// React Router v7 (loader/action)
export const Route = createFileRoute('/dashboard')({
  loader: async () => {
    const data = await fetchDashboardData()
    return { data }
  },
  component: DashboardPage,
})
```

---



---
> [← 返回主目录](../SKILL.md)
