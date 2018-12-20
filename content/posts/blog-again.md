---
author: "Zhenkuo Liu"
date: 2018-12-21T01:48:10+08:00
title: "第 n 次构建 blog，要简单"
linktitle: Blog Again
---


搜索了下当前比较流行的博客系统，Wordpress、Hexo、Jekyll、Hugo。

不少人用 Wordpress 做过独立站点，虽然生态强大，但独立部署+数据库难免有些臃肿，部署后还需要针对国内网络环境对资源做各种优化。而其余3个本质上是静态文件生成器，并且支持 markdown 语法，托管在 GitHub Pages 非常方便。其中 Hexo 基于 NodeJs，Jekyll 基于 Ruby，Hugo 基于 Go。本质上是不同语言重复造的轮子。

我最终选了 Hugo，单纯对 Go 有好感。