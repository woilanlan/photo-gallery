# photo-gallery

图片管理

目录组成考虑因素：

1. 当一个文件夹文件过多的话，每次打开就会很慢（按日期存放）
2. 文件重名，会覆盖之前文件（使用uuid文件重命名保证唯一）
3. 项目后期的迁移和维护（按项目分类）

文件名：

对于博客的话，图片依赖文章存在，图片复用程度低，可以直接使用截图工具生成的命名：年月日时分秒.png

目录：项目名/2019/11/12/文件名.png
