# task6 资产库

任务详情: [learn-design/steps/term1/task6.md](https://github.com/west2-online/learn-design/blob/main/steps/term1/task6.md)

## 提交内容

1. 建设个人资产库: 使用 `linkding + TagSpaces + Git / Git LFS + Figma / Penpot` 跑通完整流程, 将 task1-task5 产生的资产收编入库
2. 建立参考库 / 通用资产库 / 项目资产库 / 设计系统的用途划分, 为每类资产补充来源、作者、授权凭证与必要标签
3. 统一文件结构: 原始文件 / 可编辑源文件 / 导出文件分开保存, 使用他人能够理解和检索的文件名
4. 建立 `Inbox / Reviewing / Approved / Deprecated / Archived` 状态区分, 并记录每次状态变化
5. 记录资产信息: 来源、获取时间、授权、格式、色彩空间、尺寸、使用项目与维护者
6. 提交物需包括:
   - README: 目录结构说明、处理记录与复盘内容、环境要求、工具选型与替代方案、命名与标签规则、授权分类、同步与备份策略、其他人如何接手维护
   - 资产库的文件树说明, 无需附目录截图或其他预览图
   - 代表性处理案例(如某个资产的完整生命周期记录)

> [!NOTE]
> 资产库本体通常不直接提交到本仓库(体积大且含授权敏感信息), 提交的是"资产库的说明书": 结构、规则、记录与复盘

## 目录规范

```txt
term1/task6
|___ README.md          // 本说明文件
|___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|___ <你的 GitHub ID>   // 你的提交目录
```

个人提交目录建议结构:

```txt
<你的 GitHub ID>
|___ README.md            // 资产库总说明: 工具选型、环境要求、授权分类、同步与备份、如何接手
|___ structure.md         // 资产库目录树(文件树说明)与四类库的用途划分
|___ naming-and-tags.md   // 命名规则与标签体系
|___ processing-log.md    // 处理记录: 失效链接、来源不明资产、重复文件、超限文件等
|___ cases                // 代表性处理案例
|    |___ case-01-xxx.md  // 某个资产的完整生命周期记录
|___ retrospective.md     // 复盘: 收集习惯改进
```

## 参考

- 提交范例: [example/](example/)
