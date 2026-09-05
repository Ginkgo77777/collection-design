# task3 提交范例

> [!WARNING]
> 本目录是 task3 的**提交范例**, 仅用于展示建议的文件结构与说明写法, 请勿直接复制内容提交

- 假想的提交者: `example-student`
- 临摹对象: 「XX 社团公众号」的文章《迎新特辑》排版(示例占位, 实际替换为你选择的公众号与文章)
  - 参考文章链接: `https://mp.weixin.qq.com/s/xxxxxxxx`(示例占位)
- Figma 展示链接: `https://www.figma.com/design/xxxxxxxx/wechat-theme-comparison`(示例占位, 实际替换为你的项目链接, 并开启查看权限)
- 本次日期 / 版本：`<日期> / <主题 Commit 或版本> / <Figma 版本>`。示例中的命令、结论与地址需按实际项目替换，不表示本目录已经完成部署验证。

## 阅读与源文件入口

- 内容：[统一测试文稿](content/test-post.md)。
- 临摹：[CSS](themes/imitated/theme.css)、[可编辑 SVG](themes/imitated/assets/divider.svg)。
- 重设计：[CSS](themes/redesigned/theme.css)、[可编辑 SVG](themes/redesigned/assets/divider.svg)。
- 依据：[参考分析](analysis/reference-analysis.md)、[环境、流程与工作记录](analysis/worklog.md)、[验证记录](analysis/validation.md)、[来源与授权](#参考与授权记录)。
- Figma 首 Page 放两版对照、版本与本 README 链接；后续按 `Final / Foundations / References & Process` 保存渲染、排版规则、参考与修改。具体节点链接填写在验证记录中，不必手工重排文章。
- 若主题在个人项目维护，补本次 Commit 下的文稿、CSS / SVG、运行 README 链接，并以它们为主版本。

## 目录结构

```txt
example
|___ README.md                // 本说明文件
|___ .gitignore               // 任务级忽略规则
|___ content
|    |___ test-post.md        // 统一测试文稿
|___ themes
|    |___ imitated            // 临摹主题
|    |    |___ theme.css
|    |    |___ assets
|    |         |___ divider.svg
|    |___ redesigned          // 优化/重设计主题
|         |___ theme.css
|         |___ assets
|              |___ divider.svg
|___ analysis
     |___ reference-analysis.md   // 参考主题分析
     |___ worklog.md              // 环境配置与工作记录
     |___ validation.md           // 版本、宽度、实际内容、修改与复查
```

## 环境要求与启动方式

- Node.js `>= 22`(或 Docker)
- 启动:

```bash
# 方式一: npm cli
npm i -g @doocs/md-cli
md-cli          # 默认 http://localhost:8800

# 方式二: Docker
docker run -d -p 8080:80 doocs/md:latest   # http://localhost:8080
```

- 使用方法: 打开编辑器 → 粘贴 `content/test-post.md` 的 Markdown 源文 → 在"主题"面板粘贴对应 `theme.css` → 预览 → 复制渲染结果到公众号后台

## 主题使用方法

1. 两个主题共用 `content/test-post.md`, 便于对照效果
2. 将 `themes/<主题>/theme.css` 全文粘贴到 doocs/md 的"自定义 CSS"中
3. 替换颜色: 修改 CSS 顶部 `:root` 中的变量即可, 不需要逐段调整
4. 替换 SVG 装饰: 将 `themes/<主题>/assets/divider.svg` 重新导出(如修改配色)后, 替换主题配置中的对应图片地址
5. 交付方式: 编辑器预览页"复制"或通过 Draft API 推送到公众号草稿箱(凭据使用环境变量, 见 `analysis/worklog.md`)

## 参考与授权记录

| 内容 | 来源 | 授权 | 性质 |
| --- | --- | --- | --- |
| 临摹排版对象 | 参考公众号文章《迎新特辑》 | 仅用于学习与考核, 不对外发布 | 引用 |
| doocs/md | [github.com/doocs/md](https://github.com/doocs/md) | [WTFPL](https://github.com/doocs/md/blob/main/LICENSE) | 引用 |
| 分隔线 SVG | 基于参考主题样式重绘 | 原创(重构) | 原创 |
| 示例图片 | 本人拍摄 / 已授权图库 | 按实际来源填写 | 原创或引用 |

> 声明: 本提交中的临摹主题仅用于学习与考核, 未将参考公众号的品牌标识或专属资产用于对外发布

> 两版预览、小截图或差异图可按实际体积附在文档中；大幅长截图裁切、压缩或提供链接。CSS / SVG、Markdown 与轻量运行图片随主题保留，截图不替代图形源文件。

## 替代路线如何记录

本例演示 doocs/md 路线。若实际使用秀米，可在相同索引中改填两版可复用模板入口、统一文稿、套用与交付步骤、Figma 对照和验证记录；未开放 CSS / SVG 时说明限制及未实践能力，无需伪造源文件。两条路线都不要求实际发布公众号或配置全部外部服务。
