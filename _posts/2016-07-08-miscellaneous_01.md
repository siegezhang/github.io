---
layout: post
title: "如何利用GitHub Pages搭建自己的博客"
date: 2016-07-08
---

我们可以利用GitHub Pages搭建自己的博客系统，同时可以利用Jekyll和Markdown，实现博客风格的定制化，那么如何搭建自己的博客系统呢？下面介绍搭建GitHub Pages的基本操作步骤。

-- 第一步，我们按照https://pages.github.com/ 创建博客仓库，其取名按照规范，即username.github.io，其中username为自己注册GitHub的用户名。
-- 第二步，安装Jekyll，按照https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/ 中的操作步骤，先安装Ruby，然后安装Jekyll，其Jekyll实际上是用来解析我们使用*Liquid*语法写的静态页面，同时我们可以使用Jekyll在本地部署博客，在本地正确调试完成之后，再利用Git的相关操作部署到GitHub Pages的服务器上，我们在访问访问服务器上的页面时，服务器同样采用Jekyll解析该模板页面，生成对应的html页面，实际上我们本地安装Jekyll的目的就是为了调试部署。

-- 第三步，为了我们在本地书写博客的方便，我们为该系统添加Markdown的支持，即安装vim的Markdwon的支持，我们在https://github.com/plasticboy/vim-markdown 上下载相应的文件，放入vim的配置文件中，其具体操作步骤可参考该连接。

这样，我们就搭建好了自己的博客网站，其中关于配置Jekyll主题，可参考http://jmcglone.com/guides/github-pages/ 。 
