---
name: frontend-dev
description: '**前端开发专属技能包** — 专为前端开发者设计。涵盖 HTML/CSS/JS/TS 核心、React/Vue/Svelte/Solid 框架、Next.js/Nuxt/Astro 元框架、UI 组件库、CSS 方案、构建工具、测试、动画、可视化、性能优化、AI 辅助前端开发等全领域。集成 GitHub 高星前端开源项目的最佳实践。当用户编写前端代码（.jsx/.tsx/.vue/.svelte/.html/.css 等）或询问前端问题时自动激活。'
applyTo: "**/*.{jsx,tsx,vue,svelte,astro,html,css,scss,less,tailwind,tailwindcss,js,ts,mjs,mts}"
---

# 🎨 前端开发专属技能包 — Frontend Developer Skill

> 基于 GitHub 高星前端开源项目整合的最佳实践知识库。
> 覆盖从页面布局到复杂交互的全流程，为 Copilot agent 提供精准的前端开发指引。
>
> 📂 内容已按章节拆分至 `chapters/` 子目录中。

---

## 📋 目录

| # | 章节 | 文件 | 简介 |
|---|------|------|------|
| 1 | 🌐 [核心 Web 技术](chapters/01-core-web-technology.md) | `01-core-web-technology.md` | HTML5、CSS3 现代特性、JavaScript/TypeScript 基础 |
| 2 | ⚛️ [前端框架](chapters/02-frontend-frameworks.md) | `02-frontend-frameworks.md` | React、Vue、Svelte、Solid、Qwik 五大框架生态 |
| 3 | 🏗️ [元框架（全栈框架）](chapters/03-meta-frameworks.md) | `03-meta-frameworks.md` | Next.js、Nuxt、Remix、Astro、SvelteKit + 选型指南 |
| 4 | 🎨 [CSS 框架与工具](chapters/04-css-frameworks.md) | `04-css-frameworks.md` | Tailwind CSS、UnoCSS、Bootstrap、PostCSS、CSS-in-JS |
| 5 | 🧩 [UI 组件库](chapters/05-ui-component-libraries.md) | `05-ui-component-libraries.md` | Ant Design、shadcn/ui、MUI、Element Plus 及图标库 |
| 6 | 🔄 [状态管理](chapters/06-state-management.md) | `06-state-management.md` | Zustand、Redux、Jotai、Pinia、nanostores 等 10+ 方案 |
| 7 | ⚙️ [构建工具与打包器](chapters/07-build-tools.md) | `07-build-tools.md` | Vite、Webpack、esbuild、Turbopack、SWC、Biome + Vite 插件 |
| 8 | 📦 [包管理器](chapters/08-package-managers.md) | `08-package-managers.md` | npm、yarn、pnpm、bun 速查与选型建议 |
| 9 | ✅ [测试框架](chapters/09-testing.md) | `09-testing.md` | Vitest、Jest、Playwright、Cypress、MSW、Storybook |
| 10 | 💅 [样式方案](chapters/10-styling-solutions.md) | `10-styling-solutions.md` | CSS Modules、Tailwind 最佳实践、Panda CSS、方案选型 |
| 11 | 📝 [表单管理](chapters/11-form-management.md) | `11-form-management.md` | React Hook Form + Zod 验证、Vue FormKit 最佳实践 |
| 12 | 🧭 [路由](chapters/12-routing.md) | `12-routing.md` | TanStack Router、React Router v7、Vue Router |
| 13 | 📡 [数据获取与服务端状态](chapters/13-data-fetching.md) | `13-data-fetching.md` | TanStack Query（缓存/乐观更新/无限滚动）、tRPC |
| 14 | 🔍 [类型检查与代码质量](chapters/14-type-checking-code-quality.md) | `14-type-checking-code-quality.md` | TypeScript 技巧、Biome 配置、ESLint/Prettier/Husky |
| 15 | ✨ [动画与交互](chapters/15-animation.md) | `15-animation.md` | Framer Motion(Motion)、GSAP、CSS 动画最佳实践 |
| 16 | 📊 [数据可视化](chapters/16-data-visualization.md) | `16-data-visualization.md` | D3、ECharts、Recharts、Chart.js、visx |
| 17 | 🧱 [组件开发与管理](chapters/17-component-development.md) | `17-component-development.md` | Storybook、Radix UI、组件组合模式设计原则 |
| 18 | 📱 [移动端与跨平台](chapters/18-mobile-cross-platform.md) | `18-mobile-cross-platform.md` | Expo/React Native、Tauri、Electron、Flutter 选型 |
| 19 | 🔌 [后端 / BFF](chapters/19-backend-bff.md) | `19-backend-bff.md` | tRPC、Hono、Prisma、Drizzle、tRPC+Prisma 全栈模板 |
| 20 | 🌍 [国际化 (i18n)](chapters/20-i18n.md) | `20-i18n.md` | react-i18next、vue-i18n、FormatJS 最佳实践 |
| 21 | ⚡ [性能优化](chapters/21-performance.md) | `21-performance.md` | Web Vitals、懒加载、虚拟列表、Web Worker 代码示例 |
| 22 | ♿ [无障碍访问 (a11y)](chapters/22-a11y.md) | `22-a11y.md` | ARIA 原则、语义 HTML、键盘导航、检测工具 |
| 23 | 🤖 [AI 辅助前端开发](chapters/23-ai-assisted-frontend.md) | `23-ai-assisted-frontend.md` | 提示词模板、AI 工作流、v0.dev 等工具推荐 |
| 24 | 📁 [前端项目模板](chapters/24-project-templates.md) | `24-project-templates.md` | 目录结构模板、快速初始化命令 |
| 25 | 📚 [学习资源](chapters/25-learning-resources.md) | `25-learning-resources.md` | 官方文档、GitHub 高星教程、设计资源 |

