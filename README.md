# Collection - design

这个仓库用作保存有志于加入西二在线的同学的作业, 这里记录了他们学习过程中的点点滴滴

## 作业仓库

请访问: [west2-online/learn-design](https://github.com/west2-online/learn-design)

这个作业与帮助资料是**不断迭代的**(也就是不断在更新, 可能你做了一半作业发现作业内容变了很多)

但是资料请访问上述仓库, 资料是随时都会更新的, 不过我们还是希望你可以养成一个**自我学习查找**的好习惯, 不要过度依赖他人

## 仓库结构

```txt
collection-design
|___ term1           // 第一学期考核
|    |___ README.md  // 第一学期总览
|    |___ task1      // 每一轮任务的提交目录
|    |    |___ README.md          // 本轮任务的提交说明与目录规范
|    |    |___ example            // 提交范例(仅作格式参考, 请勿抄袭)
|    |    |___ <你的 GitHub ID>   // 你的提交目录, 以 GitHub ID 命名
|    |___ task2
|    |___ task3
|    |___ task4
|    |___ task5
|    |___ task6
|___ winter          // 寒假轮考核
|    |___ README.md  // 寒假轮总览
|    |___ task1      // 博客设计、实现、部署与维护
|    |___ task2      // 个人品牌视觉系统与跨平台主页
|    |___ task3      // 作品集与设计进阶
|    |___ task4      // 面试展示说明(无需仓库提交)
|___ term2           // 第二学期考核(待完善)
|___ summer          // 暑假轮(待完善)
```

## Github入门使用

请查看我们的飞书文档: [Git & GitHub](https://west2-online.feishu.cn/wiki/Lsz9w3CiGinXzgkevtmceHZknrf)

## 提交作业

请查看我们的飞书文档: [如何提交我的作业](https://west2-online.feishu.cn/wiki/Zvqow0CUxig3iWkWQgBcHp4AnHe)

简要流程如下:

1. 创建一个 [Github](https://github.com) 账号
2. 从 [collection-design](https://github.com/west2-online-reserve/collection-design) 仓库创建分支(fork)
3. 克隆(clone)到个人电脑上
4. 阅读 [learn-design](https://github.com/west2-online/learn-design) 的对应任务文档与本仓库的文件树结构, 在对应任务目录下创建以你的 **GitHub ID** 命名的提交目录, 将作业放入其中
5. 需要仓库提交的任务目录下设有 `example` 范例文件夹, 请参照其文件结构组织你的作业, 但**不要直接复制或抄袭**范例内容
6. 创建一次语义合适的提交(commit), 可参考 [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/)
7. 从你的分支仓库, 向本仓库的 main 分支发送一次推送请求(pull request)
8. 等待推送请求被合并到主分支, 或联系考核负责人以通过推送请求

## 提交注意事项

- 请仅提交属于你自己的任务文件, 不要修改 `example` 范例目录与其他同学的提交
- 注意 `.gitignore` 的规范性: 不提交依赖目录、构建缓存、账号密码、Cookie、Token、`.env` 或微信公众号后台凭据
- 设计效果统一通过具有查看权限的 Figma 链接展示, 提交仓库不附预览图; 仅在任务明确要求时提交按实际用途导出的文件, Github 仓库本身并不适合存储大文件
- 提交的图片请使用图床或控制大小, 并注意图片的版权许可
