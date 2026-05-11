---
title: "maya4linux"
date: 2026-05-11T13:32:51+02:00
slug: "maya4linux"

description: "Maya 2026.3 execution in Linux using Docker containers"
summary: "Maya 2026.3 execution in Linux using Docker containers"
keywords: ["maya", "autodesk", "linux", "docker", "container", "3d", "animation", "development", "open source"]
techs: ["maya", "docker", "docker_compose"]
state: "finished"
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/maya4linux"
  - name: "Pull Request"
    url: "https://github.com/animaj-lab/maya4linux/pull/5"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "Autodesk Maya Logo"
      hidden_in_single : true
---

# Description

I wanted to start learning Maya, and was really surprised that in its most recent versions it is virtually impossible to install in Linux. The [documentation](https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=GUID-3E0A3A36-B1C2-4B91-994B-731C672D9694) is awfully outdated, it only works on very specific versions of some distros, and even then, the process is confusing and very error prone.

The closest thing I could find to a working install was [this GitHub project](https://github.com/animaj-lab/maya4linux), which only worked for Maya version 2024.2.

# My Work

Using the project I found, I worked out how to make a Docker container that can execute Maya 2026.3 on Linux, independent of distro and without polluting your system with dozens of packages and always-running processes. Once I managed to make it work, I contributed the new files upstream, and they were incorporated into the original project :)

# What I Learnt

- How to run graphical applications inside Docker containers (surprisingly, I had not done that yet, they always have web interfaces)
- How Maya works at the program level, its dependencies, the inner workings of the licensing program, etc.
- Some basic Maya, once it was installed
