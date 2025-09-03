---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
slug: {{ substr .File.UniqueID 0 7 }}
description: "这是这篇文章的介绍"
tags: ["分类A", "标签B"]
categories: ["分类A"]
---