---

## 🚀 快速导航

| 常用场景 | 推荐章节 |
|---------|---------|
| 新建前端项目 | [📁 前端项目模板 →](chapters/24-project-templates.md) |
| 选择前端框架 | [⚛️ 前端框架 →](chapters/02-frontend-frameworks.md) + [🏗️ 元框架 →](chapters/03-meta-frameworks.md) |
| UI 组件选型 | [🧩 UI 组件库 →](chapters/05-ui-component-libraries.md) |
| CSS 方案决策 | [🎨 CSS 框架 →](chapters/04-css-frameworks.md) + [💅 样式方案 →](chapters/10-styling-solutions.md) |
| 状态管理选择 | [🔄 状态管理 →](chapters/06-state-management.md) |
| API 数据获取 | [📡 数据获取 →](chapters/13-data-fetching.md) + [🔌 后端/BFF →](chapters/19-backend-bff.md) |
| 添加动画效果 | [✨ 动画与交互 →](chapters/15-animation.md) |
| 构建配置优化 | [⚙️ 构建工具 →](chapters/07-build-tools.md) |
| 代码质量规范 | [🔍 类型检查 →](chapters/14-type-checking-code-quality.md) |
| 性能调优 | [⚡ 性能优化 →](chapters/21-performance.md) |
| AI 辅助开发 | [🤖 AI 辅助前端 →](chapters/23-ai-assisted-frontend.md) |
| 学习提升 | [📚 学习资源 →](chapters/25-learning-resources.md) |

---

> **数据来源**: GitHub Stars, npm trends, MDN Web Docs, awesome-list 生态, 及社区最佳实践。
> 最后更新: 2025年
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **ant-design/ant-design** | 94k+ | ⭐ 企业级 UI 库（中后台首选） | `npm i antd` |
| **mui/material-ui** | 95k+ | ⭐ Material Design 3 组件库 | `npm i @mui/material` |
| **shadcn-ui/ui** | 85k+ | ⭐ 现代化组件（Tailwind + Radix UI） | `npx shadcn@latest init` |
| **radix-ui/primitives** | 17k+ | headless UI 原语（无障碍优先） | `npm i @radix-ui/react-dialog` |
| **ariakit/ariakit** | 8k+ | headless UI 库（无障碍） | `npm i ariakit` |
| **react-bootstrap/react-bootstrap** | 23k+ | Bootstrap React 组件 | `npm i react-bootstrap` |
| **chakra-ui/chakra-ui** | 38k+ | ⭐ 可访问性优先组件库（v3 使用 Panda CSS） | `npm i @chakra-ui/react` |
| **primefaces/primereact** | 15k+ | 丰富组件集（90+ 组件） | `npm i primereact` |
| **mantine/mantine** | 28k+ | ⭐ 现代 React 组件库（完整生态） | `npm i @mantine/core` |
| **nextui-org/nextui** | 24k+ | ⭐ 美观 UI 库（Tailwind + Framer Motion） | `npm i @nextui-org/react` |

### Vue UI 库
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **element-plus/element-plus** | 26k+ | ⭐ Vue 3 组件库（企业级，类似 Ant Design） | `npm i element-plus` |
| **nuxt/ui** | 4k+ | ⭐ Nuxt 官方 UI（Tailwind + Headless UI） | `npm i @nuxt/ui` |
| **primefaces/primevue** | 12k+ | Vue 组件库（90+ 组件/主题） | `npm i primevue` |
| **vuejs/headlessui** | 1k+ | Vue headless UI（Tailwind 团队） | `npm i @headlessui/vue` |
| **vueComponent/ant-design-vue** | 20k+ | Ant Design Vue 版 | `npm i ant-design-vue` |
| **varletjs/varlet** | 5k+ | Vue 移动端组件库 | `npm i @varlet/ui` |
| **vuetifyjs/vuetify** | 40k+ | Vue Material Design 组件 | `npm i vuetify` |

### Svelte UI 库
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **skeleton-app/skeleton** | 8k+ | Svelte UI 库（Tailwind） | `npm i @skeletonlabs/skeleton` |
| **saadeghi/daisyui** | 38k+ | Tailwind CSS 组件（框架无关） | `npm i daisyui` |

### 图标库
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **lucide-icons/lucide** | 17k+ | ⭐ 简洁清晰的 SVG 图标（推荐） | `npm i lucide-react` |
| **tailwindlabs/heroicons** | 22k+ | Tailwind 团队 SVG 图标 | `npm i @heroicons/react` |
| **phosphor-icons/phosphor-react** | 7k+ | 灵活图标库（6 种风格） | `npm i phosphor-react` |
| **tabler/tabler-icons** | 19k+ | 5000+ 开源 SVG 图标 | `npm i @tabler/icons-react` |
| **react-icons/react-icons** | 13k+ | 图标集合（包含所有主流图标集） | `npm i react-icons` |
| **unplugin/unplugin-icons** | 4k+ | 按需加载图标（UnoCSS 生态） | `npm i unplugin-icons` |

