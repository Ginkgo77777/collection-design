# task5 提交范例

> [!WARNING]
> 本目录是 task5 的**提交范例**，仅用于展示建议的文件结构与说明写法，请勿直接复制内容提交。

- 假想的提交者: `example-student`
- 博客地址: `https://example-student.example.com`（示例占位）
- 源码仓库: `https://github.com/example-student/my-blog`（示例占位）
- Figma: `https://www.figma.com/design/xxxxxxxx/personal-blog`（示例占位，需开启查看权限）
- 验证文章: `https://example-student.example.com/posts/first-case-study`（示例占位）

## 项目概览

- 定位: 用案例和文章展示设计判断，并保留可迁移的长期内容。
- 主要读者: 面试官、同方向学习者与未来的维护者。
- 技术方案: Astro + Markdown + GitHub Actions + GitHub Pages（示例）。
- 设计衔接: 以 Grid / Spacing / Typography / Color / Component Token 连接 Figma 与代码，单独验收深浅色和移动端。

## 目录结构

```txt
example
|___ README.md
|___ design
|    |___ design-notes.md
|___ workflow
|    |___ workflow-setup.md
|    |___ agent-log.md
|    |___ agent-web-comparison.md
|    |___ publishing-sop.md
|___ skills
|    |___ README.md
|___ report
|    |___ skill-benchmark.md
|___ assets
|    |___ LICENSE.md
|___ reflection.md
```

## 验收摘要

| 场景 | 验收内容 | 结果 |
| --- | --- | --- |
| 桌面端 / 浅色 | 首页、文章列表、文章详情与键盘 Focus | 通过（示例） |
| 桌面端 / 深色 | Token、图片与代码块对比度 | 修复 1 处后通过（示例） |
| 移动端 | 导航、长标题、横图与代码块溢出 | 修复 2 处后通过（示例） |
| 发布回归 | 构建、链接、线上文章与回滚入口 | 通过（示例） |

项目源码、自研 Skill 与完整 Prompt 记录维护在个人仓库中；本目录只保留可审核的摘要、对照、评测、授权清单与固定链接，所有凭据均未进入仓库。
