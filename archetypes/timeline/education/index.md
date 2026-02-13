---
title: "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date: {{ .Date }}
endDate: {{ .Date }}  # Graduation date
slug: "{{ .File.ContentBaseName | urlize }}"

# customDate: "2019-2023" # Uncomment to use custom date text instead of automatic date range

organization: "University Name"
location: "City, Country"
type: "education"

description: "Brief description of your degree/program for SEO"
summary: "One-line summary of your degree and specialization"
keywords: ["keyword1", "keyword2", "keyword3"]
techs: ["python", "java", "cpp"]  # Use tech IDs from hugo.toml

projects: []  # Add project slugs here to display them as "Related Projects"

links:
  - name: "University"
    url: "https://university.edu"
  # - name: "Thesis"
  #   url: "https://thesis-url.com"
  # - name: "Certificate"
  #   url: "https://certificate-url.com"

params:
  neso:
    show_toc: false
    cover:
      image: "img/logo.png"  # University/institution logo
      alt_text: "University logo"
---

# Degree Overview

Describe your degree program, field of study, and any specializations or concentrations.

## Key Courses

- Course 1: Advanced Algorithms and Data Structures
- Course 2: Distributed Systems
- Course 3: Software Architecture and Design Patterns
- Course 4: Database Systems
- Course 5: Operating Systems

## Academic Achievements

- GPA: X.X/4.0
- Dean's List for X semesters
- Academic scholarships or honors received
- Thesis/Capstone project title and description

## Projects & Research

### Project 1 Title
Brief description of a significant academic project or research work.

### Project 2 Title
Brief description of another project or research work.

## Extracurricular Activities

- Student organizations or clubs
- Teaching assistant positions
- Volunteer work or community service

## Skills Developed

- Technical skills learned during your studies
- Research and analytical skills
- Collaboration and teamwork experience