---

## 🔄 状态管理

| 项目 | Stars | 框架 | 用途 | 安装 |
|------|-------|------|------|------|
| **pmndrs/zustand** | 52k+ | React | ⭐ 轻量状态管理（推荐首选） | `npm i zustand` |
| **reduxjs/redux** | 61k+ | React | 传统状态管理（含 Redux Toolkit） | `npm i @reduxjs/toolkit` |
| **pmndrs/jotai** | 21k+ | React | 原子状态管理（Recoil 替代） | `npm i jotai` |
| **pmndrs/valtio** | 9k+ | React | 代理状态管理（MobX 风格） | `npm i valtio` |
| **vuejs/pinia** | 15k+ | Vue | ⭐ Vue 状态管理（Vuex 5） | `npm i pinia` |
| **vuejs/vuex** | 28k+ | Vue | Vuex 状态管理（已归档，推荐 Pinia） | `npm i vuex` |
| **sveltejs/svelte** | 82k+ | Svelte | 内置 store（writable/derived） | 内置 |
| **TanStack/store** | 3k+ | 通用 | 框架无关状态管理 | `npm i @tanstack/store` |
| **nanostores/nanostores** | 6k+ | 通用 | 极简原子状态管理（Astro 推荐） | `npm i nanostores` |
| **legendapp/state** | 2k+ | React | 高性能状态管理 | `npm i @legendapp/state` |

---

## ⚙️ 构建工具与打包器

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **vitejs/vite** | 72k+ | ⭐ 下一代前端工具链（默认推荐） | `npm create vite@latest` |
| **webpack/webpack** | 66k+ | 传统打包器（大型旧项目） | `npm i webpack` |
| **evanw/esbuild** | 39k+ | ⭐ 极速 JS 打包器（Go 编写） | `npm i esbuild` |
| **vercel/turborepo** | 27k+ | ⭐ 增量打包器/Rust 编写 | `npm i turbo` |
| **rollup/rollup** | 26k+ | ES Module 打包器（库开发首选） | `npm i rollup` |
| **parcel-bundler/parcel** | 44k+ | 零配置打包器 | `npm i parcel` |
| **swc-project/swc** | 31k+ | ⭐ Rust 编写的 JS/TS 编译器 | `npm i @swc/core` |
| **oxc-project/oxc** | 18k+ | Rust JS 工具链（Linter/解析器/打包器） | `npm i oxc` |
| **biomejs/biome** | 22k+ | ⭐ Rust 格式器 + Linter（替代 ESLint + Prettier） | `npm i @biomejs/biome` |
| **microsoft/rushstack** | 6k+ | 大型仓库构建工具 | `npm i @rushstack/eslint-config` |

### Vite 生态插件
| 插件 | 用途 | 安装 |
|------|------|------|
| **@vitejs/plugin-react** | React Fast Refresh | `npm i @vitejs/plugin-react` |
| **@vitejs/plugin-vue** | Vue SFC 支持 | `npm i @vitejs/plugin-vue` |
| **@vitejs/plugin-legacy** | 传统浏览器兼容 | `npm i @vitejs/plugin-legacy` |
| **unplugin-auto-import** | 自动导入 API | `npm i unplugin-auto-import` |
| **unplugin-vue-components** | Vue 组件自动导入 | `npm i unplugin-vue-components` |
| **vite-plugin-pwa** | PWA 支持 | `npm i vite-plugin-pwa` |
| **vite-plugin-inspect** | 构建检查 | `npm i vite-plugin-inspect` |

---

## 📦 包管理器

| 项目 | Stars | 用途 | 初始化 |
|------|-------|------|--------|
| **npm/cli** | 8k+ | Node 官方包管理器 | `npm init` |
| **yarnpkg/berry** | 7k+ | ⭐ 快速可靠包管理（PnP/零安装） | `yarn init` |
| **pnpm/pnpm** | 31k+ | ⭐ 高效磁盘空间/快速（推荐） | `pnpm init` |
| **oven-sh/bun** | 92k+ | ⭐ 极速 JS 运行时 + 包管理器/打包器 | `bun init` |

### 包管理器选型建议
```bash
# pnpm — 节省磁盘、速度快（推荐新项目使用）
pnpm create vite my-app --template react-ts
pnpm add @tanstack/react-query

# yarn berry — PnP 模式适用于严格依赖管理
yarn set version berry
yarn dlx create-vite my-app

# bun — 极速运行/安装/测试（实验性）
bun create vite my-app
bun add lucide-react
```

---

## ✅ 测试框架

### 单元测试
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **vitest-dev/vitest** | 14k+ | ⭐ Vite 原生测试框架（推荐） | `npm i vitest` |
| **jestjs/jest** | 45k+ | 广泛使用的 JS 测试框架 | `npm i jest` |
| **facebook/jest** | 45k+ | React 团队推荐 | `npm i jest` |
| **testing-library/testing-library** | 23k+ | ⭐ UI 组件测试库 | `npm i @testing-library/react` |

