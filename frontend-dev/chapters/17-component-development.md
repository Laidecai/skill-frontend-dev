---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
