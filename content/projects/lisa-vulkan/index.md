---
title: "Lisa (Vulkan)"
date: 2026-05-11T19:42:48+02:00
slug: "lisa-vulkan"

description: "Hobby rendering engine in Vulkan"
summary: "Hobby rendering engine in Vulkan"
keywords: ["vulkan", "rendering engine", "cpp", "slang", "meson", "gltf", "computer graphics", "urjc"]
techs: ["cpp", "vulkan", "slang", "meson", "gltf"]
state: "in progress" # in progress/finished/dropped/paused
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/lisa-vulkan"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "Lisa Vulkan rendering engine"
      hidden_in_single : false
---

# Description

Hobby rendering engine in C++, using Vulkan. The evolution of my previous work in the [OpenGL Lisa render engine](../lisa/index.md). Started developing it as an alternative implementation to the base project provided for the Rendering Avanzado II course at URJC, as a way to, while implementing anything else needed for the subject, learn Vulkan more indepth and experiment with different technologies, techniques, architectures, etc... not covered in the course. Here is the current list of features:

- Support for Linux and Windows (experimental)
- Full Vulkan 1.4 setup with validation layers using Vulkan Profiles
- ECS architecture with ENTT
- Both standard glTF and a custom easy-to-use XML format supported. You can even nest them!
- Multi-pass rendering
- Easy-to-edit XML render graph definitions with schema validation, automatic barrier management and no recompilation needed!
- Many preprocessing, forward rendering, deferred rendering and postprocess passes
- PBR materials, defined by constants or textures
- Multiple light types
- Strong assets pipeline
- FPS-style camera movement and rotation with keyboard and mouse

The project is built with Meson and tries to use newer technologies, like the Slang shading language, Vulkan-Hpp, Vulkan Profiles...
