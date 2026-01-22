---
title           : "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date            : {{ .Date }}
slug            : "{{ .File.ContentBaseName | urlize }}"  # slug (URL segment) for this post

description     : "Enter the post description (a short SEO-friendly blurb)"
summary         : "Enter a brief summary of the post (used in list previews)"
keywords        : ["SEO keyword 1", "SEO keyword 2", "SEO keyword 3"]
tags            : ["tag a", "tag b", "tag c"]

params:
  neso:
    show_toc   : false  # show the table of contents
    cover:     # cover image settings (remove this whole block if you have no cover)
      image    : "header.png"  # just put the filename if the cover lives in the same bundle as the md
      alt_text : "<cover alt text>"   # optional; accessibility text
      hidden_in_single : true
---

# Description



# My Work



# Links


