# 命名规则与标签体系

## 命名规则

- 资产文件名: `类型-名称-版本.扩展名`, 如 `font-siyuanheiti-v2.075.otf`, `icon-camera-16px.svg`
- 版本号: 稳定版 `vN`, 未定稿 `draft-日期`
- 禁止出现 `新建文件夹(2)`、`最终版-真的最终版` 一类不可检索的名字
- 日期一律 `YYYY-MM-DD`

## 标签体系(示例)

| 维度 | 标签示例 |
| --- | --- |
| 内容 | `人物` `风景` `图标` `字体` `纹理` |
| 风格 | `扁平` `赛博` `新中式` `酸性` |
| 场景 | `海报` `Banner` `推文` `UI` |
| 授权 | `cc0` `ofl` `mit` `original` `ai-generated` |
| 项目 | `task2-poster` `task4-app` |
| 状态 | `inbox` `reviewing` `approved` `deprecated` `archived` |

## 元数据(sidecar)

每个资产附 `同名.json`, 至少包含:

```json
{
  "id": "AST-2026-0001",
  "name": "思源黑体 Bold",
  "source": "https://github.com/adobe-fonts/source-han-sans",
  "author": "Adobe",
  "license": "SIL OFL 1.1",
  "acquired_at": "2026-09-01",
  "tags": ["字体", "无衬线", "正文", "ofl"],
  "format": "otf",
  "color_space": "-",
  "size": "16MB",
  "used_in": ["task2-poster", "task4-app"],
  "modified": "无",
  "maintainer": "example-student"
}
```
