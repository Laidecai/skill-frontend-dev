---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
