# task2 提交范例

> [!WARNING]
> 本目录是 task2 的**提交范例**，仅用于展示建议的文件结构与说明写法，请勿直接复制内容提交。

- 假想的提交者: `example-student`
- 作品集页面: `https://example-student.example.com/portfolio`（示例占位）
- 博客源码: `https://github.com/example-student/blog`（示例占位）
- 平面练习 Figma: `https://www.figma.com/design/xxxxxxxx/graphic-study`（示例占位）
- Three.js 在线页面 / 源码: `https://example-student.example.com/lab/brand-orbit` / `https://github.com/example-student/brand-orbit`（示例占位）

## 提交版本与证据索引

- 日期、博客源码 Commit / Tag、Figma 版本：实际填写。示例地址和记录骨架不构成已发布或已验证的作品。
- 项目 README：填写固定 Commit 下的文件链接及运行 / 部署章节，Three.js 若为独立项目则另填其 README 和入口文件。

| 内容 | 文档入口 | 需要能定位的证据 |
| --- | --- | --- |
| 作品清单与 3~5 个完整案例 | [案例索引](case-studies/README.md) | 每篇 Markdown 源文件、已上线具体页面或未上线标记 |
| Case Study 结构示例 | [校园服务案例](case-studies/case-01-campus-service.md) | 真实记录、节点、反馈、迭代与贡献范围 |
| 平面进阶练习与应用 | [平面设计记录](advanced/graphic-design/README.md) | 几何辅助线、光学修正、Critique、必要媒介输出及检查 |
| 图形学学习 | [GAMES101 笔记](advanced/games101-notes.md) | 至少变换、光栅化、着色的理解、对应关系与验证过程 |
| Three.js 组件 | [演示与运行说明](threejs/README.md) | 在线演示或可复现本地运行、源码版本与入口、参数和验证 |
| 资产来源与授权 | [授权清单](assets/LICENSE.md) | 字体、图片、模型、贴图与代码等实际使用项 |

Figma 首 Page 展示作品集页面与平面进阶成果，标明版本和本 README；`Final` 放页面 / 作品，`Foundations / Components & Assets` 放复用规则与资产，`References & Process` 放参考、辅助线、几何 / 光学对照、Critique 和修改。可分文件，需在本页逐一给入口和关键节点链接。Three.js 的静帧、结构和参数对照放笔记，实际场景通过网页 / 本地运行检查，源代码和运行资产在项目中维护。

Case Study 配图、辅助线和光学对照、实际尺寸检查照片、SVG 及必要的小型导出可直接提交；按阅读需要压缩且保留待检查细节。送印 PDF、大型 3D 工程、模型贴图与视频按实际体积另存并链接，保留原始质量的来源。

作品集移动 / 桌面、浅色 / 深色阅读检查需记录页面与版本、视口、长文 / 图片 / 章节导航的操作和结果、问题修改及复测，可写在项目 README 的验证章节并在本页链接。

## 目录结构

```txt
example
|___ README.md
|___ case-studies
|    |___ README.md
|    |___ case-01-campus-service.md
|___ advanced
|    |___ graphic-design
|    |    |___ README.md
|    |___ games101-notes.md
|___ threejs
|    |___ README.md
|___ assets
     |___ LICENSE.md
```

> 实际提交需包含 3~5 个完整 Case Study，并在平面设计目录补充符合目标媒介的必要交付文件；本范例只放骨架文件，用来说明叙事与记录结构。

## 与前序任务的衔接

- 作品集复用 `term1/task5` 博客的文章排版、Color / Spacing / Typography Token，并新增案例目录卡片与章节导航。
- 作品集与 Three.js 组件使用 `winter/task1` 的主色和图形语言；动态组件提供减少动态效果的模式，不影响正文阅读。
