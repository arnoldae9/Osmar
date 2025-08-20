---
title: "Fisica"
subtitle: "Mediciones"
author: "Prof. Arnoldo Del Toro Peña"
date: \today
subject: "Física"
grade: "Grado: [2° Año] Secundaria"
geometry: margin=1in
fontsize: 12pt
lang: es
documentclass: article
header-includes:
  - \usepackage{amsmath}
  - \usepackage{amssymb}
  - \usepackage{mathtools}
  - \everymath{\displaystyle}
  - \everydisplay{\displaystyle}
  - \usepackage{xcolor}
  - \usepackage{tcolorbox}
  - \usepackage{fancyhdr}
  - \pagestyle{fancy}
  - \fancyhead[L]{Física}
  - \fancyhead[R]{2° Año}
  - \fancyfoot[C]{\thepage}
  - \tcbuselibrary{most}
  - \newtcolorbox{objetivo}{colback=green!5!white,colframe=green!75!black,title=OBJETIVO}
  - \newtcolorbox{definicion}{colback=yellow!5!white,colframe=orange!75!black,title=DEFINICIÓN}
  - \newtcolorbox{ejemplo}{colback=blue!5!white,colframe=blue!75!black,title=EJEMPLO}
  - \newtcolorbox{ejercicio}{colback=cyan!5!white,colframe=cyan!75!black,title=EJERCICIO}
  - \newtcolorbox{formula}{colback=gray!5!white,colframe=gray!75!black,title=FÓRMULA}
  - \newtcolorbox{nota}{colback=red!5!white,colframe=red!75!black,title=NOTA IMPORTANTE}
---
 <!-- pandoc file.md -o file.pdf --pdf-engine=xelatex, puedes usar los begin con: objetivo, definicion, ejemplo, ejercicio, formula, nota-->

## Medición y Cantidad Física

\begin{definicion}
La \textbf{medición} es el proceso de comparar una magnitud física con una unidad de referencia establecida para obtener un valor numérico. Una \textbf{cantidad física} es cualquier propiedad de la materia o fenómeno que puede ser medida, como la longitud, masa, tiempo, temperatura, velocidad, etc. Estas cantidades se clasifican en fundamentales (longitud, masa, tiempo, corriente eléctrica, temperatura, cantidad de sustancia, intensidad luminosa) y derivadas (área, volumen, densidad, fuerza, etc.).
\end{definicion}

## Sistema Internacional de Unidades (SI)

El **Sistema Internacional de Unidades** es el sistema de medidas más utilizado mundialmente, establecido en 1960. Se basa en siete unidades fundamentales:

- **Metro (m)** para longitud

- **Kilogramo (kg)** para masa  

- **Segundo (s)** para tiempo

- **Ampere (A)** para corriente eléctrica

- **Kelvin (K)** para temperatura

- **Mol (mol)** para cantidad de sustancia

- **Candela (cd)** para intensidad luminosa

A partir de estas unidades fundamentales se derivan todas las demás unidades del sistema, como el newton (N) para fuerza, el pascal (Pa) para presión, el joule (J) para energía, etc.

## Conversión de Unidades
\begin{definicion}
La \textbf{conversión de unidades} es el proceso de cambiar el valor de una cantidad física de una unidad a otra equivalente. Esto es necesario cuando trabajamos con diferentes sistemas de medida o cuando queremos expresar una cantidad en unidades más convenientes para el contexto específico.
\end{definicion}

## Método del Factor de Conversión

\begin{definicion}
El \textbf{método del factor de conversión} es una técnica sistemática para realizar conversiones de unidades. Consiste en multiplicar la cantidad original por uno o más factores de conversión (fracciones equivalentes a 1) de manera que las unidades no deseadas se cancelen y queden las unidades deseadas.
\end{definicion}

**Pasos del método:**

1. Identificar la unidad inicial y la unidad final deseada

2. Establecer la relación de equivalencia entre ambas unidades

3. Escribir el factor de conversión como una fracción donde el numerador y denominador son equivalentes

4. Multiplicar la cantidad original por el factor de conversión, asegurándose de que las unidades se cancelen correctamente

5. Realizar las operaciones matemáticas para obtener el resultado

**Ejemplo:** Convertir 5 metros a centímetros

- Factor de conversión: 1 m = 100 cm

- 5 m × (100 cm/1 m) = 500 cm

\begin{nota}
Este método es especialmente útil para conversiones complejas que requieren múltiples pasos, ya que permite mantener un seguimiento claro de las unidades y asegurar que la conversión sea correcta.
\end{nota}