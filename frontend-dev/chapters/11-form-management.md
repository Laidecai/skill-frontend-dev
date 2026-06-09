---
name: frontend-dev
description: '**前端开发专属技能包** — 为前端开发者提供全面的编码指引。'
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



---
> [← 返回主目录](../SKILL.md)
