---
title: "Lisa"
date: 2025-12-18T10:17:57+01:00
slug: "lisa"

description: "Motor de render con OpenGL en C++"
summary: "Motor de render con OpenGL en C++"
keywords: ["OpenGL", "C++", "Motor de Render", "Deferred Rendering", "Forward Rendering", "Post-proceso", "ECS", "Gráficos 3D"]
tags: ["Motor de render", "Post-proceso", "ECS"]
techs: ["cpp", "opengl", "glsl", "cmake", "git"]
state: "paused"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "<cover alt text>"
      hidden_in_single : true
---

# Descripción

Lisa es un motor de render con OpenGL en C++, realizado para la asignatura de Gráficos 3D en la Universidad Rey Juan Carlos.

El objetivo principal del proyecto es entender la estructura y arquitectura tanto de un proyecto de C++ como de un motor de render moderno.

El proyecto implementa un motor de render con tanto _forward_ como _deferred_ rendering, definición de escenas basado en ECS, una _pipeline_ de post-proceso completa totalmente modular y una interfaz simple.

# Mi trabajo

Era el único desarrollador de este motor, aunque empecé a partir del proyecto base provisto por los profesores, constituido por un único archivo con todo dentro.

Por tanto, parte de mi tiempo lo dediqué a refactorizar el proyecto con una arquitectura bien diseñada y con técnicas modernas de programación en C++.

El resto lo dediqué sobre todo a construir una _pipeline_ de post-proceso que pudiese aplicar una cantidad arbitraria de pasadas de cualquier tipo (convolucional, basada en profundidad, etc.) de manera modular, incluyendo sus interfaces de ajustes.

# Lo que aprendí

- Cómo se estructuran tanto los proyectos modernos en C++ como un motor simple de render
- Cómo funciona y cómo implementar una _pipeline_ de post-proceso compleja en motores de render
- Técnicas de C++ para tener un programa eficiente y que gestione correctamente sus recursos

# Enlaces

{{< gh-repo "kiinami/lisa" >}}
