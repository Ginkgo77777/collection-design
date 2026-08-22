# 处理记录(示例)

> 收编 task1-task5 资产时遇到的问题与处理方式

## 收编范围

| 任务 | 收编内容 |
| --- | --- |
| task1 | 参考链接 32 条(入 linkding)、分析文章 3 篇(Git) |
| task2 | Figma 项目链接、海报参考来源、字体授权记录、可编辑标题字与 Variables |
| task3 | 主题 CSS 2 套、分隔线 SVG、测试文稿 |
| task4 | Figma 组件、Styles、Token、UX 测试记录 |
| task5 | Prompt 记录、Skill 评测报告、AI 生成物(隔离区) |

## 遇到的问题与处理

1. **失效链接**: task1 收集的 32 条链接中 4 条已失效 → 保留标题、原始 URL、来源与失效时间等元数据进 Archived, 不删除记录(可追溯)
2. **来源不明的资产**: 3 张"很久前存的"壁纸无法确认来源 → 停在 Reviewing, 未进入 Approved
3. **重复文件**: 同一张星空图在 task2 与 task4 各存一份 → 归一化后保留通用库唯一副本, 项目库记录引用关系
4. **超限文件**: 一段 300MB 录屏 → 原始文件存 NAS, 仓库只记录文件位置、大小、格式与授权信息
5. **AI 生成物**: task5 的 AI 生成图片 → 记录模型、时间、Prompt 后放隔离区, 未确认授权不进通用库

## 状态变化记录(节选示例)

| 资产 | 状态流转 | 负责人 | 时间 |
| --- | --- | --- | --- |
| AST-2026-0001 思源黑体 | Inbox → Reviewing → Approved | example-student | 2026-09-01 |
| AST-2026-0004 星空壁纸 | Inbox → Reviewing(来源不明, 滞留) | example-student | 2026-09-02 |
| AST-2026-0007 失效链接 | Approved → Archived | example-student | 2026-09-05 |
