---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date }}'
draft: true
tags:
-
slug: '{{ replace .File.ContentBaseName " " "-" | lower }}'
---
