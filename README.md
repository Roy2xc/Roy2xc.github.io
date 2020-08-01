Wellcome
## 1

**2**

### 3

### 第三步 发布博文

在你的博客的GitHub代码库页面里，点开_posts文件夹，这里面就是你的博客文章。

这些文章使用的格式是Markdown，文件后缀名是md，这是一种非常简单易用的有格式文本标记语言，你应该已经注意到，在LOFFER自带的示例性博文中有一篇中文的Markdown语法介绍。

更简单的办法是使用[Typora](https://typora.io/)，这是一个全图形化界面，全实时预览的Markdown写作软件，非常轻量，而且免费。

![img](https://raw.githubusercontent.com/FromEndWorld/LOFFER/master/images/Typora.png)

在发布博文前，你需要在文章的头部添加这样的内容，包括你的文章标题，发布日期，作者名，和tag等。

    ---
    layout: post
    title: LOFFER文档
    date: 2019-06-02
    Author: 来自中世界
    categories: 
    tags: [sample, document]
    comments: true
    --- 

完成后，保存为.md文件，文件名是date-标题，例如 2019-06-02-document.md (注意这里的标题会成为这个post的URL，所以推荐使用字母而非中文，它不影响页面上显示的标题)，然后上传到_posts文件夹，commit，很快就可以在博客上看到新文章了。
