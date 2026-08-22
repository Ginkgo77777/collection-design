# task3 提交范例

> [!WARNING]
> 本目录是 task3 的**提交范例**, 仅用于展示建议的文件结构与说明写法, 请勿直接复制内容提交

- 假想的提交者: `example-student`
- 临摹对象: 「XX 社团公众号」的文章《迎新特辑》排版(示例占位, 实际替换为你选择的公众号与文章)
  - 参考文章链接: `https://mp.weixin.qq.com/s/xxxxxxxx`(示例占位)
- Figma 展示链接: `https://www.figma.com/design/xxxxxxxx/wechat-theme-comparison`(示例占位, 实际替换为你的项目链接, 并开启查看权限)

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

> 两阶段视觉效果统一通过上方 Figma 链接展示, 本提交目录不附预览图。
