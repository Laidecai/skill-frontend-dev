---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
