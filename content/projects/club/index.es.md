---
title: "Club App"
date: 2024-01-30T16:09:26+01:00
slug: "club"

description: "App dirigida a padres y niños de asociaciones juveniles en Italia"
summary: "App dirigida a padres y niños de asociaciones juveniles en Italia"
keywords: ["flutter", "dart", "app móvil", "asociación juvenil", "italia", "polimi", "material design", "multiplataforma", "gestión de eventos"]
techs: ["dart", "flutter", "git", "github"]
state: "finished"
links:
  - name: "Play Store"
    url: "https://play.google.com/store/apps/details?id=com.mycompany.dima&hl=en-US&ah=hVKYlBiDzc_5nDXs1Qp9CvLuaow"

params:
  neso:
    show_toc: false
    cover:
      image: "img/icon.png"
      hidden_in_single : true
---

# Descripción

Pequeña aplicación dirigida a informar a padres y niños de asociaciones juveniles en Italia sobre las múltiples actividades que se ofrecen, con muchas pequeñas funcionalidades para facilitar también la vida a los organizadores.

La aplicación incluye la creación y envío de información sobre eventos (con notificaciones), confirmaciones de asistencia a actividades, un calendario con todas las actividades ofrecidas por la asociación, un sistema de clasificación de usuarios basado en partidos de fútbol para aquellas asociaciones que ofrecen escuela de fútbol, verificación y aprobación de usuarios para acceder a cualquier dato, y mucho más.

Puede ejecutarse tanto en dispositivos móviles como en escritorio, con una interfaz responsiva que se adapta al tamaño de la pantalla. Todas las operaciones, incluidas las administrativas como crear eventos, aprobar usuarios o introducir nuevos resultados de fútbol, se pueden realizar también desde cualquier dispositivo, directamente en la aplicación.

La aplicación ha sido utilizada en producción desde el principio por [Tiber Club](https://tiberclub.org/), una asociación juvenil en Roma, y más recientemente por Delta Center en Milán.

# Mi trabajo

Esta aplicación comenzó como un proyecto para la asignatura de Diseño e Implementación de Aplicaciones Móviles en el [Polimi](timeline/polimi), que realicé junto a otro desarrollador. La aplicación está programada desde cero en Flutter, que fuimos aprendiendo sobre la marcha.

Dado que ambos éramos voluntarios en asociaciones juveniles en ese momento, teníamos un contacto muy estrecho con los "clientes". Hicimos la aplicación que nos hubiera gustado usar mientras éramos voluntarios, resolviendo el mayor problema que dificultaba la organización de actividades: la comunicación clara entre padres, niños y organizadores.

La aplicación fue internacionalizada desde el principio tanto en italiano como en inglés, para atender a las asociaciones juveniles a las que se la ofrecíamos pero mantenerla abierta para cualquier otra asociación que pudiera estar interesada.

Tras finalizar la asignatura, me aparté del desarrollo, mientras que el otro miembro del equipo ha continuado su desarrollo hasta el día de hoy.

# Lo que aprendí

- A crear una aplicación Material Design en Flutter
- A crear una aplicación pensada para un grupo reducido de usuarios, y con fuertes requisitos de privacidad
