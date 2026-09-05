# task4 提交范例

> [!WARNING]
> 本目录是 task4 的**提交范例**, 仅用于展示建议的文件结构与说明写法, 请勿直接复制内容提交

- 假想的提交者: `example-student`
- 选题: 虚构软件「拾光」校园失物招领小程序
- Figma 链接: `https://www.figma.com/design/xxxxxxxx/拾光-失物招领小程序`(示例占位, 实际替换为你的项目链接, 并开启查看权限)
- 日期 / 版本：`<本次日期> / <Figma 文件内版本>`。本例展示记录结构，测试数据为示意；真实提交应使用自己的证据。

## 阅读与证据入口

1. [调研与问题定义](research/problem-definition.md)：事实、反馈、假设及来源。
2. [Information Architecture](flows/ia.md) 与 [User Flow](flows/user-flow.md)：本例以 Markdown 为流程主版本，Figma 入口引用它们。
3. 可点击 Prototype：`https://www.figma.com/proto/xxxxxxxx/拾光?node-id=<起始节点>&starting-point-node-id=<起始节点>`（格式占位，替换为实际分享链接）；与 IA / Flow 分开提供。
4. [测试计划](ux-test/test-plan.md)、[观察](ux-test/observations.md)、[修改与复测](ux-test/iterations.md)、[交接与验证范围](handoff.md)。
5. [资产与授权](assets/LICENSE.md)。正式设计、Logo / favicon、图标规则、色版与语义 Token 的节点见下方分区说明，提交时补实际节点入口。

## 项目概览

- 选题背景: 校内失物信息分散在 QQ 群、表白墙与宿舍群, 寻找与发布效率低, 且难以确认"已找回"
- 目标用户: 在校学生(发布者 / 寻找者), 移动端为主
- 核心任务: 从"发布一条失物信息"到"双方建立联系并确认找回"的完整闭环
- 项目范围: 首页信息流、发布表单、详情与联系、我的发布与状态管理, 及空态/错误/权限等边界状态

## 文件结构

```txt
example
|___ README.md                 // 本说明文件
|___ handoff.md                // 交接、版本、使用与验证范围
|___ research
|    |___ problem-definition.md
|___ flows
|    |___ ia.md                // 信息架构(思维导图)
|    |___ user-flow.md         // 核心用户流程
|___ ux-test
|    |___ test-plan.md
|    |___ observations.md
|    |___ iterations.md
|___ assets
|    |___ LICENSE.md           // 资产与第三方内容清单
```

## Prototype 入口与建议体验顺序

- Prototype 入口: Figma 的 `Flows & Prototype` 分区链接到正式界面的 Flow Starting Point；设置与入口均为示例占位，实际提交需验证可点击体验
- 建议体验顺序:
  1. 从首页开始, 完成一次"发布失物"流程
  2. 切换到"寻找者"视角, 完成一次"搜索 → 详情 → 联系发布者"流程
  3. 查看发布者的"已找回"状态流转与消息通知
  4. 体验空状态(新账号)、无权限(未登录发布)与网络错误等边界状态

## 主要设计取舍

- 卡片列表 vs 地图视图: 校园范围小且用户习惯 QQ 群文字, 选择**卡片信息流**为主, 搜索与筛选为辅助
- 表单一次性填完 vs 分步: 失物信息字段少, 采用**单页表单** + 图片可选, 降低发布门槛
- 联系对方: 不使用站内聊天(开发成本高), 用"**一键复制联系方式 + 微信跳转**", 让沟通回到用户熟悉的工具
- 状态流转: 发布者需手动标记"已找回", 防止信息长期悬挂; 系统在 14 天未更新时提醒确认

## 如何查看和复用

- Figma 首 Page 放项目、预览、版本、Prototype 与 README 链接；后续按 `Flows & Prototype / Final / Foundations / Components & Assets / References & Process / Review & Handoff` 组织，可以用 Pages / Sections，正式稿直接承担原型。
- `Foundations` 放 Logo / favicon 小尺寸变体、全局色版及 Primitive -> Semantic Color Token 映射；`Components & Assets` 放图标库规则、修改 / 自制图标、组件及状态，注明正式界面的使用位置。
- `References & Process` 放标识草图、图标比较、重要方案取舍与修改；`Review & Handoff` 对应 [交接说明](handoff.md)，不把文档全文再复制一次。
- 字体、图标与图片的来源和授权见 [清单](assets/LICENSE.md)。允许体积合适的状态截图、修改对照或轻量 SVG；大图 / 长录屏压缩或链接查看，仍需可编辑设计和可点击原型。
