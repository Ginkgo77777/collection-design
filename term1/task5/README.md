# task5 AI 融合工作流

任务详情: [learn-design/steps/term1/task5.md](https://github.com/west2-online/learn-design/blob/main/steps/term1/task5.md)

## 提交内容

1. 本任务选题自由(个人博客、自媒体运营、任意设计课题等), 建议将选题项目放在你自己的 GitHub 仓库维护
2. 部署本地 AI 工作流: 安装并使用至少一种 Agent(Codex / Opencode / Claude Code 等), 尝试两类工作流(设计工具 + MCP Server / 文件、代码或开放设计格式)
3. 使用设计术语与 AI 进行可回溯的交互式改进, 保留关键 Prompt、AI 回复摘要、工具与模型信息、生成结果和人工修改记录
4. 分析 AI 生成与修改结果(至少一个成功案例与一个失败案例), 检查来源、授权、隐私与事实性风险
5. 使用并客观评判他人 Skill(保留 Baseline, 至少两个可比的 Skill), 并自行设计或优化一个 Skill
6. 提交到 collection-design 时, 仅需带有:
   - 你评测的 **Skill 源文件或项目地址**
   - **评测报告**
   - **心得体会**
7. 项目主体与自研 Skill 推荐放在你自己的仓库, 将链接放在 README 中

## 目录规范

```txt
term1/task5
|___ README.md          // 本说明文件
|___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|___ <你的 GitHub ID>   // 你的提交目录
```

个人提交目录建议结构:

```txt
<你的 GitHub ID>
|___ README.md               // 选题项目仓库链接 + 本目录说明
|___ skills                  // 评测过的 Skill 源文件(或仅记录链接)
|    |___ README.md          // 来源、版本/Commit、License、适用 Agent 清单
|___ report
|    |___ workflow-setup.md  // 本地 AI 工作流部署记录(Agent、环境、PATH、两类工作流)
|    |___ skill-benchmark.md // Skill 评测报告(Baseline 对照、评判维度、结论)
|    |___ prompts-log.md     // 关键 Prompt 与 AI 回复摘要记录(可选, 也可放在项目仓库)
|___ reflection.md           // 心得体会与总结
```

## 注意

- 不要将 API Key、凭据与私有配置暴露到公网, 使用环境变量或占位值说明
- 运行第三方 Skill 前先检查其说明、修改范围与权限要求

## 参考

- 提交范例: [example/](example/)
