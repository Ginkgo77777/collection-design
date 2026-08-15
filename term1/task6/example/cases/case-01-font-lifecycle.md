# 代表性案例: 思源黑体完整生命周期(示例)

## 生命周期记录

| 阶段 | 记录 |
| --- | --- |
| Collect | 2026-09-01 从 task2 的资产清单进入 Inbox(当时仅存了字体文件, 无来源记录) |
| Review | 补充来源 [Adobe Fonts GitHub](https://github.com/adobe-fonts/source-han-sans), 确认授权 SIL OFL 1.1, 检查与本地既有字体无重复 |
| Normalize | 重命名为 `font-siyuanheiti-v2.075.otf`, 存入 `20-general/fonts/original` |
| Register | 分配 ID `AST-2026-0001`, 补齐 sidecar 元数据(作者、授权、标签、适用场景) |
| Approve | 维护者(本人)确认后进入 Approved, 可在通用库取用 |
| Use | task4 设计稿引用, 在元数据中记录 `used_in: task4-app` |
| Update | 未发生版本更新(示例) |
| Archive | 未归档(示例); 若未来授权变更, 将按影响评估 → 通知项目 → 迁移 → 归档旧版流程处理 |

## 案例说明

这个案例的典型之处在于: 资产在 task2 时"只存了文件", 收编时才补全来源与授权, 因此走了完整的 Inbox → Approved 流程。
教训: **收集时顺手记录来源, 比事后溯源成本低得多**。
