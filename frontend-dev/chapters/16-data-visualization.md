---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
