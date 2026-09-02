---
title: "TFM"
date: 2026-09-02T10:26:24+02:00
slug: "tfm"

description: "Master's Thesis in Computer Graphics at URJC, implementing a custom user-controllable node-based material point method (MPM) simulator in Python to integrate with Houdini"
summary: "Master's Thesis in Computer Graphics at URJC, implementing a custom user-controllable node-based material point method (MPM) simulator in Python to integrate with Houdini"
keywords: ["material point method", "mpm", "houdini", "python", "gpu simulation", "computer graphics", "master thesis", "urjc", "warp", "simulation"]
techs: ["python", "warp", "houdini", "uv", "typst", "latex"]
state: "in progress" # in progress/finished/dropped/paused
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/tfm"

params:
  neso:
    show_toc: false
    cover:
      image: "img/snowball_on_diamond_at_30kmph.gif"
      alt_text: "A snowball falling on a diamond cube"
      hidden_in_single : false
---

# Description

My master's thesis for the Master's Degree in Computer Graphics, Games and Virtual Reality at Rey Juan Carlos University. The project consists of implementing a custom user-controllable node-based material point method (MPM) simulator in Python to integrate with Houdini. For this purpose, I am using the [Warp](https://nvidia.github.io/warp/stable/index.html) framework, which allows me to write high-performance GPU code in Python.

The project is still in its early stages, but I have already implemented a basic MPM simulator with explicit integration following the original paper by Stomakhin et al. [^1], and I am currently working on implementing a more advanced implicit integration scheme that allows for larger time steps and better stability. After that, I will implement a node-based interface in Houdini that allows the user to control the simulation parameters and visualize the results in real-time.

[^1]: A. Stomakhin, C. Schroeder, L. Chai, J. Teran, and A. Selle, “A material point method for snow simulation,” ACM Transactions on Graphics, vol. 32, no. 4, pp. 1–10, Jul. 2013, doi: 10.1145/2461912.2461948. Available at: https://www.disneyanimation.com/publications/a-material-point-method-for-snow-simulation/
