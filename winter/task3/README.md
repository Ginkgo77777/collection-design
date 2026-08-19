# task3 作品集与设计进阶

任务详情: [learn-design/steps/winter/task3.md](https://github.com/west2-online/learn-design/blob/main/steps/winter/task3.md)

## 提交内容

1. 在博客中完成作品集首页与至少一个案例详情页，提供可访问链接；说明如何复用 task1 的 Design Token 与组件，以及新增组件的理由。
2. 梳理既有作品并选择 3~5 个案例，提交全部 Case Study 的 Markdown 源文件。每个案例需围绕一个核心问题，覆盖背景与问题、目标与角色、调研与思考、方案与过程、结果与验证、反思。
3. 提交平面设计进阶记录与产出：
   - 几何构造练习、完整辅助线与比例关系；
   - 纯几何结果与光学修正结果的对照；
   - 一件应用所学基础的作品、目标媒介与真实尺寸、缩略图/实际尺寸/目标媒介检查；
   - 一次“描述 -> 分析 -> 解释 -> 评价”的 Critique、至少一轮修改和 Figma 链接。
4. 提交 GAMES101 学习笔记，至少覆盖变换、光栅化与着色，并记录概念理解、与 Three.js / 渲染器的对应关系及个人验证过程。
5. 提供至少一个可嵌入网页的 Three.js 组件的可访问链接或源码仓库链接，说明相机、灯光、材质等关键参数、与个人 VI 的关系、Agent 协作与人工修改。
6. 提交字体、图片、图标、模型、贴图、教程与代码等内容的来源和授权；AI 生成或辅助资产需记录模型与生成时间。

> [!NOTE]
> 作品集网站与 Three.js 工程建议在个人仓库持续维护。本目录保留 Case Study 源文、学习记录、关键预览和可回溯链接，不重复提交依赖或构建产物。

## 目录规范

```txt
winter/task3
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
|    |    |___ README.md          // 学习、构造、光学修正、作品、Critique、导出检查
|    |___ games101-notes.md       // 变换、光栅化、着色及个人验证
|___ threejs
|    |___ README.md               // 在线/源码链接、关键参数、VI 衔接与协作记录
|___ assets
|    |___ LICENSE.md              // 全部第三方与 AI 辅助内容清单
|___ preview                      // 压缩后的案例、练习、对照与目标媒介预览
```

## 注意

- Case Study 需引用真实过程证据，并明确区分事实、他人反馈与自己的假设。
- Figma、作品集、源码与在线组件链接需开启查看权限，并保证面试时可以访问。
- 不以 AI 总结代替个人学习笔记，不直接使用未经人工修改与检查的 AI 成品。
- 不提交 `node_modules`、构建缓存、密钥、Token、`.env`、来源不明的模型或无必要的大体积导出。

## 参考

- 提交范例: [example/](example/)
