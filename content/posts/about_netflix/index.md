---
# weight: 1
title: "关于Netflix的一些事"
date: 2022-10-19T15:57:40+08:00
# lastmod: 2022-09-15T16:45:40+08:00
draft: false
author: "MAN"
# authorLink: "https://dillonzq.com"
description: ""
images: []

tags: ["Netflix"]
categories: ["杂"]

lightgallery: true
---

# 面临的问题

在安卓端，通过clash可以畅通无阻解锁所有剧


但是通过路由器上的clash只能实现自制剧的观看，但好的是没有提示使用代理云云

# 一些探索
在路由器设置界面倒腾一天后我总结出
1. 路由器的dns最终只能给到ss——proxy中的某个第三方dns程序
2. clash中设置的dns好像没用，但是又能体现在我的nslookup里，（使用fake-ip模式）
3. 最后我只能说节点确实能够解锁Netflix但是条件很苛刻，导致在路由器上运行时不论是电脑还是电视都没法看非自制剧

所以电脑端和电视端的检验应该更严格，具体应当通过抓包？反编译等手段来确定了

# 一些吐槽
在网上一搜就是你的节点不解锁云云

或者是你的机场被封什么的

# 思路
还是要找是否dns对这个有影响