### E2E 测试
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **microsoft/playwright** | 70k+ | ⭐ 现代 E2E 测试（多浏览器/自动等待） | `npm i @playwright/test` |
| **cypress-io/cypress** | 48k+ | E2E 测试 + 组件测试 | `npm i cypress` |
| **puppeteer/puppeteer** | 90k+ | 浏览器自动化（Chrome） | `npm i puppeteer` |

### 测试工具
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **storybookjs/storybook** | 86k+ | ⭐ 组件开发/测试/文档 | `npx storybook@latest init` |
| **chalk/chromatic** | 1k+ | Storybook 视觉回归测试 | `npm i chromatic` |
| **mswjs/msw** | 16k+ | ⭐ API Mock 库（拦截真实请求） | `npm i msw` |
| **faker-js/faker** | 13k+ | ⭐ 假数据生成 | `npm i @faker-js/faker` |

---

## 💅 样式方案

### CSS Modules
```css
/* Component.module.css */
.wrapper { composes: container from global; }
.button { background: var(--primary); }
```

```tsx
import styles from './Component.module.css'
export const Button = () => <button className={styles.button}>Click</button>
```

### Tailwind CSS 最佳实践
```tsx
// ⭐ 推荐：组合使用（shadcn/ui 风格）
import { cn } from '@/lib/utils'

export function Button({ className, ...props }: ButtonProps) {
  return (
    <button
      className={cn(
        'inline-flex items-center justify-center rounded-md',
        'bg-primary text-primary-foreground shadow-sm',
        'hover:bg-primary/90 transition-colors',
        'focus-visible:outline-none focus-visible:ring-2',
        'disabled:pointer-events-none disabled:opacity-50',
        className
      )}
      {...props}
    />
  )
}
```

### Panda CSS (类型安全 CSS-in-JS)
```tsx
import { css } from '@/styled-system/css'

export const Button = () => (
  <button className={css({
    bg: 'primary',
    color: 'white',
    px: 4,
    py: 2,
    borderRadius: 'md',
    _hover: { bg: 'primary.600' }
  })}>
    Click
  </button>
)
```

### 样式方案选型

| 方案 | 适用场景 | 优势 |
|------|---------|------|
| **Tailwind CSS** | 通用首选（推荐） | 快速开发、一致性强、Purge 优化 |
| **CSS Modules** | 组件库/复杂项目 | 原生 CSS、无运行时开销 |
| **Panda CSS** | 类型安全项目 | 构建时生成、TS 类型提示 |
| **Vanilla Extract** | 零运行时 CSS-in-JS | TypeScript 变量共享 |
| **Styled Components** | 动态样式场景 | 运行时动态 Props |

---

## 📝 表单管理

| 项目 | Stars | 框架 | 用途 | 安装 |
|------|-------|------|------|------|
| **react-hook-form/react-hook-form** | 43k+ | React | ⭐ 高性能表单（uncontrolled） | `npm i react-hook-form` |
| **formik/formik** | 34k+ | React | 流行表单管理 | `npm i formik` |
| **final-form/react-final-form** | 7k+ | React | 订阅式表单 | `npm i react-final-form` |
| **@tanstack/form** | 2k+ | 通用 | TanStack 表单 | `npm i @tanstack/form` |
| **vueuse/vueuse** | 21k+ | Vue | `useForm` 组合式表单 | `npm i @vueuse/core` |
| **formkit/formkit** | 6k+ | Vue | ⭐ Vue 表单构建（验证/布局/主题） | `npm i @formkit/vue` |

### React Hook Form 最佳实践
```tsx
import { useForm } from 'react-hook-form'
import { z } from 'zod'
import { zodResolver } from '@hookform/resolvers/zod'

const schema = z.object({
  email: z.string().email(),
  password: z.string().min(8),
})

type FormData = z.infer<typeof schema>

export function LoginForm() {
  const {
    register, handleSubmit, formState: { errors, isSubmitting }
  } = useForm<FormData>({
    resolver: zodResolver(schema),
  })

  const onSubmit = async (data: FormData) => {
    // API 调用...
  }

  return (
    <form onSubmit={handleSubmit(onSubmit)}>
      <input {...register('email')} />
      {errors.email && <span>{errors.email.message}</span>}
      <input type="password" {...register('password')} />
      <button disabled={isSubmitting}>Submit</button>
    </form>
  )
}
```

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

## 🔍 类型检查与代码质量

### TypeScript 配置
```jsonc
// tsconfig.json — 现代前端推荐配置
{
  "compilerOptions": {
    "target": "ES2022",
    "lib": ["ES2023", "DOM", "DOM.Iterable"],
    "module": "ESNext",
    "moduleResolution": "bundler",
    "strict": true,
    "noUncheckedIndexedAccess": true,
    "exactOptionalPropertyTypes": true,
    "jsx": "react-jsx",
    "paths": { "@/*": ["./src/*"] }
  }
}
```

### TypeScript 类型技巧
```typescript
// 组件 Props 模式
interface ButtonProps extends React.ButtonHTMLAttributes<HTMLButtonElement> {
  variant?: 'primary' | 'secondary' | 'ghost'
  size?: 'sm' | 'md' | 'lg'
  isLoading?: boolean
}

// 泛型组件
function createQueryHook<TData, TParams extends any[]>(
  fetcher: (...params: TParams) => Promise<TData>
) { /* ... */ }

// 类型守卫
function isNonNullable<T>(value: T): value is NonNullable<T> {
  return value != null
}

// 字面量类型推导（const 断言）
export const THEME = {
  primary: '#0070f3',
  secondary: '#7928ca',
} as const
export type Theme = keyof typeof THEME
```

