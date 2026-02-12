---
title: "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date: {{ .Date }}
# endDate: {{ .Date }} # Uncomment and set end date, or remove for current position
slug: "{{ .File.ContentBaseName | urlize }}"

# customDate: "Summers 2020-2023" # Uncomment to use custom date text instead of automatic date range

organization: "Company Name"
location: "City, Country"
type: "work"

description: "Brief role description for SEO"
summary: "One-line summary of your role and main responsibilities"
keywords: ["keyword1", "keyword2", "keyword3"]
techs: ["python", "django", "postgresql"]  # Use tech IDs from hugo.toml

links:
  - name: "Company Website"
    url: "https://example.com"
  # - name: "Project"
  #   url: "https://project-url.com"

params:
  neso:
    show_toc: false
    cover:
      image: "img/logo.png"  # Company/organization logo
      alt_text: "Company logo"
---

# Role Overview

Describe your position and main responsibilities here.

## Key Achievements

- Achievement 1: Describe a significant accomplishment
- Achievement 2: Quantify impact where possible (e.g., "improved performance by 40%")
- Achievement 3: Highlight leadership or collaboration

## Main Responsibilities

- Responsibility 1
- Responsibility 2
- Responsibility 3

## What I Learned

- Learning 1: Technical skills gained
- Learning 2: Soft skills developed
- Learning 3: Domain knowledge acquired
