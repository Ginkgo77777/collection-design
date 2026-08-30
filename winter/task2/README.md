# task2 作品集与设计进阶

任务详情: [learn-design/steps/winter/task2.md](https://github.com/west2-online/learn-design/blob/main/steps/winter/task2.md)

## 提交内容

1. 梳理 term1 与寒假轮至今的作品，选择 3~5 个案例并说明选择与放弃理由；提交全部 Case Study 的 Markdown 源文件。
2. 每个案例围绕一个核心问题，覆盖背景与问题、目标与角色、调研与思考、方案与过程、结果与验证、反思，并引用草图、中间版本、反馈与修改前后对照等真实证据。
3. 在 `term1/task5` 博客中完成作品集首页与至少一个案例详情页，提供可访问链接；说明如何复用博客组件与 `winter/task1` Identity Token，以及新增组件的理由。
4. 提交平面设计进阶记录与产出：学习重点、几何构造、辅助线与比例、纯几何 / 光学修正对照、一件应用作品、目标媒介与真实尺寸、缩略图 / 实际尺寸 / 目标媒介检查、Critique 与至少一轮迭代。
5. 提交 GAMES101 学习笔记，至少覆盖变换、光栅化与着色；记录个人理解、与 Three.js / 渲染器的对应关系及验证过程，不以 AI 总结代替学习。
6. 提供至少一个可嵌入网页的 Three.js 组件的在线或源码链接，说明相机、灯光、材质等关键参数、与个人 VI 的关系、Agent 协作、人工修改与多端验收。
7. 提交字体、图片、图标、模型、贴图、课程、教程与代码等内容的来源和授权；AI 生成或辅助资产需记录模型、生成时间与人工修改。

> [!NOTE]
> 作品集网站与 Three.js 工程建议在个人仓库持续维护。本目录保留 Case Study 源文、学习记录、必要交付文件和可回溯链接，不重复提交依赖或构建产物。

## 目录规范

```txt
winter/task2
|___ README.md          // 本说明文件
|___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|___ <你的 GitHub ID>   // 你的提交目录
```

个人提交目录建议结构：

```txt
<你的 GitHub ID>
|___ README.md                    // 作品集/源码/Figma/Three.js 链接 + 总结
|___ case-studies
|    |___ README.md               // 作品清单、选择与放弃理由
|    |___ case-01-xxx.md          // 3~5 个 Case Study Markdown 源文件
|    |___ ...
|___ advanced
|    |___ graphic-design
|    |    |___ README.md          // 学习、构造、光学修正、作品、Critique、媒介检查
|    |    |___ deliverables       // 目标媒介所需的必要交付文件
|    |___ games101-notes.md       // 变换、光栅化、着色及个人验证
|___ threejs
|    |___ README.md               // 在线/源码链接、关键参数、VI 衔接与协作记录
|___ assets
|    |___ LICENSE.md              // 全部第三方与 AI 辅助内容清单
```

## 注意

- Case Study 需引用真实过程证据，并明确区分事实、他人反馈与自己的假设。
- Figma、作品集、源码与在线组件链接需开启查看权限，并保证面试时可以访问。
- 平面作业按目标媒介提交必要文件；不要用无关截图或大量预览替代源文件、真实尺寸检查与交付验收。
- 不以 AI 总结代替个人学习笔记，不直接使用未经人工修改与检查的 AI 成品。
- 不提交 `node_modules`、构建缓存、密钥、Token、`.env`、来源不明的模型或无必要的大体积导出。

## 参考

- 提交范例: [example/](example/)
