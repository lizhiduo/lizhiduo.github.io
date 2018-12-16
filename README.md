# lizhiduo

我的个人博客：<lizhiduo.github.io>, 欢迎 Star 和 Fork。

## 声明

本博客模板基于[mzlogin](https://mazhuang.org/) 修改，感谢！

## 概览

* [效果预览](#效果预览)
* [Fork 指南](#Fork-指南)

## 效果预览

**[在线预览 &rarr;](https://lizhiduo.github.io)**

## Fork 指南

Fork本项目后，还需要做一些修改才能让你的页面**正确**跑起来。

1. 设置你自己的项目名称与分支

   按照按照 GitHub Pages 的规定，名称为 `username.github.io` 的项目的 master 分支，或者其它名称的项目的 gh-pages 分支可以自动生成 GitHub Pages 页面。

2. 修改配置

   网站的配置基本都集中在 \_config.yml 文件中，将其中与个人信息相关的部分替换成你自己的，比如网站的 url、title、subtitle 和第三方评论模块的配置等。

   **评论模块：** 目前支持 disqus、gitment 和 gitalk，选用其中一种就可以了，推荐使用 gitalk。它们各自的配置指南链接在 \_config.yml 文件的 Comments 一节里都贴出来了。如果使用gitalk,你需要创建一个 `blog-comments` 的项目。

3. 删除文章和图片

   如下文件夹中除了 template.md 文件外，都可以全部删除，然后添加你自己的内容。

   * _posts  文件夹中是我已发布的博客文章。
   * _drafts  文件夹中是我尚未发布的博客文章。
   * wiki  文件夹中是我已发布的 wiki 页面。
   * images  文件夹中是我的文章和页面里使用的图片。

4. 修改关于页面

   pages/about.md 文件内容对应网站的「关于」页面，里面的内容多为个人相关，将它们替换成你自己的信息，包括 \_data 目录下的 skills.yml 和 social.yml 文件里的数据。



## 提示

1. gitalk创建和使用可以参考[gitalk使用](https://www.jianshu.com/p/78c64d07124d)。
2. 在本地预览博客效果可以参考[Setting up your Pages site locally with Jekyll][1]。

[1]: https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/
