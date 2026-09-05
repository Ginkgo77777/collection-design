# task5 提交范例

> [!WARNING]
> 本目录是 task5 的**提交范例**，仅用于展示建议的文件结构与说明写法，请勿直接复制内容提交。

- 假想的提交者: `example-student`
- 博客地址: `https://example-student.example.com`（示例占位）
- 源码仓库: `https://github.com/example-student/my-blog`（示例占位）
- Figma: `https://www.figma.com/design/xxxxxxxx/personal-blog`（示例占位，需开启查看权限）
- 验证文章: `https://example-student.example.com/posts/first-case-study`（示例占位）

## 本次提交与证据入口

- 提交日期、源码 Commit / Tag、Figma 版本：实际填写。下方验收结果是写法示例，不代表此目录附带可运行博客或已完成测试。
- 项目完整 README：填写 `https://github.com/<user>/<blog>/blob/<commit>/README.md`，链接其中的运行、构建、部署、回滚、维护、迁移与交接章节；本目录保留摘要，不再复制一套全文。
- Figma 文件内保留可编辑 Frame、Component 与 Variables；报告中的视觉差异链接具体节点，标注对应版本。不要用网站截图替代设计源文件。

| 内容 | 文档入口 | 实际提交时补充 |
| --- | --- | --- |
| 定位、信息架构、方案与设计规则 | [设计说明](design/design-notes.md) | 基线与计划、页面 / Token 节点、对应源码 |
| 环境与设计连接方式 | [工作流部署](workflow/workflow-setup.md) | 工具版本；实操与仅了解的部分 |
| 至少三次真实 Agent 协作 | [协作记录](workflow/agent-log.md) | 关键输入、修改文件 / Commit、命令结果与人工决定 |
| 同一任务的 Agent / Web 对照 | [对照报告](workflow/agent-web-comparison.md) | 两方输入、运行证据、错误处理与人工成本 |
| 第三方 Skill 与可复用源文件 | [来源清单](skills/README.md) | 第三方与自研 / 优化后完整 Skill 的固定版本入口 |
| Baseline、评判与新场景复测 | [评测报告](report/skill-benchmark.md) | 输入、输出、原版 / 修改版及人工修正证据 |
| 三篇真实文章与浏览器检查 | [验证记录](workflow/validation.md) | 文章页面和 Markdown 源文件、环境、问题与回归 |
| 实际新增 / 更新文章的维护过程 | [发布 SOP](workflow/publishing-sop.md) | 本次文章与 Commit、发布后检查 |
| 资产与复盘 | [授权清单](assets/LICENSE.md)、[心得](reflection.md) | 真实来源、使用边界与判断依据 |

可按用途附少量小截图、WebP、SVG 或压缩预览图，注明版本与对应问题；实际网站的运行图片和源码在项目中维护。大体积原始素材、批量测试截图与长录屏另行保存并链接，判断依据是实际体积、总量和用途。

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
|    |___ validation.md
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
