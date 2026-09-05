# 本地 AI 工作流部署记录

## 环境

| 项 | 值 |
| --- | --- |
| Agent | Opencode(示例, 可换 Codex / Claude Code 等) |
| Python | 3.12, 已加入 PATH |
| Node.js | v22, 已加入 PATH |
| Playwright | 1.4x, 用于生成页面截图辅助检查 |
| MCP Server | Figma MCP(社区版, 记录来源与版本)(示例) |

## 部署步骤与验证(示例)

```bash
npm i -g opencode-ai      # 安装 Agent(示例)
python --version          # 验证 Python PATH
node --version            # 验证 Node PATH
playwright install        # 安装浏览器依赖
```

- 验证方式: 让 Agent 读取指定目录上下文、调用 Playwright 截图并输出到约定路径, 均成功
- 凭据管理: API Key 与 MCP 配置写入环境变量与本地配置文件, `.gitignore` 排除, 未进入任何仓库

## 两类设计连接方式：实操与学习比较

本例选择开放格式工作流深入实践；设计工具连接方式仅作为学习比较对象，以下能力描述是待核对的示例分析，不作为已实操证据。实际提交时写明自己选择的路径、版本、输入输出与限制。不要求两类都实操，Agent / Web 对照与 Skill 新场景复测仍需实际完成。

1. **设计工具连接工作流**: Figma + MCP Server(示例)
   - 能执行: 读取文件结构、读取图层与部分变量
   - 局限: 写入操作需逐步确认; 复杂 Auto Layout 的嵌套关系解读经常出错
2. **开放设计格式工作流**: 博客主题的 HTML/CSS 文件(示例)
   - 能执行: 直接修改文件、运行构建、截图自检
   - 优势: 变更可 diff 回溯, 便于人工检查
   - 实际证据填写在 [Agent 协作记录](agent-log.md) 与 [浏览器验证](validation.md)，补充输入文件、修改文件 / Commit 和运行结果。

## 遇到的问题与解决(示例)

- Agent 修改 CSS 时把散落数值写进组件, 与 Token 体系冲突 → 在 prompt 中显式约束"只修改 :root 变量"
- Playwright 截图与浏览器手动查看有差异 → 截图只用于快速检查, 最终结论以人工判断为准
