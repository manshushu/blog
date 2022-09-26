---
title: "关于Gitpage的自定义域名"
date: 2022-09-26T11:04:49+08:00
draft: false
description: "关于 MAN"
author: "MAN"

tags: ["疑惑"]
categories: ["网站建设"]

lightgallery: true
---

# 关于我的博客技术栈

使用的是markdown写作，hugo进行静态页面生成，push到blog仓库进行博客源码管理，另有一个仓库负责最后的静态页面托管。

其中第一个仓库使用github的workflow进行页面生成并且推到我的第二个仓库，我认为**问题**应该就出在这个workflow上

# 对于域名
- gitpage的自定义域名是否只能用国外的域名商？（这应该是没道理的）
- 我的域名解析设置没有问题，应该是出错在git仓库中的cname文件上

# 总结来说
应该是workflow设置问题，每次推的时候要将cname一起推过去，同时要怎么设置我的dns？？
