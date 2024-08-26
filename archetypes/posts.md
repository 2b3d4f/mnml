---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date }}'
draft: true
categories:
- uncategorized
tags:
-
slug: '{{ replace .File.ContentBaseName " " "-" | lower }}'
---
