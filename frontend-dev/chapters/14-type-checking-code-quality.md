---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
