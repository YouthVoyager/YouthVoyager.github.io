---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
lastmod: {{ .Date }}
author: ["YouthVoyager"]
draft: true

# 核心分类配置
categories: 
  - "后端开发" # 这里可以写一个最常用的默认值
tags: 
  - "待分类"   # 提醒自己记得改标签

# PaperMod 主题配置
description: "这是一句简短的描述，会显示在文章列表中，也会被 SEO 抓取。"
weight: 0 # 默认不置顶（1是置顶）

cover:
  image: "" # 例如: img/cover.jpg
  alt: ""
  caption: ""
  relative: false

comments: true
showToc: true
---