### 代码质量工具
| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **eslint/eslint** | 26k+ | ⭐ JS/TS Linter | `npm i eslint` |
| **prettier/prettier** | 51k+ | ⭐ 代码格式化器 | `npm i prettier` |
| **biomejs/biome** | 22k+ | ⭐ Rust 格式器 + Linter（替代 ESLint + Prettier） | `npm i @biomejs/biome` |
| **oxc-project/oxc** | 18k+ | Rust JS 工具链 | `npm i oxc` |
| **typicode/husky** | 33k+ | Git Hooks 管理 | `npm i husky` |
| **okonet/lint-staged** | 14k+ | 暂存文件 Lint | `npm i lint-staged` |
| **commitizen/cz-cli** | 17k+ | 规范化提交信息 | `npm i commitizen` |
| **conventional-changelog** | 8k+ | 自动生成 CHANGELOG | `npm i conventional-changelog-cli` |

### Biome 配置（推荐替代 ESLint + Prettier）
```jsonc
// biome.json
{
  "$schema": "https://biomejs.dev/schemas/1.9/schema.json",
  "organizeImports": { "enabled": true },
  "linter": {
    "enabled": true,
    "rules": {
      "recommended": true,
      "complexity": { "noBannedTypes": "error" },
      "style": { "useConst": "error", "noNonNullAssertion": "warn" }
    }
  },
  "formatter": {
    "enabled": true,
    "indentStyle": "space",
    "indentWidth": 2,
    "lineWidth": 100
  }
}
```

---

## ✨ 动画与交互

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **pmndrs/react-spring** | 29k+ | ⭐ 物理动画库 | `npm i @react-spring/web` |
| **pmndrs/framer-motion** | 25k+ | ⭐ React 声明式动画库（最流行） | `npm i framer-motion` |
| **motiondivision/motion** | 28k+ | ⭐ Framer Motion 继任者（框架无关） | `npm i motion` |
| **greensock/GSAP** | 20k+ | 专业动画库（时间线/滚动） | `npm i gsap` |
| **airbnb/lottie-web** | 31k+ | After Effects 动画渲染 | `npm i lottie-web` |
| **animejs/anime** | 50k+ | 轻量动画库 | `npm i animejs` |
| **pmndrs/react-three-fiber** | 28k+ | ⭐ Three.js React 渲染器（3D） | `npm i @react-three/fiber` |
| **pmndrs/ drei ** | 8k+ | React Three Fiber 辅助库 | `npm i @react-three/drei` |
| **wellyshen/react-cool-dimensions** | 2k+ | 元素尺寸/ IntersectionObserver Hook | `npm i react-cool-dimensions` |
| **floating-ui/floating-ui** | 30k+ | ⭐ 浮动元素定位（Tooltip/Popover/Dropdown） | `npm i @floating-ui/react` |

### Framer Motion (Motion) 最佳实践
```tsx
import { motion, AnimatePresence } from 'motion/react'

// 进入/退出动画
<motion.div
  initial={{ opacity: 0, y: 20 }}
  animate={{ opacity: 1, y: 0 }}
  exit={{ opacity: 0, y: -20 }}
  transition={{ type: 'spring', stiffness: 300, damping: 25 }}
/>

// 列表动画
<AnimatePresence>
  {items.map(item => (
    <motion.div
      key={item.id}
      layout
      initial={{ opacity: 0 }}
      animate={{ opacity: 1 }}
      exit={{ opacity: 0 }}
    />
  ))}
</AnimatePresence>

// 手势交互
<motion.div
  whileHover={{ scale: 1.05 }}
  whileTap={{ scale: 0.95 }}
  drag="x"
  dragConstraints={{ left: -100, right: 100 }}
  onDragEnd={(_, info) => console.log(info.offset.x)}
/>
```

### CSS 动画最佳实践
```css
/* 高性能动画 — 仅使用 transform 和 opacity */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}

.animate-in {
  animation: fadeIn 0.3s ease-out;
  /* GPU 加速 */
  will-change: transform, opacity;
}

/* 滚动驱动动画（Chrome 115+） */
@keyframes reveal {
  from { opacity: 0; scale: 0.8; }
  to { opacity: 1; scale: 1; }
}

.reveal-card {
  animation: reveal linear both;
  animation-timeline: view();
  animation-range: entry 0% entry 100%;
}
```

---

## 📊 数据可视化

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **d3/d3** | 110k+ | ⭐ 底层数据可视化库（强大但陡峭） | `npm i d3` |
| **apache/echarts** | 63k+ | ⭐ 成熟图表库（中文生态丰富） | `npm i echarts` |
| **chartjs/Chart.js** | 66k+ | ⭐ 轻量 Canvas 图表 | `npm i chart.js` |
| **plotly/plotly.js** | 17k+ | 交互式图表 | `npm i plotly.js-dist-min` |
| **pmndrs/react-three-fiber** | 28k+ | ⭐ Three.js React 渲染器（3D 可视化） | `npm i @react-three/fiber` |
| **airbnb/visx** | 20k+ | ⭐ D3 React 组件化封装 | `npm i @visx/xychart` |
| **recharts/recharts** | 25k+ | ⭐ React 图表库（基于 D3） | `npm i recharts` |
| **observablehq/plot** | 5k+ | 简洁数据可视化 | `npm i @observablehq/plot` |
| **nvidia/neuralangelo** | 4k+ | 3D 重建可视化 | 见项目文档 |
| **tremorlabs/tremor** | 17k+ | ⭐ React 仪表板组件（Tailwind + Recharts） | `npm i @tremor/react` |

