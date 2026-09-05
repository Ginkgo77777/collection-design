# task5 个人博客、Agent 与 Skill

任务详情: [learn-design/steps/term1/task5.md](https://github.com/west2-online/learn-design/blob/main/steps/term1/task5.md)

## 提交内容

1. 完成个人博客的设计、实现与公网部署，并至少发布或更新一篇真实文章，验证 `写作 -> 检查 -> 构建 -> 发布 -> 回归` 流程。
2. README 需提供可访问的博客、源码仓库与 Figma 链接，并说明 Purpose / Audience / Context、信息架构、技术选型、Design Token、运行部署、维护迁移与资产授权。
3. 使用本地 Agent 完成至少三次需要读取既有项目并修改多个相关文件的真实协作，记录任务边界、关键 Prompt、实际修改、运行命令、失败恢复、验收结果与人工决定。
4. 对同一项真实改动完成 Agent 与 Web 端 AI 对照，比较上下文提供、跨文件修改、运行验证、错误恢复、人工修正成本与适用场景。
5. 保留无 Skill 的 Baseline，使用至少一个第三方 Skill 解决博客中的真实设计或检查问题；记录来源、版本 / Commit、License、依赖、权限与评判结论。
6. 优化该 Skill 或自行设计一个 Skill，提交可复用源文件或固定 Commit 链接；使用新内容或新场景复测，并说明适用范围、失败停止条件、风险与人工确认点。
7. 提交设计说明、Agent / Web 对照、Skill 评测、心得体会、发布维护 SOP 与资产授权清单。项目源码与完整 Skill 可在个人仓库持续维护，本目录保留可审核的说明、记录与稳定链接。

上述协作、Agent / Web 对照、设计连接方式与 Skill 评测可以共用一个博客及一处真实改动。三次协作可连续推进同一功能，但每次要有真实目标、修改与验收；设计连接方式可选一类深入实践，另一类注明仅了解。Agent / Web 对照及 Skill 新场景复测仍需实际完成。

## 目录规范

```txt
term1/task5
|___ README.md          // 本说明文件
|___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|___ <你的 GitHub ID>   // 你的提交目录
```

个人提交目录建议结构：

```txt
<你的 GitHub ID>
|___ README.md                       // 博客/源码/Figma 链接 + 项目说明 + 验收摘要
|___ design
|    |___ design-notes.md            // 定位、信息架构、Token、响应式与设计迭代
|___ workflow
|    |___ workflow-setup.md          // Agent、环境、权限与两类工作流
|    |___ agent-log.md               // 三次真实协作、失败恢复与人工验收
|    |___ agent-web-comparison.md    // 同一任务的 Agent / Web 对照
|    |___ publishing-sop.md          // 发布、回归、维护、备份与迁移
|    |___ validation.md              // 真实文章、浏览器环境、问题与复测
|___ skills
|    |___ README.md                  // 第三方与自研 Skill 的来源、版本和链接
|___ report
|    |___ skill-benchmark.md         // Baseline、第三方与修改版 / 自研版对照
|___ assets
|    |___ LICENSE.md                 // 字体、图片、图标、模板、代码与 AI 内容清单
|___ reflection.md                   // Skill 优缺点、风格化边界与个人结论
```

## 注意

- 按源任务的设计要求提供可查看的 Figma 设计证据，报告可链接具体节点或标注版本的小图；体积合适的预览、截图、WebP、SVG 和必要的小录屏允许提交，不替代实际网站与可编辑设计。
- README 汇总设计、协作、对照、Skill 源文件 / 评判 / 复测、浏览器验证、维护和授权入口；运行与部署等全文以项目 README 为主，给本次 Commit / Tag 与具体文件，不维护两份全文。
- 博客至少用三篇真实文章验证内容表现，并实际新增或更新一篇验证发布维护；必要小型运行资产随项目保留，大原图、复杂工程、长视频另行存储并链接，临时批量截图和重复构建产物不必入库。
- 不提交依赖目录、构建缓存、API Key、Token、Cookie、`.env`、部署凭据、私密对话或无关完整日志。
- 自动构建、Lint、链接检查与浏览器测试是验收证据，不能代替人工视觉判断和真实阅读。
- 运行第三方 Skill 前先阅读说明、依赖、脚本、修改范围与权限要求；无法确认来源或授权的内容不得进入最终交付。

## 参考

- 提交范例: [example/](example/)
