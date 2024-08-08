
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Índice de Marginación (1990 - 2015) utilizando Componentes Principales y cambios metodológicos para el 2020.

<!-- badges: start -->
<!-- badges: end -->

Este repositorio contiene archivos y documentación relacionados con el
índice de marginación estimado por el Consejo Nacional de Población
(CONAPO) para los años 1990, 1995, 2000, 2005, 2010 y 2015.

## Descripción General

Desde hace más de 25 años, el CONAPO ha estimado el índice de
marginación a partir de censos y conteos nacionales en México. Este
índice tiene como objetivo proporcionar un resumen de las carencias en
los servicios que la población padece en distintas unidades
territoriales del país.

## Acercamientos

- **Índice de Marginación (CONAPO):** Enfatiza la cuestión territorial y
  la población que vive en territorios marginados.
- **Medición Multidimensional de la Pobreza (CONEVAL):** Establece
  umbrales de línea de pobreza y necesidades insatisfechas.
- **Índice de Desarrollo Humano (PNUD):** Aborda la desigualdad desde la
  perspectiva de las unidades territoriales.

## Definición de Marginación

En 1990, el CONAPO definió la marginación como un proceso estructural
relacionado con el desarrollo socioeconómico del país, dificultando la
propagación del progreso a todos los grupos sociales y expresándose en
desigualdades territoriales.

### Tipos de Marginación

- **Marginación Social:** Privación de oportunidades y acceso a bienes y
  servicios básicos.
- **Marginación por Desventaja Económica:** Falta de recursos económicos
  y empleo.
- **Marginación por Desventajas Culturales:** Analfabetismo y escasa
  formación educativa.

## Objetivo del Índice

El objetivo principal del índice de marginación es identificar áreas que
aún carecen de servicios básicos y proporcionar un acercamiento al
conocimiento de la desigualdad regional.

## Problemática Metodológica

El índice se estima utilizando la técnica estadística de Análisis de
Componentes Principales (ACP). Sin embargo, los resultados no son
comparables en el tiempo debido a la variabilidad de los datos y mejoras
en la calidad de vida, lo que afecta la correlación entre las variables
originales.

## Cambios Metodológicos para 2020

Para mejorar la comparabilidad y precisión del índice de marginación, se
han implementado varios cambios metodológicos en el año 2020:

- **Nueva técnica con el método de distancias**: Se adoptó la técnica de
  Distancias Ponderadas al Cuadrado para las estimaciones de 2020. Esta
  técnica garantiza la comparabilidad temporal y mejora el procesamiento
  de datos, elevando la calidad de los resultados.
- **Medición de Cardinalidad:** Se ha trabajado en una metodología que
  permita medir la cardinalidad y cuantificar las mejoras o retrocesos
  en la marginación.
- **Ajustes en Indicadores**: Se realizaron ajustes para alinear las
  estimaciones con las recomendaciones de organismos nacionales e
  internacionales.
- **Método de Estratificación**: Se mantuvo la técnica de
  estratificación de Dalenius y Hodges para el cálculo de los estratos
  del índice, pero con un algoritmo de iteración que predice los
  estratos de menor varianza.

## Contenido del Repositorio

- **Datos:** Archivos de datos para los años 1990, 1995, 2000, 2005,
  2010 y 2015.
- **Documentación:** Descripción detallada de la metodología utilizada y
  los cambios implementados para 2020. [Nota
  técnica](https://www.gob.mx/cms/uploads/attachment/file/634902/Nota_t_cnica_marginaci_n_2020.pdf).  
- **Scripts:** Códigos y scripts utilizados para el análisis y la
  estimación del índice de marginación.

## Autor

Este proyecto es desarrollado y mantenido por @dvillasanao