### ECharts React 示例
```tsx
import ReactECharts from 'echarts-for-react'

function LineChart() {
  const option = {
    xAxis: { type: 'category', data: ['Mon', 'Tue', 'Wed'] },
    yAxis: { type: 'value' },
    series: [{ data: [150, 230, 224], type: 'line', smooth: true }],
    tooltip: { trigger: 'axis' },
  }
  return <ReactECharts option={option} style={{ height: 400 }} />
}
```

### Recharts 示例
```tsx
import { LineChart, Line, XAxis, YAxis, Tooltip, ResponsiveContainer } from 'recharts'

const data = [
  { month: 'Jan', revenue: 4000, cost: 2400 },
  { month: 'Feb', revenue: 3000, cost: 1398 },
]

function RevenueChart() {
  return (
    <ResponsiveContainer width="100%" height={300}>
      <LineChart data={data}>
        <XAxis dataKey="month" />
        <YAxis />
        <Tooltip />
        <Line type="monotone" dataKey="revenue" stroke="#8884d8" strokeWidth={2} />
      </LineChart>
    </ResponsiveContainer>
  )
}
```

---

## 🧱 组件开发与管理

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **storybookjs/storybook** | 86k+ | ⭐ 组件文档/开发/测试环境 | `npx storybook@latest init` |
| **ladle.dev/ladle** | 3k+ | 极速组件开发环境（Vite 驱动） | `npm i @ladle/react` |
| **argos-ci/argos** | 2k+ | 视觉回归测试 | `npm i @argos-ci/cli` |
| **bit-tasks/bit** | 18k+ | 组件驱动开发平台 | `npx @teambit/bvm install` |
| **radix-ui/primitives** | 17k+ | ⭐ 无样式无障碍组件原语 | `npm i @radix-ui/react-dialog` |
| **react-aria/react-aria** | 13k+ | ⭐ Adobe 无障碍 React Hooks | `npm i react-aria-components` |
| **downshift-js/downshift** | 12k+ | 输入/选择框原语 | `npm i downshift` |
| **reach/reach-ui** | 5k+ | 无障碍组件库 | `npm i @reach/dialog` |

### 组件设计原则
```tsx
// ✅ 组件设计 — 组合优于配置
interface ModalProps {
  trigger: React.ReactNode
  children: React.ReactNode
  open?: boolean
  onOpenChange?: (open: boolean) => void
}

// ✅ 使用 Composition 模式
<Modal>
  <Modal.Trigger>Open</Modal.Trigger>
  <Modal.Content>
    <Modal.Header>
      <Modal.Title>Title</Modal.Title>
    </Modal.Header>
    <Modal.Body>Content here</Modal.Body>
    <Modal.Footer>
      <Modal.Close>Close</Modal.Close>
    </Modal.Footer>
  </Modal.Content>
</Modal>

// ✅ 使用 `asChild` 模式（Radix UI 方式）
<Button asChild>
  <a href="/dashboard">Go to Dashboard</a>
</Button>

// ❌ 避免 Props 爆炸
<Modal
  triggerText="Open"
  title="Title"
  bodyText="Content"
  footerButtons={['Close', 'Save']}
  onSave={handleSave}
  size="lg"
  // ...
/>
```

---

## 📱 移动端与跨平台

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **facebook/react-native** | 122k+ | ⭐ 原生移动应用（React） | `npx react-native init` |
| **expo/expo** | 38k+ | ⭐ React Native 开发平台（推荐） | `npx create-expo-app` |
| **flutter/flutter** | 170k+ | Google 跨平台 UI 工具包 | 官网下载 |
| **tauri-apps/tauri** | 107k+ | ⭐ Rust 跨平台桌面应用 | `npm i @tauri-apps/cli` |
| **electron/electron** | 116k+ | 传统跨平台桌面应用 | `npm i electron` |
| **capacitor-community/capacitor** | 13k+ | Web → 原生移动应用桥接 | `npm i @capacitor/core` |
| **nativescript/nativescript** | 24k+ | 原生跨平台框架 | `npm i nativescript` |
| **ionic-team/ionic** | 51k+ | Web 技术移动框架 | `npm i @ionic/react` |

### 跨平台选型指南
| 场景 | 推荐方案 | 优势 |
|------|---------|------|
| 移动 App（简单-中等） | **Expo (React Native)** | 快速开发、热更新、丰富插件 |
| 移动 App（复杂/原生） | **React Native CLI** | 完全原生控制 |
| 桌面 App（轻量） | **Tauri** | 包体积小（<10MB）、Rust 性能 |
| 桌面 App（成熟生态） | **Electron** | 成熟稳定、VS Code 同款 |
| 跨平台全端 | **Flutter** | 高性能 Canvas 渲染 |

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

## 🌍 国际化 (i18n)

