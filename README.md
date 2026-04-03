# Torsión FEM Libre

Herramienta web para el análisis FEM 1D de barras circulares sometidas a torsión.

## Descripción

**Torsión FEM Libre** es una aplicación en HTML, CSS y JavaScript que permite modelar barras a torsión mediante elementos finitos 1D, considerando:

- segmentos con distintas geometrías
- secciones macizas y huecas
- secciones constantes o variables
- distintos valores de módulo de rigidez `G`
- cargas puntuales, distribuidas y polinómicas
- condiciones de borde con empotramientos y resortes torsionales

La herramienta genera resultados gráficos de:

- carga distribuida `q(x)`
- momento torsor `T(x)`
- ángulo de giro `φ(x)`
- esfuerzo cortante `τ(x)`
- rigidez torsional `GJ(x)`

## Características principales

- Interfaz simple y visual
- Análisis FEM 1D en el navegador
- Soporte para múltiples segmentos
- Secciones huecas circulares
- Sistema de unidades configurable
- Gráficos interactivos
- Uso libre y gratuito

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- Chart.js
- chartjs-plugin-annotation

## Cómo usar

1. Define la longitud total de la barra.
2. Ajusta la cantidad de elementos por segmento.
3. Configura las condiciones de borde.
4. Agrega uno o más segmentos con sus propiedades geométricas y material.
5. Define las cargas torsionales.
6. Haz clic en **Calcular**.
7. Revisa los gráficos y resultados obtenidos.

## Publicación

Este proyecto está pensado para publicarse como sitio estático:

- GitHub

## Estado del proyecto

Proyecto en desarrollo. Se seguirán añadiendo mejoras y nuevas funciones.

## Autor

Desarrollado por Celso Gómez.

## Licencia

Puedes dejar esto provisionalmente así:

**Uso libre y gratuito.**

Si después quieres, te ayudo a ponerle una licencia formal tipo MIT.
