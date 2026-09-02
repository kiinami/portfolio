---
title: "TFM"
date: 2026-09-02T10:26:24+02:00
slug: "tfm"

description: "Trabajo Fin de Máster en Informática Gráfica en la URJC, implementando un simulador personalizado y controlable basado en nodos del método de puntos materiales (MPM) en Python para integrar con Houdini"
summary: "Trabajo Fin de Máster en Informática Gráfica en la URJC, implementando un simulador personalizado y controlable basado en nodos del método de puntos materiales (MPM) en Python para integrar con Houdini"
keywords: ["método de puntos materiales", "mpm", "houdini", "python", "simulación gpu", "informática gráfica", "trabajo fin de máster", "urjc", "warp", "simulación"]
techs: ["python", "warp", "houdini", "uv", "typst", "latex"]
state: "in progress"
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/tfm"

params:
  neso:
    show_toc: false
    cover:
      image: "img/snowball_on_diamond_at_30kmph.gif"
      alt_text: "Una bola de nieve cayendo sobre un cubo de diamante"
      hidden_in_single : false
---

# Descripción

Mi trabajo fin de máster para el Máster en Informática Gráfica, Juegos y Realidad Virtual en la Universidad Rey Juan Carlos. El proyecto consiste en implementar un simulador personalizado y controlable basado en nodos del método de puntos materiales (MPM) en Python para integrar con Houdini. Para ello, estoy utilizando el framework [Warp](https://nvidia.github.io/warp/stable/index.html) de Nvidia, que me permite escribir código para la GPU en Python.

El proyecto aún está en sus inicios, pero ya he implementado un simulador MPM básico con integración explícita siguiendo el artículo original de Stomakhin et al. [^1], y actualmente estoy trabajando en la implementación de un esquema de integración implícita más avanzado que permite pasos de tiempo más grandes y una mejor estabilidad. Después de eso, implementaré una interfaz basada en nodos en Houdini que permita al usuario controlar los parámetros de la simulación y visualizar los resultados en tiempo real.

[^1]: A. Stomakhin, C. Schroeder, L. Chai, J. Teran, and A. Selle, "A material point method for snow simulation," ACM Transactions on Graphics, vol. 32, no. 4, pp. 1–10, Jul. 2013, doi: 10.1145/2461912.2461948. Disponible en: https://www.disneyanimation.com/publications/a-material-point-method-for-snow-simulation/