| 项目 | Stars | 用途 | 安装 |
|------|-------|------|------|
| **i18next/i18next** | 7k+ | ⭐ 通用国际化框架 | `npm i i18next` |
| **i18next/react-i18next** | 9k+ | React i18n | `npm i react-i18next` |
| **intlify/vue-i18n** | 4k+ | Vue i18n 官方 | `npm i vue-i18n` |
| **formatjs/formatjs** | 14k+ | ⭐ 国际化消息格式化（Fluent API） | `npm i @formatjs/intl` |
| **niuteam/typesafe-i18n** | 2k+ | 类型安全 i18n | `npm i typesafe-i18n` |
| **lingui/js-lingui** | 5k+ | React i18n 编译时 | `npm i @lingui/react` |

### react-i18next 最佳实践
```tsx
// i18n.ts
import i18n from 'i18next'
import { initReactI18next } from 'react-i18next'

i18n.use(initReactI18next).init({
  resources: {
    zh: { translation: { welcome: '欢迎回来' } },
    en: { translation: { welcome: 'Welcome back' } },
  },
  lng: 'zh',
  fallbackLng: 'en',
})

// Component
import { useTranslation } from 'react-i18next'

function Welcome() {
  const { t, i18n } = useTranslation()
  return (
    <div>
      <h1>{t('welcome', { name: 'User' })}</h1>
      <button onClick={() => i18n.changeLanguage('en')}>English</button>
    </div>
  )
}
```

---

## ⚡ 性能优化

### 核心指标（Web Vitals）
| 指标 | 说明 | 目标 |
|------|------|------|
| **LCP** (Largest Contentful Paint) | 最大内容渲染 | < 2.5s |
| **FID** (First Input Delay) / **INP** | 首次交互延迟 / 交互到下次渲染 | < 100ms / < 200ms |
| **CLS** (Cumulative Layout Shift) | 累积布局偏移 | < 0.1 |
| **TTFB** (Time to First Byte) | 首字节时间 | < 800ms |
| **TBT** (Total Blocking Time) | 总阻塞时间 | < 300ms |

### 优化技术速查

```tsx
// 1. 懒加载组件
const HeavyComponent = lazy(() => import('./HeavyComponent'))

<Suspense fallback={<Spinner />}>
  <HeavyComponent />
</Suspense>

// 2. 图片优化（Next.js）
import Image from 'next/image'
<Image
  src="/hero.jpg"
  alt="Hero"
  width={1200}
  height={600}
  priority  // LCP 图片加此属性
  loading="lazy"
  placeholder="blur"
/>

// 3. React.memo + useMemo + useCallback
const ExpensiveList = memo(function ExpensiveList({ items }: {
  items: Item[]
}) {
  return items.map(item => <Item key={item.id} {...item} />)
})

function Parent({ items }: { items: Item[] }) {
  const sorted = useMemo(
    () => [...items].sort((a, b) => a.name.localeCompare(b.name)),
    [items]
  )
  const handleClick = useCallback((id: string) => {
    console.log('Clicked', id)
  }, [])

  return <ExpensiveList items={sorted} onItemClick={handleClick} />
}

// 4. 虚拟列表（大量数据）
import { Virtuoso } from 'react-virtuoso'
<Virtuoso
  style={{ height: 400 }}
  totalCount={10000}
  itemContent={index => <Row index={index} />}
/>

// 5. Web Worker 计算
const worker = new Worker(
  new URL('./heavy-calculation.worker.ts', import.meta.url),
  { type: 'module' }
)
worker.postMessage({ data })
worker.onmessage = (e) => setResult(e.data)
```

### 性能工具
| 项目/工具 | 用途 |
|-----------|------|
| **Google Lighthouse** | 性能/SEO/无障碍审计（Chrome DevTools） |
| **web.dev/measure** | Web Vitals 在线测量 |
| **Chrome DevTools Performance** | 运行时性能分析 |
| **bundlephobia.com** | npm 包大小/依赖分析 |
| **webpack-bundle-analyzer** | 打包体积分析 |
| **vite-plugin-visualizer** | Vite 打包分析 |
| **clinicjs/clinic** | Node.js 性能诊断 |
| **pixi-sharp/bling** | 运行时性能监控 |

---

## ♿ 无障碍访问 (a11y)

### ARIA 使用原则
```tsx
// ✅ 正确使用 ARIA
<button
  aria-label="Close dialog"
  aria-expanded={isOpen}
  onClick={handleClose}
>
  <XIcon aria-hidden="true" />
</button>

// ❌ 不要重复语义（原生元素自带动词）
<button role="button">Submit</button>          // ❌ 冗余
<button>Submit</button>                        // ✅

// ✅ 使用语义 HTML
<nav aria-label="Main navigation">
  <ul role="list">
    <li><a href="/">Home</a></li>
  </ul>
</nav>
```

### 无障碍最佳实践
| 实践 | 说明 |
|------|------|
| **语义 HTML** | 使用 `<nav>`, `<main>`, `<aside>`, `<article>` 等 |
| **焦点管理** | 模态框捕获焦点、Tab 键顺序合理 |
| **颜色对比度** | WCAG AA (4.5:1) / AAA (7:1) |
| **alt 文本** | 所有 `<img>` 必须有 alt |
| **键盘导航** | 所有交互元素可用键盘操作 |
| **aria-live** | 动态内容更新时通知屏幕阅读器 |
| **prefers-reduced-motion** | 尊重用户减少动画偏好 |
| **prefers-color-scheme** | 支持暗色模式 |

