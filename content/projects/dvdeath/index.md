---
title: "DVDeath"
date: 2026-01-15T16:09:09+01:00
slug: "dvdeath"

description: "Make the DVD logo hit the corner before it kills you!"
summary: "Make the DVD logo hit the corner before it kills you!"
keywords: ["bullet hell", "unity", "csharp", "aseprite", "python", "rhythm game", "videogame development", "urjc", "migjrv"]
techs: ["unity", "csharp", "aseprite", "python"]
state: "paused" # in progress/finished/dropped/paused
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/dvdeath"

params:
  neso:
    show_toc: false
    cover:
      image: "img/dvdeath3.png"
      alt_text: "<cover alt text>"
      hidden_in_single : true
---

# Description

Small bullet-hell game made for the Videogame Engines course at [URJC](timeline/migjrv). The objective is to make the DVD logo hit a corner of the screen before it kills you with its bullets or the song ends.

To make the logo hit the corner, you must hit it directly with the character (a disk), taking into account the way it bounces. The character moves with the music's beats, traveling far if on rhythm or barely moving if off-beat. You can also shield the disk in its case, losing the ability to move but bouncing bullets off.

# My Work

I was the only developer for this game. It took about a week to finish.

I started from the base laid out by the teachers, although I rewrote it from scratch, changing much along the way. I was specially focused on performant programming patterns like the event system or object pools, as required by the course's assignment.

I also spent some time with animations, another requirement for the course. The disk has several, from the blinking when hit by a bullet, to the deformation and trail left when moving, all the way to the closing and opening of the disk case, which I drew and animated by hand in Aseprite. In fact, except for the actual DVD logo, all assets in the game have been made by hand.

Beat analysis of the songs included in the game needed for the movement of the player on beat were done using a script in Python that makes use of the [`essentia` library](https://essentia.upf.edu/). This information is then encapsulated in a `ScriptableObject` to be used in the game.

The concept of the game is really fun, and in the future I would like to expand on it to make it a fully fledged game.

# What I Learnt

- Useful programming patterns for performant videogame design
- Unity's animation system, including states and blend trees
- How to draw and animate simple pixel art using Aseprite
- How to perform algorythmic beat analysis on a song

# Gallery

{{< gallery hover-effect="none" caption-effect="appear" >}} {{< load-photoswipe >}}
{{< picture src="img/dvdeath1.png" >}}
{{< picture src="img/dvdeath2.png" >}}
{{< picture src="img/dvdeath3.png" >}}
{{< picture src="img/dvdeath4.png" >}}
{{< /gallery >}}
