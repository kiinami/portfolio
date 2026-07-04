---
title: "Ingeniero de desarrollo de SW OpenGL"
date: 2026-07-04T10:22:34+02:00
# endDate: 2026-07-04T10:22:34+02:00 # Fecha de finalización
slug: "ocs"

# customDate: "Veranos 2020-2023" # Descomenta para usar texto de fecha personalizado en lugar del rango automático

organization: "Orbital Critical Systems"
location: "Getafe, España"
type: "work"

description: "Desarrollo de interfaces gráficas para sistemas de visualización de cabina (CDS) en OpenGL SC1 y SC2"
summary: "Desarrollo de interfaces gráficas para sistemas de visualización de cabina (CDS) en OpenGL SC1 y SC2"
keywords: ["palabra1", "palabra2", "palabra3"]
techs: ["c", "openglsc1", "openglsc2", "redis", "cmake", "git", "bitbucket", "python"]

projects: []  # Agrega los slugs de proyectos aquí para mostrarlos como "Proyectos Relacionados"

links:
  - name: "Orbital Critical Systems"
    url: "https://www.orbitalcs.com/"
  # - name: "Proyecto"
  #   url: "https://proyecto-url.com"

params:
  neso:
    show_toc: false
---

# Descripción del puesto

Desarrollo interfaces gráficas para sistemas de visualización de cabina definidos por el estándar [ARINC661 Parte 1](https://www.sae.org/standards/arinc661p1-9-661p1-9-cockpit-display-system-interfaces-user-systems-part-1-avionics-interfaces-basic-symbology-behavior). El resultado es un motor de renderizado genérico programado en C puro que puede procesar binarios que definen la interfaz y renderizarlos de manera eficiente mediante OpenGL SC, comunicándose con aplicaciones que proporcionan datos a través de Redis.
