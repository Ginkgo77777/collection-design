# task3 公众号排版

任务详情: [learn-design/steps/term1/task3.md](https://github.com/west2-online/learn-design/blob/main/steps/term1/task3.md)

## 提交内容

1. 使用 [doocs/md](https://github.com/doocs/md) 搭建本地公众号排版工作流, 记录环境配置与启动步骤
2. 临摹自选公众号文章的排版主题, 至少覆盖标题、二级与三级标题、正文、强调、引用、列表、链接、图片、图片说明、分隔线、文末信息、表格与代码块
3. 在临摹基础上优化或重新设计主题, 并说明目标读者、使用场景、视觉方向与主要取舍
4. 提交物需包括:
   - 临摹的公众号链接、统一测试文稿、临摹主题、优化/重设计主题、CSS、可编辑 SVG、主题所需资产、两阶段预览图、参考分析与工作记录
   - README 说明目录结构、环境要求、启动方式、主题使用方法、常见内容如何套用、如何替换颜色与 SVG、怎样交付结果
   - README 中记录参考公众号与文章、第三方代码和资产的来源及授权, 说明临摹内容只用于学习与考核, 区分原创、修改和引用的部分
5. 注意 `.gitignore` 规范: 不提交依赖目录、构建缓存、无必要的重复导出文件、账号密码、Cookie、Token、`.env` 或微信公众号后台凭据; 图床与 Draft API 等外部服务使用占位配置或环境变量说明

## 目录规范

```txt
term1/task3
|___ README.md          // 本说明文件
|___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|___ <你的 GitHub ID>   // 你的提交目录
```

个人提交目录建议结构:

```txt
<你的 GitHub ID>
|___ README.md              // 目录结构、环境与启动、主题使用与交付说明、参考与授权记录
|___ .gitignore             // 任务级忽略规则(依赖、缓存、凭据)
|___ content                // 内容层
|    |___ test-post.md      // 统一测试文稿(两个主题共用, 用于对照)
|___ themes
|    |___ imitated          // 临摹主题
|    |    |___ theme.css
|    |    |___ assets       // 可编辑 SVG 资产
|    |___ redesigned        // 优化/重设计主题
|         |___ theme.css
|         |___ assets
|___ preview                // 两阶段预览图(同一测试文稿的对照)
|___ analysis               // 参考分析与工作记录
     |___ reference-analysis.md
     |___ worklog.md
```

## 注意

- SVG 必须可编辑且有正确的 `viewBox`, 不得用不可编辑的截图代替图形资产
- 临摹的目的是理解主题的构成与实现方式, 不得将参考公众号的品牌标识或专属资产用于对外发布

## 参考

- 提交范例: [example/](example/)
