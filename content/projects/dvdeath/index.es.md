---
title: "DVDeath"
date: 2026-01-15T16:09:09+01:00
slug: "dvdeath"

description: "¡Haz que el logo del DVD golpee la esquina antes de que te mate!"
summary: "¡Haz que el logo del DVD golpee la esquina antes de que te mate!"
keywords: ["bullet hell", "unity", "csharp", "aseprite", "python", "juego de ritmo", "desarrollo de videojuegos", "urjc", "migjrv"]
techs: ["unity", "csharp", "aseprite", "python"]
state: "paused"
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/dvdeath"

params:
  neso:
    show_toc: false
    cover:
      image: "img/dvdeath3.png"
      alt_text: "Captura de pantalla de DVDeath"
      hidden_in_single : true
---

# Descripción

Pequeño juego *bullet-hell* desarrollado para la asignatura de Motores de Videojuegos en la [URJC](timeline/migjrv). El objetivo es hacer que el logo del DVD golpee una esquina de la pantalla antes de que te mate con sus balas o termine la canción.

Para hacer que el logo golpee la esquina, debes chocarte directamente con el personaje (un disco), teniendo en cuenta la forma en la que ambos rebotan. El personaje se mueve al ritmo de la música, llegando lejos si va con ritmo o apenas moviéndose si se va a destiempo. También puedes escudar el disco en su caja, perdiendo la capacidad de moverte pero haciendo rebotar las balas.

# Mi trabajo

Fui el único desarrollador de este juego. Tardé aproximadamente una semana en terminarlo.

Partí de la base establecida por los profesores, aunque la reescribí desde cero, cambiando mucho por el camino. Me centré especialmente en patrones de programación eficientes como el sistema de eventos o los *object pools*, tal y como requerían los requisitos de la asignatura.

También dediqué algo de tiempo a las animaciones, otro requisito de la asignatura. El disco tiene varias, desde el parpadeo al ser golpeado por una bala, hasta la deformación y el rastro que deja al moverse, pasando por el cierre y apertura de la caja del disco, que dibujé y animé a mano en Aseprite. De hecho, a excepción del propio logo del DVD, todos los *assets* del juego han sido hechos a mano.

El análisis de ritmo de las canciones incluidas en el juego, necesario para el movimiento del jugador al compás, se realizó mediante un script en Python que hace uso de la [librería `essentia`](https://essentia.upf.edu/). Esta información se encapsula luego en un `ScriptableObject` para ser utilizada en el juego.

El concepto del juego es muy divertido, y en el futuro me gustaría ampliarlo para convertirlo en un juego completo.

# Lo que aprendí

- Patrones de programación útiles para el diseño eficiente de videojuegos
- El sistema de animación de Unity, incluyendo estados y *blend trees*
- A dibujar y animar *pixel art* sencillo usando Aseprite
- A realizar análisis algorítmico de ritmo en una canción

# Galería

{{< gallery hover-effect="none" caption-effect="appear" >}} {{< load-photoswipe >}}
{{< picture src="img/dvdeath1.png" >}}
{{< picture src="img/dvdeath2.png" >}}
{{< picture src="img/dvdeath3.png" >}}
{{< picture src="img/dvdeath4.png" >}}
{{< /gallery >}}
