# task1 提交范例

> [!WARNING]
> 本目录是 task1 的**提交范例**, 仅用于展示建议的文件结构与说明写法, 请勿直接复制内容提交。

- 假想的提交者: `example-student`
- 博客地址: `https://example-student.example.com`(示例占位)
- 源码仓库: `https://github.com/example-student/blog`(示例占位)
- Figma: `https://www.figma.com/design/xxxxxxxx/personal-blog`(可选示例占位, 需开启查看权限)

## 项目概览

- 定位: 记录交互设计学习与个人项目复盘
- 主要读者: 面试官、同方向学习者与未来的自己
- 技术方案: Astro + Markdown + GitHub Actions + GitHub Pages(示例)
- 验证文章: `/posts/first-case-study`(示例占位)

## 目录结构

```txt
example
|___ README.md
|___ design
|    |___ design-notes.md
|___ workflow
|    |___ agent-log.md
|    |___ publishing-sop.md
|___ assets
     |___ LICENSE.md
```

## 验收摘要

| 场景 | 验收内容 | 结果 |
| --- | --- | --- |
| 桌面端 / 浅色 | 首页、文章列表、文章详情与键盘焦点 | 通过(示例) |
| 桌面端 / 深色 | Token、图片与代码块对比度 | 修复 1 处后通过(示例) |
| 移动端 | 导航、长标题、横图与代码块溢出 | 修复 2 处后通过(示例) |

详细的设计与人工修改证据分别见 `design/design-notes.md` 和 `workflow/agent-log.md`。
