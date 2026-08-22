# 资产库目录树(文件树说明)

> 示例结构, 实际提交时替换为你的真实文件树说明, 无需附目录截图或其他预览图

```txt
asset-library
|___ 00-inbox            // 收集暂存, 不过度分类
|___ 10-reference        // 参考库(linkding 导出 + 来源元数据)
|    |___ links          // linkding 导出的书签
|___ 20-general          // 通用资产库(仅 Approved)
|    |___ fonts
|    |    |___ original  // 原始文件
|    |    |___ source    // 可编辑源文件
|    |    |___ export    // 导出文件
|    |___ icons
|    |    |___ original
|    |    |___ source
|    |    |___ export
|    |___ images
|    |    |___ ...
|    |___ svg
|    |    |___ ...
|___ 30-projects         // 项目资产库
|    |___ task2-poster
|    |    |___ original
|    |    |___ source
|    |    |___ export
|    |___ task4-app
|    |    |___ ...
|___ 40-design-system    // 设计系统(Figma Library 导出与说明)
|    |___ tokens
|    |___ components
|    |___ changelog
|___ 50-deprecated       // 废弃但未删除
|___ 60-archive          // 归档
|___ meta                // 元数据与记录
     |___ processing-log.md
     |___ backups.md
```

## 设计取舍

- 每个资产类目内部统一 `original / source / export` 三级目录: 原始文件不破坏, 可编辑源文件与实际交付文件分离
- 用数字前缀固定排序, 新库可插在任意位置
- `meta` 目录只放流程记录, 不放资产, 避免"说明书与货物混放"
