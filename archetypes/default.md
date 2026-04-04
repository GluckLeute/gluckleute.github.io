---
date: {{ .Date | time.Format "2006-01-02" }}
draft: false
slug: "{{ .File.ContentBaseName }}"
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
description: ""
tags: []
categories: []
---
