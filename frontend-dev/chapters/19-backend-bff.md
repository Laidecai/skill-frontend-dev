---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
---

## 🔌 后端 / BFF

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **trpc/trpc** | 38k+ | ⭐ 类型安全 API（端到端 TS，前端首选） | `npm i @trpc/client @trpc/server` |
| **hono/hono** | 24k+ | ⭐ 轻量 Web 框架（Edge/Fastify 风格） | `npm i hono` |
| **expressjs/express** | 66k+ | Node.js 传统 Web 框架 | `npm i express` |
| **fastify/fastify** | 33k+ | 高性能 Node.js 框架 | `npm i fastify` |
| **nestjs/nest** | 70k+ | Node.js 企业级框架 | `npm i @nestjs/core` |
| **hapijs/hapi** | 14k+ | 配置驱动 Web 框架 | `npm i @hapi/hapi` |
| **graphql/graphql-js** | 20k+ | GraphQL JS 实现 | `npm i graphql` |
| **apollographql/apollo-server** | 14k+ | GraphQL 服务端 | `npm i @apollo/server` |
| **prisma/prisma** | 43k+ | ⭐ 数据库 ORM（类型安全） | `npm i prisma @prisma/client` |
| **drizzle-team/drizzle-orm** | 28k+ | ⭐ 轻量 SQL ORM（类型安全） | `npm i drizzle-orm` |
| **lucia-auth/lucia** | 7k+ | 认证库（TypeScript） | `npm i lucia` |
| **better-auth/better-auth** | 6k+ | 现代认证框架（TypeScript） | `npm i better-auth` |

### tRPC + Prisma 全栈模板
```typescript
// server/router.ts
import { z } from 'zod'
import { publicProcedure, protectedProcedure, router } from './trpc'

export const todoRouter = router({
  list: publicProcedure.query(async () => {
    return db.todo.findMany({ orderBy: { createdAt: 'desc' } })
  }),
  create: protectedProcedure
    .input(z.object({ title: z.string().min(1).max(100) }))
    .mutation(async ({ input, ctx }) => {
      return db.todo.create({
        data: { title: input.title, userId: ctx.user.id },
      })
    }),
  toggle: protectedProcedure
    .input(z.object({ id: z.string(), completed: z.boolean() }))
    .mutation(async ({ input }) => {
      return db.todo.update({
        where: { id: input.id },
        data: { completed: input.completed },
      })
    }),
})
```

---



---
> [← 返回主目录](../SKILL.md)
