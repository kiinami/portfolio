---
title: "maya4linux"
date: 2026-05-11T13:32:51+02:00
slug: "maya4linux"

description: "Ejecución de Maya 2026.3 en Linux mediante contenedores de Docker"
summary: "Ejecución de Maya 2026.3 en Linux mediante contenedores de Docker"
keywords: ["maya", "autodesk", "linux", "docker", "contenedor", "3d", "animación", "desarrollo", "código abierto"]
techs: ["maya", "docker", "docker_compose"]
state: "finished"
links:
  - name: "GitHub"
    url: "https://github.com/kiinami/maya4linux"
  - name: "Pull Request"
    url: "https://github.com/animaj-lab/maya4linux/pull/5"

params:
  neso:
    show_toc: false
    cover:
      image: "header.png"
      alt_text: "Logo de Autodesk Maya"
      hidden_in_single : true
---

# Descripción

Quería empezar a aprender Maya y me sorprendió mucho que en sus versiones más recientes sea prácticamente imposible de instalar en Linux. La [documentación](https://help.autodesk.com/view/MAYAUL/2026/ENU/?guid=GUID-3E0A3A36-B1C2-4B91-994B-731C672D9694) está muy desactualizada, solo funciona en versiones muy específicas de algunas distribuciones y, aun así, el proceso es confuso y propenso a errores.

Lo más parecido a una instalación funcional que pude encontrar fue [este proyecto en GitHub](https://github.com/animaj-lab/maya4linux), que solo funcionaba para la versión 2024.2 de Maya.

# Mi trabajo

Utilizando el proyecto que encontré, deduje cómo crear un contenedor de Docker que pudiera ejecutar Maya 2026.3 en Linux, independientemente de la distribución y sin contaminar el sistema con decenas de paquetes y procesos permanentemente en ejecución. Una vez que conseguí que funcionara, contribuí los nuevos archivos *upstream*, y fueron incorporados al proyecto original :)

# Lo que aprendí

- A ejecutar aplicaciones gráficas dentro de contenedores de Docker (sorprendentemente, aún no lo había hecho, siempre tenían interfaces web)
- Cómo funciona Maya a nivel de programa, sus dependencias, el funcionamiento interno del programa de licencias, etc.
- Algo del uso básico de Maya, una vez  instalado
