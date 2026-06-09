---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