```css
/* 尊重用户偏好 */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}

@media (prefers-color-scheme: dark) {
  :root { --bg: #1a1a2e; --text: #e0e0e0; }
}
```

### 无障碍检测工具
| 工具 | 用途 |
|------|------|
| **axe DevTools** | 浏览器扩展 a11y 检测 |
| **WAVE** | 网页无障碍评估工具 |
| **Lighthouse** | 内置 a11y 评分 |
| **eslint-plugin-jsx-a11y** | JSX 无障碍 Lint |
| **Accessibility Insights** | Microsoft a11y 检测套件 |

---

## 🤖 AI 辅助前端开发

### AI 代码生成提示词模板

```
生成一个 React 组件：可搜索/多选的下拉框
要求：
- TypeScript 类型安全
- 使用 shadcn/ui 风格的 Tailwind 样式
- 支持键盘导航（上下箭头/回车选择/Esc 关闭）
- 支持远程搜索（debounce 300ms）
- 使用 @tanstack/react-query 获取数据
- 无障碍兼容（ARIA 属性）
```

### AI 前端工作流
```
前端开发最佳 AI 提示顺序：
1. "根据需求生成组件设计/Props 接口"
2. "实现组件骨架（类型定义 + 空状态）"
3. "填充组件逻辑（状态管理/数据流）"
4. "添加样式（Tailwind / CSS Modules）"
5. "添加动画和交互（Framer Motion / CSS transitions）"
6. "添加无障碍支持"
7. "生成 Storybook stories"
8. "生成单元测试 / E2E 测试"
```

### 常用 AI 辅助工具
| 工具 | 用途 |
|------|------|
| **v0.dev** | 文本 → React/Tailwind UI 代码生成 |
| **copilot.lovable.dev** | 自然语言 → 全栈应用 |
| **bolt.new** | 浏览器内 AI 全栈开发 |
| **cursor.ai** | AI 驱动 IDE（前端代码生成） |
| **anima.ai** | Figma 设计稿 → React 代码 |
| **locofy.ai** | Figma/XD → React/Vue 代码 |
| **claude.ai / chatgpt** | UI 组件/布局生成 |

### 前端项目 AI 提示模板

```markdown
## 项目背景
- 框架: Next.js 15 (App Router) + TypeScript
- 样式: Tailwind CSS + shadcn/ui
- 状态管理: Zustand
- 数据获取: TanStack Query
- 测试: Vitest + Playwright

## 开发规范
- 使用函数组件 + Hooks
- Props 用 interface 定义，导出
- 组件使用 default export
- 工具函数使用 named export
- CSS 类名遵循 Tailwind 约定
- 使用 Biome 格式化和 Lint
```

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

## 📚 学习资源

### 官方文档
| 资源 | 链接 |
|------|------|
| **MDN Web Docs** | developer.mozilla.org |
| **React 官方文档 (新版)** | react.dev |
| **Vue 官方文档** | vuejs.org |
| **Next.js 文档** | nextjs.org/docs |
| **Tailwind CSS 文档** | tailwindcss.com/docs |
| **TypeScript 手册** | typescriptlang.org/docs |
| **Vite 指南** | vitejs.dev/guide |
| **Web.dev (Google)** | web.dev/learn |

### 优质教程
| 项目 | Stars | 用途 | 链接 |
|------|-------|------|------|
| **javascript-tutorial/zh.javascript.info** | 20k+ | ⭐ 现代 JS 教程（中文） | github.com/javascript-tutorial |
| **airbnb/javascript** | 146k+ | ⭐ JS 编码规范 | github.com/airbnb/javascript |
| **ryanmcdermott/clean-code-javascript** | 92k+ | ⭐ 整洁代码原则 | github.com/ryanmcdermott/clean-code-javascript |
| **sudheerj/reactjs-interview-questions** | 42k+ | React 面试题 | github.com/sudheerj/reactjs-interview-questions |
| **goldbergyoni/nodebestpractices** | 106k+ | Node.js 最佳实践 | github.com/goldbergyoni/nodebestpractices |
| **dypsilon/frontend-dev-bookmarks** | 45k+ | 前端开发书签 | github.com/dypsilon/frontend-dev-bookmarks |
| **kamranahmedse/developer-roadmap** | 315k+ | ⭐ 开发者路线图 | github.com/kamranahmedse/developer-roadmap |
| **bradtraversy/50projects50days** | 38k+ | 50 个前端实战项目 | github.com/bradtraversy/50projects50days |

### 设计资源
| 资源 | 用途 | 链接 |
|------|------|------|
| **Figma** | UI/UX 设计工具 | figma.com |
| **Dribbble** | UI 设计灵感 | dribbble.com |
| **realtimecolors.com** | 实时配色方案 | realtimecolors.com |
| **coolors.co** | 调色板生成 | coolors.co |
| **fonts.google.com** | 免费字体 | fonts.google.com |
| **unsplash.com** | 免费高清图片 | unsplash.com |
| **icons8.com** | 免费图标 | icons8.com |
| **ui.shadcn.com/themes** | 主题配色 | ui.shadcn.com/themes |

---

> **数据来源**: GitHub Stars, npm trends, MDN Web Docs, awesome-list 生态, 及社区最佳实践。
> 最后更新: 2025年
