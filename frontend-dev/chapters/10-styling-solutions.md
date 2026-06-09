---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
