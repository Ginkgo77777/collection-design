# task4 UI/UX 设计

任务详情: [learn-design/steps/term1/task4.md](https://github.com/west2-online/learn-design/blob/main/steps/term1/task4.md)

## 提交内容

1. 在 Figma 中完成真实软件场景的 UI/UX 设计(Web / 客户端 / 小程序 / 游戏内界面等), 需支持从进入软件到完成任务并得到结果反馈的完整流程
2. 前期构思: Purpose / Audience / Context、调研依据(访谈/问卷/竞品分析等)、Information Architecture 与 User Flow
3. 中期设计: Responsive Layout、Component System(Variants/Properties/状态)、Design System(Token/Variables/Modes)、Prototyping(流程与动效)、规范的 Pages/Sections/图层命名
4. 后期验证与交付: UX 测试记录与迭代、Dev Mode 或 Annotations 交付说明
5. 提交物需包括:
   - README: Figma 链接(可访问且具有查看权限)、选题背景、目标用户、核心任务、项目范围、文件结构、Prototype 入口、建议体验顺序、主要设计取舍、如何查看和复用
   - 前期调研与问题定义记录(优化已有软件附原流程/界面分析, 虚构软件附需求假设与业务规则)
   - 分别提供 IA、User Flow 与可点击 Prototype；README 给各自主版本入口、Prototype Flow 链接和体验顺序。思维导图 / 流程图不能代替可点击原型
   - UX 测试任务、观察记录、发现的问题、修改前后对照与复测结论
   - 资产与第三方内容清单(来源、授权与修改情况, 区分原创/修改/引用; 字体需说明嵌入与分发授权)
   - 通过 README 中的版本说明与 Figma 文件本身保留可回溯证据
   - Figma 首 Page 放项目、预览、Prototype、版本和 README；其余按 Flows & Prototype / Final / Foundations / Components & Assets / References & Process / Review & Handoff 分区，可合并 Pages / Sections，正式稿可直接承担原型
   - 调研、测试、交接与授权报告链接到具体节点或主版本；测试区分设计已考虑、原型已验证、实现已验证与待验证。无实现侧时做同伴交接走读，不额外要求完整开发
   - 图标库与修改 / 自制过程、Logo / favicon、小尺寸变体、全局色版和 Primitive -> Semantic Color Token 映射应能定位到正式使用位置
   - 允许体积合适的界面、状态、前后对照截图和轻量 SVG；大图 / 长录屏压缩或用合适存储的链接提供，不替代可编辑设计与 Prototype

## 目录规范

```txt
term1/task4
|___ README.md          // 本说明文件
|___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|___ <你的 GitHub ID>   // 你的提交目录
```

个人提交目录建议结构:

```txt
<你的 GitHub ID>
|___ README.md               // 项目总说明 + Figma 链接 + Prototype 入口 + 体验顺序
|___ research                // 前期调研
|    |___ problem-definition.md
|___ flows                   // 信息架构与流程(可用 Mermaid 思维导图/流程图)
|    |___ ia.md
|    |___ user-flow.md
|___ ux-test                 // UX 验证与迭代记录
|    |___ test-plan.md
|    |___ observations.md
|    |___ iterations.md
|___ assets
|    |___ LICENSE.md         // 字体/图标/图片/插件/UI Kit 来源与授权
```

## 参考

- 提交范例: [example/](example/)
