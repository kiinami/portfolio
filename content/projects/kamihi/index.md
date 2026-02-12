---
title           : "Kamihi"
date: 2025-07-18T10:17:57+01:00
slug            : "kamihi"  # slug (URL segment) for this post
state: "in progress"

description     : "Python framework for Telegram bot development and management"
summary         : "Python framework for Telegram bot development and management"
keywords        : ["python", "telegram", "framework", "webapp", "postgresql", "sqlite", "intuitive", "api"]
techs           : ["python", "telegram", "postgresql", "sqlite", "mongodb", "docker", "docker_compose", "linear", "bash", "git", "github", "github_actions"]
links:
  - name: "GitHub"
    url: "https://github.com/kamihi-org/kamihi"
  - name: "Docs"
    url: "https://kamihi-org.github.io/kamihi/latest/"

params:
  neso:
    show_toc   : false  # show the table of contents
    cover:     # cover image settings (remove this whole block if you have no cover)
      image    : "img/header.png"  # just put the filename if the cover lives in the same bundle as the md
      caption  : ""    # optional; shown under the cover image
      alt_text : "Kamihi logo"   # optional; accessibility text
      hidden_in_single : true
---

# Description

Kamihi is an open-source Python framework for Telegram bot development and management. Born as my Final Degree Project, it has evolved far beyond that, and it is actively used in companies.

The framework tries to address the inherent complexity that the Telegram API and its wrappers (`python-telegram-bot`, `pyrogram`, `telethon`) have by presenting a simple programing interface that abstracts most of the complexity away, making it feel like 'magic'.

The target audience is developers who have just started programming in Python, and that have little or no experience with the Telegram API and its many peculiarities.

The goal is for this project to be come an active part of the ecosystem, although for the moment it is in the beta stage.

# My Work

As the solo developer and maintainer of this project, my work as of the moment encompasses all aspects of the development and mangament of the project, including coding, testing, documentation, CI/CD...

I try to pay special attention to the design of the programming interface, making it feel intuitive to use and 'magic' in the right places, while giving the possibility to go deeper if they so desire. The users I know about are not experienced programmers, so the framework should do most of the work for them so they can focus on building the bot they need as fast as posible.

I also put significant work into the end-to-end testing framework. With the help of Docker containers, the automatic end-to-end tests can verify user code directly against Telegram servers in a simulated conversation, as well as test every other part of the framework (admin web interface, CLI, logs...).

# What I learnt

- How to structure and develop a modern, complex Python framework
- Techniques for improving developer experience via programming interface choices, CLI tooling and auto-configuration
- How to orchestrate ephemeral environments for automated end-to-end testing
- Managing the full lifecycle of an Open Source Python package (CI/CD, semantic versioning, PyPI)
