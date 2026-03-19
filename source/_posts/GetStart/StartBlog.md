---
title: The Beginning of a Blog Era
date: 2026-03-19 12:00:00
categories:
  \- Startup
tags:
  \- Log
---
- **这是第一次搭建博客的小小记录**
- 使用的是 Hexo 进行博客管理；目前使用的模板是 `NEXT`

> ```bash
> # 本地预览部署博客情况
> hexo clean
> hexo server
> # 更新远程仓库
> cd D:\Code\GitBlog
> git status
> git add .
> git commit -m "reason of updating"
> git push origin main
> ```

- 所有的博客都会放置在项目的 `\source\_posts` 路径下；由于平时用于编辑 `.md` 文件的 `Typora` 使用的存放路径地址是 `assets/image-xxxx.png ` ，而这种格式又不是 Hexo 所支持的。因此每次上传博客都要修改 `assets → XX (XX.md)` 并删去`.md` 文档中的 `assets/` 相对路径。

- 例如这个博客引用图片就会是这样 （当然 `Typora` 里面不可见了……有点烦😥，有空再研究一下）

![MyLove](profile.jpg)
