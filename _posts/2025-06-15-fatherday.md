---
layout: post
title: 四年后的父亲节我在做新闻收集与分析
categories: life
description: father's day little project of parsing news with AI
keywords: father's day, AI, news
---

四年后的父亲节回来写这篇笔记，有点意思。世界大变样。分享一下在树莓派3上收集新闻的小项目：
- Python收取RSS
- cron定时执行，遇到了log权限问题，chmod解决；生成文件使用绝对路径
- Nginx运行静态网页展示
下一步准备：
- 将txt新闻数据转换为db
- 寻找AI分析并预测对经济金融的影响