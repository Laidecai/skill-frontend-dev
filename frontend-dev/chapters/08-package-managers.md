---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
