在 GitHub 上，所有 Markdown 文件（.md）都天然支持插图，不需要特殊“新建”格式。你只需要：

创建一个 .md 文件（例如 README.md 或 doc.md）；
在文件中插入图片的 Markdown 语法；
确保图片资源可被访问（本地上传或远程链接）。
✅ 步骤详解
1️⃣ 创建 Markdown 文件
在 GitHub 仓库中：

点击 Add file → Create new file
文件名以 .md 结尾，如 tutorial.md
点击 Commit new file
2️⃣ 插入图片语法
方式 A：使用本地图片（推荐用于 README）
⚠️ 前提：图片必须已上传到同一仓库中（与 .md 文件同级或子目录）。

![描述文字](images/截图.png)
✅ 示例结构：

your-repo/
├── README.md
└── images/
    └── 截图.png
在 README.md 中写：

![项目截图](images/截图.png)
方式 B：使用远程图片链接（适用于临时展示）
![示例图片](https://example.com/image.png)
⚠️ 注意：链接必须公开可访问，否则图片无法显示。

3️⃣ 上传本地图片（关键步骤！）
如果你想在 README 中显示本地图片，必须先把图片上传到仓库：

在 GitHub 网页端进入你的仓库；
点击 Add file → Upload files；
拖入图片（如 screenshot.png）；
填写提交信息，点击 Commit changes；
然后在 Markdown 中使用相对路径引用。
💡 小技巧：你也可以用 git 命令行同步本地图片：

git add images/screenshot.png
git commit -m "Add screenshot"
git push
🌟 进阶技巧
✅ 图片自适应宽度
![自适应宽度](images/截图.png){width=50%}
⚠️ 注意：GitHub 原生 Markdown 不支持 {width=...} 这种 HTML 属性。
若需控制尺寸，请使用 HTML 标签：

<img src="images/截图.png" width="50%">
✅ 图片作为链接
[点击查看大图](images/大图.png)
✅ 多张图片排版（用 HTML 表格或 flex）
<table>
  <tr>
    <td><img src="img1.png" width="200"></td>
    <td><img src="img2.png" width="200"></td>
  </tr>
</table>
❌ 常见错误
问题	原因	解决
图片显示为红叉或空白	图片未上传到仓库	先上传图片，再用相对路径
路径错误（404）	路径写错（大小写/目录层级）	检查路径，GitHub 路径区分大小写
本地图片无法显示	直接用 file:// 或本地路径	必须上传到 GitHub 仓库
📝 总结
操作	是否支持
新建 .md 文件	✅ 天然支持
插入本地图片	✅ 需先上传到仓库
插入远程链接图片	✅ 直接写 URL
控制图片大小	⚠️ 需用 HTML <img> 标签
使用 + 合并图片？	❌ 不支持（图片不是字典）
