---
layout: post
title: 在GitHub上搭建自己的Jekyll博客
category: 工具
tags: [GitHub, Jekyll, Markdown]
description: 搭建一个基于GitHub和Jekyll的博客
---

### GitHub
GitHub不用多说，具有版本管理功能的代码仓库，[官网](www.github.com)

### Jekyll
Jekyll是一个简单的用来生成静态页面的工具，不光能生成博客。[项目位置](https://github.com/mojombo/jekyll)，[项目Wiki](https://github.com/mojombo/jekyll/wiki)

### 为什么用GitHub和Jekyll搭建博客
GitHub不仅具有代码托管功能，而且GitHub Pages提供了域名访问功能，支持静态页面的访问，同时完美支持Jekyll。
搭建好后，博客的发布非常简单：

- 采用[Markdown](http://wowubuntu.com/markdown/)写博客内容，保存成.md文件并存放至_posts文件夹下。
- 将新生成的.md文件提交到GitHub相关目录下。

### Jekyll本地环境的搭建
如果不在本地搭建Jekyll环境，那么我们只能将新博客内容push到GitHub后才能看到网站效果。而在本地搭建Jekyll环境后，通过Jekyll serve命令就可以在本地启动博客网站，通过http://localhost:4000/来查看网站效果。