---
author: "SRE NL"
title: "{{ replace (substr .File.Dir 6 -1) "/" " " | title }}"
date: "{{ time.Now.Format "2006-01-02" }}"
draft: false
description:
tags: []
---

## First presenter (host company)

[title](./files/p1.pdf)

## Second presenter

[title](./files/p2.pdf)
