---
title: "Documentación de funciones en R"
subtitle: "Documenta las funciones de tus paquetes en R con roxygen2"
excerpt: "Un tutorial de 20 minutos sobre cómo usar roxygen2 para documentar funciones en R."
date: 2023-06-09
author: "Andrés Arredondo Cruz, CDSB2023"
featured: true
draft: false
tags:
  - roxygen2
  - R
categories:
  - R
  - Education
layout: single
links:
  - icon: book-open
    icon_pack: fas
    name: Website
    url: https://comunidadbioinfo.github.io/cdsb2023/Documentacion_slides_03_sesion5.html#1
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/ComunidadBioInfo
---

<div style="text-align: center;">
  <img src="https://comunidadbioinfo.github.io/cdsb2023/Documentacion_slides_03_sesion5.html#1" alt="Documentación en R" width="75%">
</div>

## Workshop Description

Este tutorial de una hora fue creado para el curso **Desarrollo de paqueterías de R/Bioconductor** en [CDSB2023](https://comunidadbioinfo.github.io/cdsb2024/index.html).

[Diapositivas](https://comunidadbioinfo.github.io/cdsb2023/Documentacion_slides_03_sesion5.html#1).

[Capítulo del bookdown](https://comunidadbioinfo.github.io/cdsb2024/documentaci%C3%B3n-de-funciones.html#diapositivas-5).

### ¿Qué es la documentación?

La documentación es un archivo de ayuda para el usuario que contiene información detallada sobre las funciones de un paquete en R. Aquí te explicamos lo más importante:

- 🙇️ **Información complementaria:** Es el texto que el desarrollador escribe sobre una función. Los usuarios acceden a ella usando `?` seguido del nombre de la función, por ejemplo: `?unafuncion`.
- 📁 **Archivo .Rd:** La documentación se almacena como un archivo `.Rd` (abreviatura de *R documentation*) en la carpeta `man/` del paquete.
- 🔎 **Sintaxis especial:** Utiliza una sintaxis diferente a la de R, basada ligeramente en LaTeX.
- 📄 **Formatos:** Puede renderizarse como HTML, PDF o texto sin formato, dependiendo de la necesidad.

## Imagen destacada

![Documentación de funciones](featured.png)
