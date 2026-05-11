---
title: "Lisa (Vulkan)"
date: 2026-05-11T19:42:48+02:00
slug: "lisa-vulkan"

description: "Motor de render en Vulkan"
summary: "Motor de render en Vulkan"
keywords: ["vulkan", "motor de renderizado", "cpp", "slang", "meson", "gltf", "informática gráfica", "urjc"]
techs: ["cpp", "vulkan", "slang", "meson", "gltf"]
state: "in progress"
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/lisa-vulkan"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "Motor de renderizado Lisa Vulkan"
      hidden_in_single : false
---

# Descripción

Motor de renderizado aficionado en C++, utilizando Vulkan. Comencé a desarrollarlo como una implementación alternativa al proyecto base proporcionado para la asignatura de Rendering Avanzado II en la URJC, como una forma de, al paso de los requisitos de la asignatura, aprender Vulkan más en profundidad y experimentar con diferentes tecnologías, técnicas, arquitecturas, etc... que no se cubren. Ahora mismo ofrece:

- Soporte para Linux y Windows (experimental)
- Configuración completa de Vulkan 1.4 con capas de validación utilizando Vulkan Profiles
- Arquitectura ECS con ENTT
- Soporte tanto para glTF estándar como para un formato XML personalizado fácil de usar
- Renderizado multipaso (*multi-pass*)
- Definiciones de grafos de renderizado en XML fáciles de editar con validación de esquemas, gestión automática de barreras y sin necesidad de recompilar
- Múltiples pasadas de preproceso, renderizado *forward*, renderizado diferido (*deferred*) y postproceso
- Materiales PBR, definidos mediante constantes o texturas
- Múltiples tipos de luces
- *Pipeline* completo de *assets*
- Movimiento y rotación de cámara estilo FPS con teclado y ratón

El proyecto está construido con Meson e intenta utilizar tecnologías más recientes, como el lenguaje de *shaders* Slang, Vulkan-Hpp, Vulkan Profiles...
