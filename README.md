# Trabajo Individual - Teoría de la Decisión (2026/2027)

**Autor:** Eduardo Llovet Rojas  
**Asignatura:** Teoría de la Decisión  
**Titulación:** Grado en Estadística (Universidad de Sevilla)  

## Descripción del Proyecto

Este repositorio contiene el desarrollo del Proyecto RStudio Individual correspondiente a la evaluación continua (Tema 1: Métodos de Decisión bajo Incertidumbre). El objetivo principal es la formulación y resolución de dos problemas originales mediante la aplicación de distintos criterios de decisión bajo incertidumbre, utilizando el lenguaje de programación R y control de versiones con Git/GitHub.

## Contenido del Repositorio

El trabajo se divide principalmente en dos documentos generados mediante Quarto (exportados simultáneamente a formatos HTML y PDF mediante Typst):

1. **`Enunciados.qmd` (y sus salidas `.html` / `.pdf`):** 
   Contiene los enunciados de los dos problemas planteados, junto con un cuestionario de 5 preguntas (Verdadero/Falso) para cada uno, indicando claramente las respuestas correctas al final.
   - *Problema 1:* Toma de decisiones sobre la organización de torneos en un club de pádel.
   - *Problema 2:* Estrategia de stock de vehículos híbridos en un concesionario ante la normativa ZBE.

2. **`resoluciones.qmd` (y sus salidas `.html` / `.pdf`):** 
   Incluye los enunciados completos acompañados del código en R y la resolución detallada. 
   - El primer problema se resuelve aplicando las funciones individuales de los criterios de decisión (Wald, Optimista, Hurwicz, Savage, Laplace y Punto Ideal) tanto en situación favorable como desfavorable.
   - El segundo problema, basado en una situación real, se resuelve aplicando la función generalizadora `criterio.Todos`.

3. **`teoriadecision_funciones_incertidumbre.R`:** 
   Script de R proporcionado en la asignatura que contiene las funciones necesarias para los cálculos de los diferentes criterios de decisión.

