---
title           : "Kamihi"
slug            : "kamihi"  # slug (URL segment) for this post

description     : "Framework de código abierto para el desarrollo y manejo de bots de Telegram en Python"
summary         : "Framework de código abierto para el desarrollo y manejo de bots de Telegram en Python"
keywords        : ["python", "telegram", "framework", "webapp", "postgresql", "sqlite", "intuitive", "api"]
tags            : ["Python", "Telegram", "Framework", "Webapp", "PostgreSQL", "SQLite"]

params:
  neso:
    show_toc   : false  # show the table of contents
    cover:     # cover image settings (remove this whole block if you have no cover)
      image    : "header.png"  # just put the filename if the cover lives in the same bundle as the md
      caption  : ""    # optional; shown under the cover image
      alt_text : "Logo de Kamihi"   # optional; accessibility text
      hidden_in_single : true
---

# Descripción

Kamihi es un _framework_ de código abierto para el desarrollo y manejo de bots de Telegram en Python. Siendo en un principio mi Trabajo de Fin de Grado, ha evolucionado más allá, y se utiliza activamente en empresas.

El _framework_ intenta hacer más manejable el desarrollo de bots de Telegram en Python, abstrayendo en su mayor parte la complejidad de la API de Telegram y de sus _wrappers_ (`python-telegram-bot`, `pyrogram`, `telethon`). Para ello, presenta una interfaz de programación simple que realiza el trabajo complicado por detrás.

Está pensado para desarrolladores con poca experiencia en Python y/o con la API de Telegram y sus muchas peculiaridades.

El objetivo es convertir este projecto en una parte activa del ecosistema de desarrollo de bots de Telegram, aunque en este momento está en fase _beta_.

# Mi trabajo

Como único desarrollador y mantenedor de este proyecto, mi trabajo engloba todos los aspectos de desarrollo y manejo del proyecto: programación, _testing_, documentación, CI/CD...

Mi foco principal es el diseño de la interfaz de programación del _framework_, que intento que sea muy intuitiva, fácil de utilizar, e incluso "mágica", sin por ello cerrar la posibilidad de utilizar las funciones más avanzadas que ofrece la API de Telegram.

Los usuarios que conozco no son programadores expertos, y el _framework_ está pensado y cuidadosamente diseñado para que puedan centrarse en su lógica de negocio, construyendo el bot que necesiten lo más rápido posible.

# Enlaces

{{< gh-repo "kamihi-org/kamihi" >}}

Documentación: https://kamihi-org.github.io/kamihi/latest/
