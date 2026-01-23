---
title: "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date: {{ .Date }}
slug: "{{ .File.ContentBaseName | urlize }}"

description: "Enter the post description (a short SEO-friendly blurb)"
summary: "Enter a brief summary of the post (used in list previews)"
keywords: ["SEO keyword 1", "SEO keyword 2", "SEO keyword 3"]
tags: ["tag a", "tag b", "tag c"]

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "<cover alt text>"
      hidden_in_single : true
---

# Description



# My Work



# What I Learnt



# Links


