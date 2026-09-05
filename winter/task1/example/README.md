# task1 提交范例

> [!WARNING]
> 本目录是 task1 的**提交范例**，仅用于展示建议的文件结构与说明写法，请勿直接复制内容提交。

- 假想的提交者: `example-student`
- 个人定位: 关注校园数字产品与信息可视化的设计学习者（示例）
- Figma: `https://www.figma.com/design/xxxxxxxx/personal-vi`（示例占位）
- GitHub Profile: `https://github.com/example-student`（示例占位）
- 设计社区主页: `https://www.behance.net/example-student`（示例占位）
- 社交平台主页: `https://space.bilibili.com/xxxxxxxx`（示例占位）
- term1/task5 博客: `https://example-student.example.com`（示例占位）

## 本次版本与证据索引

- 提交日期、Figma 版本与 Profile / 自定义模块的源码 Commit：实际填写。所有地址与下方测试数据均为示例，实际提交需替换并检查查看权限。
- Figma 首 Page 汇总跨平台效果、版本及本 README 反向链接；按 `Final`、`Foundations`、`Components & Assets`、`Templates`、`References & Process` 组织。Pages 不足时可用 Sections，文档链接具体节点。

| 内容 | 文档入口 | 对应设计 / 实施证据 |
| --- | --- | --- |
| 定位、标志、颜色与字体规则 | [VI 说明](brand/vi-guide.md) | Foundations 和组件 / 资产节点 |
| 各平台简介与内容层级 | [平台文案](brand/profile-copy.md) | 真实主页地址、Final 节点 |
| Context 与导出规格 | [适配和检查记录](platforms/context-and-exports.md) | Templates、平台规则来源与实测结果 |
| 资产来源与授权 | [授权清单](assets/LICENSE.md) | 实际使用资产及引用位置 |
| 后续内容运营与面试 | [寒假轮面试索引](#寒假轮面试索引) | task2 作品集、task3 发布 / 复盘 / SOP |

GitHub Profile 的完整 README、自定义 SVG / 组件源码维护在个人仓库，本页填具体文件的固定 Commit 链接。适量压缩预览、小截图、SVG、必要导出文件可放本目录并链接；大型源工程、高清原图与长录屏另存，不以图片格式一概禁止。

GitHub 需实际发布，至少一个自定义模块应能定位到其源码与实际展示位置；设计社区 / 社交平台若暂时无法发布，记录限制、按真实尺寸完成的 Figma 节点与后续补验方式。已有合适的 Logo、字体和 Token 可沿用并说明调整。

## 目录结构

```txt
example
|___ README.md
|___ brand
|    |___ vi-guide.md
|    |___ profile-copy.md
|___ platforms
|    |___ context-and-exports.md
|___ assets
     |___ LICENSE.md
```

## 跨平台衔接与验证摘要

- Identity Token: 头像轮廓、主色语义、标题字体气质与分隔图形保持稳定。
- Platform Mapping: GitHub 强调项目与贡献，设计社区强调案例顺序，社交平台降低信息密度并突出内容栏目。
- 与博客衔接: 复用同一组颜色与图形 Token；各主页均能进入博客 / 作品集，博客也能返回主要平台。
- 3 秒识别: 参与者能认出三个主页属于同一人，但首次未找到博客入口；调整链接层级后通过（示例）。
- 真实访问: 32 px 头像中细节丢失，因此删除次要线条；GitHub 动态卡片失效时保留文字项目列表；深色背景下使用独立反白版本（示例）。

## 寒假轮面试索引

task3 沿用此入口，不新建个人提交目录或单独 PR。可以从 task1 开始规划、发布并积累反馈，面试时统一展示。下面是索引骨架，内容过程记录在自己的博客、项目仓库或资产库中维护。

| 项目 | 入口 |
| --- | --- |
| 个人 VI 与平台主页 | 本页顶部地址及上方证据表 |
| task2 作品集、完整案例与进阶练习 | [task2 提交范例](../../task2/example/README.md)（实际提交改为自己的目录） |
| 运营计划 | 填个人博客 / 项目记录的具体链接及版本，说明定位、栏目、节奏与目标 |
| 数据 / 复盘 | 填记录页及版本，写观察时段、可获得的数据、读者反馈、自己的解释、后续修改 |
| 内容生产 SOP | 填具体文档及版本，覆盖选题、素材、制作、检查、发布、复盘，链接所用模板与授权记录 |
| 封面 / 排版模板 | 填已有 Figma 文件的 Content Templates 节点与版本；无额外视觉稿时无需另建文件 |

| 平台 | 发布日期 | 实际主题 | 具体发布链接 | 过程 / 反馈 / 修改记录 |
| --- | --- | --- | --- | --- |
| 待填 | 待填 | 内容 1 | 待填真实单篇地址 | 待填具体入口 |
| 待填 | 待填 | 内容 2 | 待填真实单篇地址 | 待填具体入口 |
| 待填 | 待填 | 内容 3 | 待填真实单篇地址 | 待填具体入口 |

至少三篇 / 条真实发布。平台不提供数据或观察量少时记录限制，可补读者对标题、阅读和信息入口的反馈，不编造数据。小截图或模板源文件可随既有记录保存，发布视频与大体积原素材使用对应链接。
