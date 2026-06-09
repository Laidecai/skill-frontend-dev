---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
---

## 🌐 核心 Web 技术

### HTML5
| 项目/概念 | 说明 | 链接/资源 |
|-----------|------|-----------|
| **语义化标签** | `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` | MDN HTML |
| **表单元素** | `<input>` 类型（text/number/email/tel/date/range/file/color），`<datalist>`, `<output>` | MDN Forms |
| **媒体元素** | `<video>`, `<audio>`, `<picture>`, `<source>`, `<track>` | MDN Media |
| **Canvas** | 2D 绘图 API，像素级操作 | MDN Canvas |
| **Web Components** | Custom Elements, Shadow DOM, HTML Templates | MDN Web Components |
| **Dialog 元素** | 原生模态框 `<dialog>` | MDN Dialog |
| **可访问性** | ARIA 属性、角色、标签、焦点管理 | MDN ARIA |

### CSS3 / 现代 CSS
| 特性 | 说明 | 用法 |
|------|------|------|
| **Flexbox** | 一维布局（主轴/交叉轴） | `display: flex; justify-content: center;` |
| **Grid** | 二维布局（行列网格） | `display: grid; grid-template-columns: repeat(3, 1fr);` |
| **Container Queries** | 容器尺寸响应式（2023+） | `@container (min-width: 400px) { ... }` |
| **CSS Layers** | 层叠优先级管理（`@layer`） | `@layer base, components, utilities;` |
| **CSS Nesting** | 原生 CSS 嵌套语法（2024+） | `.card { & .title { ... } }` |
| **`:has()` 选择器** | 父级选择器 | `.card:has(img) { ... }` |
| **Subgrid** | 子元素对齐父网格线 | `grid-template-rows: subgrid;` |
| **Scroll-driven Animations** | 滚动驱动动画 | `animation-timeline: scroll();` |
| **View Transitions API** | 页面视图过渡动画 | `document.startViewTransition(...)` |
| **CSS Variables** | 自定义属性 | `--primary: #007bff; var(--primary)` |

### JavaScript / TypeScript 基础
| 特性 | 说明 | 用法 |
|------|------|------|
| **ES Modules** | `import`/`export` 模块系统 | `import { foo } from './bar.js'` |
| **可选链** | 安全深层属性访问 | `obj?.prop?.subprop` |
| **空值合并** | `null`/`undefined` 回退 | `const x = val ?? defaultValue` |
| **Top-level await** | 模块顶层直接 await | `const data = await fetch(url)` |
| **Promise.withResolvers()** | 外部 Promise 控制 | `const { promise, resolve, reject } = Promise.withResolvers()` |
| **Array 方法** | map/filter/reduce/find/some/every/flat/flatMap | 标准用法 |
| **结构化克隆** | 深拷贝 | `structuredClone(obj)` |

---



---
> [← 返回主目录](../SKILL.md)
