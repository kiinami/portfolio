---
title: "Lisa"
date: 2025-12-18T10:17:57+01:00
slug: "lisa"

description: "Simple OpenGL render engine in C++"
summary: "Simple OpenGL render engine in C++"
keywords: ["OpenGL", "C++", "Render Engine", "Deferred Rendering", "Forward Rendering", "Post-processing", "ImGUI", "ECS", "3D Graphics"]
tags: ["C++", "OpenGL", "ImGUI", "Post-processing", "ECS"]
techs: ["cpp", "opengl", "imgui"]
state: "paused"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "<cover alt text>"
      hidden_in_single : true
---

# Description

Lisa is an OpenGL render engine written in C++ for the 3D Graphics course at Rey Juan Carlos University.

The main focus of the project was to learn the structure and architecture of a modern render engine, how components interact with each other, and what abstractions need to be made.

The project implements a render engine both with forward and deferred rendering, ECS-based scene definition, a complete modular post-processing engine and a simple interface using ImGUI to control some of the parameters of the scene.

# My Work

I was the only developer for this engine, although I started from the base project the teachers provided, which could be contained in one file.

Thus, some of my time was dedicated to the refactoring the project with a clean, well-designed architecture made with modern C++ programming techniques.

The rest was dedicated to building a post-processing engine that could handle an arbitrary amount of passes of any kind (convolutional, depth-based, light-based, etc.) in a modular fashion, including their settings interfaces.

# What I Learnt

- How a modern C++ project, and how a modern (despite simple) render engine are structured
- How post-processing works in modern render engines
- C++ techniques for efficiency and correct resource management

# Links

{{< gh-repo "kiinami/lisa" >}}
