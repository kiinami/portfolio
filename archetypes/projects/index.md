---
title: "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date: {{ .Date }}
slug: "{{ .File.ContentBaseName | urlize }}"

description: "Enter the post description (a short SEO-friendly blurb)"
summary: "Enter a brief summary of the post (used in list previews)"
keywords: [""]
techs: ["tech1", "tech2", "tech3"]
state: "finished"
links:
  - name: "GitHub"
    url: "https://github.com/USERNAME/REPO"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "<cover alt text>"
      hidden_in_single : false
---

# Description



# My Work



# What I Learnt



# Links


