---
title: "{{ .File.ContentBaseName | humanize | replaceRE `\s+` " " | title }}"
date: {{ .Date }}
# endDate: {{ .Date }} # Fecha de finalización
slug: "{{ .File.ContentBaseName | urlize }}"

# customDate: "Veranos 2020-2023" # Descomenta para usar texto de fecha personalizado en lugar del rango automático

organization: "Nombre de la Empresa"
location: "Ciudad, País"
type: "work"

description: "Breve descripción del puesto para SEO"
summary: "Resumen de una línea de tu puesto y principales responsabilidades"
keywords: ["palabra1", "palabra2", "palabra3"]
techs: ["python", "django", "postgresql"]  # Usar IDs de tecnología de hugo.toml

links:
  - name: "Sitio Web de la Empresa"
    url: "https://example.com"
  # - name: "Proyecto"
  #   url: "https://proyecto-url.com"

params:
  neso:
    show_toc: false
    cover:
      image: "img/logo.png"  # Logo de la empresa/organización
      alt_text: "Logo de la empresa"
---

# Descripción del Puesto

Describe tu posición y principales responsabilidades aquí.

## Logros Clave

- Logro 1: Describe un logro significativo
- Logro 2: Cuantifica el impacto donde sea posible (ej. "mejoré el rendimiento en un 40%")
- Logro 3: Destaca liderazgo o colaboración

## Principales Responsabilidades

- Responsabilidad 1
- Responsabilidad 2
- Responsabilidad 3

## Lo Que Aprendí

- Aprendizaje 1: Habilidades técnicas adquiridas
- Aprendizaje 2: Habilidades blandas desarrolladas
- Aprendizaje 3: Conocimiento del dominio adquirido
