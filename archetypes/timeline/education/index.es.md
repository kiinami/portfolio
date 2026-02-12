---
title: "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date: {{ .Date }}
endDate: {{ .Date }}  # Fecha de graduación
slug: "{{ .File.ContentBaseName | urlize }}"

# customDate: "2019-2023" # Descomenta para usar texto de fecha personalizado en lugar del rango automático

organization: "Nombre de la Universidad"
location: "Ciudad, País"
type: "education"

description: "Breve descripción de tu título/programa para SEO"
summary: "Resumen de una línea de tu título y especialización"
keywords: ["palabra1", "palabra2", "palabra3"]
techs: ["python", "java", "cpp"]  # Usar IDs de tecnología de hugo.toml

links:
  - name: "Universidad"
    url: "https://universidad.edu"
  # - name: "Tesis"
  #   url: "https://tesis-url.com"
  # - name: "Certificado"
  #   url: "https://certificado-url.com"

params:
  neso:
    show_toc: false
    cover:
      image: "img/logo.png"  # Logo de la universidad/institución
      alt_text: "Logo de la universidad"
---

# Descripción del Título

Describe tu programa de estudios, campo de estudio y cualquier especialización o concentración.

## Cursos Clave

- Curso 1: Algoritmos Avanzados y Estructuras de Datos
- Curso 2: Sistemas Distribuidos
- Curso 3: Arquitectura de Software y Patrones de Diseño
- Curso 4: Sistemas de Bases de Datos
- Curso 5: Sistemas Operativos

## Logros Académicos

- Promedio: X.X/4.0
- Lista del Decano por X semestres
- Becas académicas u honores recibidos
- Título y descripción de la tesis/proyecto final

## Proyectos e Investigación

### Título del Proyecto 1
Breve descripción de un proyecto académico significativo o trabajo de investigación.

### Título del Proyecto 2
Breve descripción de otro proyecto o trabajo de investigación.

## Actividades Extracurriculares

- Organizaciones estudiantiles o clubes
- Posiciones de asistente de enseñanza
- Trabajo voluntario o servicio comunitario

## Habilidades Desarrolladas

- Habilidades técnicas aprendidas durante tus estudios
- Habilidades de investigación y análisis
- Experiencia en colaboración y trabajo en equipo
