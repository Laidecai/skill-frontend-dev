---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
---

## 📁 前端项目模板

### 现代 React 项目结构
```
my-app/
├── .github/
│   └── workflows/          # CI/CD
├── public/
│   └── favicon.svg
├── src/
│   ├── app/                # Next.js App Router 页面
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── api/            # API 路由
│   ├── components/         # 通用组件
│   │   ├── ui/             # 基础 UI 组件 (shadcn/ui)
│   │   └── shared/         # 业务共享组件
│   ├── features/           # 功能模块
│   │   ├── auth/
│   │   ├── dashboard/
│   │   └── settings/
│   ├── hooks/              # 自定义 Hooks
│   ├── lib/                # 工具函数/配置
│   │   ├── utils.ts
│   │   ├── api.ts          # API 客户端
│   │   └── db.ts           # Prisma/Drizzle
│   ├── stores/             # Zustand Store
│   ├── types/              # TypeScript 类型
│   ├── styles/             # 全局样式
│   └── i18n/               # 国际化
├── __tests__/              # 测试
│   ├── unit/
│   └── e2e/
├── .env.local
├── biome.json
├── tsconfig.json
├── tailwind.config.ts
├── next.config.ts
├── vitest.config.ts
└── package.json
```

### 快速初始化命令
```bash
# React (Vite)
pnpm create vite my-app --template react-ts

# Next.js
pnpm create next-app my-app --typescript --tailwind --eslint

# Nuxt
pnpm dlx nuxi init my-app

# Astro
pnpm create astro@latest

# SvelteKit
pnpm create svelte@latest my-app

# Expo (React Native)
pnpm create expo-app my-app

# shadcn/ui（在 Next.js 项目中）
pnpm dlx shadcn@latest init
pnpm dlx shadcn@latest add button card dialog form
```

---



---
> [← 返回主目录](../SKILL.md)
