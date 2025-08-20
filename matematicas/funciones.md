---
title: "Título del Tema"
subtitle: "Subtítulo o Capítulo"
author: "Prof. Arnoldo Del Toro Peña"
date: \today
subject: "Matemáticas"
grade: "Grado: [X° Año]"
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
  - \fancyhead[L]{Matemáticas - [Tema]}
  - \fancyhead[R]{[Grado]}
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

# Resumen: Funciones y sus Aplicaciones

## 1. Dominio y Rango de Funciones

### Definiciones

- **Dominio**: Conjunto de todos los valores posibles de entrada (x) para los cuales la función está definida.
- **Rango**: Conjunto de todos los valores posibles de salida (y) que puede tomar la función.

### Determinación del Dominio

Para funciones polinomiales: $D = \mathbb{R}$ (todos los números reales)
Para funciones racionales: excluir valores donde el denominador sea cero
Para funciones con raíz cuadrada: el radicando debe ser $\leq 0$

### Determinación del Rango

- Analizar el comportamiento de la función
- Identificar valores máximos y mínimos
- Considerar las restricciones del contexto del problema

## 2. Tipos de Funciones Polinomiales

### Clasificación por Grado

1. **Grado 0 (Constante)**: $f(x) = c$
2. **Grado 1 (Lineal)**: $f(x) = mx + b$
3. **Grado 2 (Cuadrática)**: $f(x) = ax^2 + bx + c$
4. **Grado 3 (Cúbica)**: $f(x) = ax^3 + bx^2 + cx + d$
5. **Grado n**: $f(x) = a_nx^n + a_{n-1}x^{n-1} + ... + a_1x + a_0$

### Características Generales

- Dominio: $\mathbb{R}$ para todas las funciones polinomiales
- Continuidad en todo su dominio
- Diferenciables en todo punto de su dominio

## 3. Función Lineal y Variación

### Función Lineal

**Forma general**: $f(x) = mx + b$

- $m$: pendiente (razón de cambio constante)
- $b$: ordenada al origen (intersección con eje y)

### Aplicaciones de la Función Lineal

1. **Problemas de costo**: Costo total = Costo fijo + Costo variable × cantidad
2. **Movimiento uniforme**: Distancia = velocidad × tiempo + posición inicial
3. **Conversiones**: Celsius a Fahrenheit: $F = \frac{9}{5}C + 32$
4. **Depreciación lineal**: Valor = Valor inicial - tasa × tiempo

### Variación Directa

$y = kx$ donde $k$ es la constante de proporcionalidad

- Si $x$ aumenta, $y$ aumenta proporcionalmente
- La gráfica pasa por el origen

### Variación Inversa

$y = \frac{k}{x}$ donde $k$ es constante

- Si $x$ aumenta, $y$ disminuye proporcionalmente
- Producto $xy = k$ (constante)

## 4. Formas de la Ecuación Cuadrática

### Forma Estándar
$f(x) = ax^2 + bx + c$

- $a \neq 0$
- Fácil identificación de coeficientes
- Útil para encontrar la ordenada al origen

### Forma Factorizada

$f(x) = a(x - r_1)(x - r_2)$

- $r_1$ y $r_2$ son las raíces de la función
- Directa identificación de las intersecciones con el eje x
- Útil cuando se conocen las raíces

### Forma Vértice (Canónica)

$f(x) = a(x - h)^2 + k$

- $(h, k)$ son las coordenadas del vértice
- $h = -\frac{b}{2a}$ (eje de simetría)
- $k = f(h)$ (valor máximo o mínimo)
- Útil para analizar el comportamiento de la parábola

## 5. Función Cuadrática y Modelos Cuadráticos

### Características de la Función Cuadrática

- **Gráfica**: Parábola
- **Dominio**: $\mathbb{R}$
- **Rango**: 
  - Si $a > 0$: $[k, +\infty)$ (parábola abre hacia arriba)
  - Si $a < 0$: $(-\infty, k]$ (parábola abre hacia abajo)

### Elementos Importantes

1. **Vértice**: $(h, k) = \left(-\frac{b}{2a}, f\left(-\frac{b}{2a}\right)\right)$
2. **Eje de simetría**: $x = -\frac{b}{2a}$
3. **Raíces**: Soluciones de $ax^2 + bx + c = 0$
4. **Discriminante**: $\Delta = b^2 - 4ac$
   - $\Delta > 0$: dos raíces reales distintas
   - $\Delta = 0$: una raíz real doble
   - $\Delta < 0$: no hay raíces reales

### Aplicaciones de Modelos Cuadráticos

1. **Tiro parabólico**: $h(t) = -\frac{1}{2}gt^2 + v_0t + h_0$
2. **Área de figuras**: Optimización de perímetros y áreas
3. **Problemas de maximización/minimización**: Ingresos, ganancias, costos
4. **Movimiento acelerado**: $s(t) = s_0 + v_0t + \frac{1}{2}at^2$

### Estrategias de Resolución

1. Identificar las variables del problema
2. Establecer la ecuación cuadrática apropiada
3. Determinar la forma más conveniente (estándar, factorizada o vértice)
4. Analizar el contexto para interpretar las soluciones
5. Verificar que las soluciones tengan sentido en el problema original

### Optimización con Funciones Cuadráticas

Para encontrar el valor máximo o mínimo:

1. Identificar si $a > 0$ (mínimo) o $a < 0$ (máximo)
2. Calcular el vértice: $x = -\frac{b}{2a}$
3. Evaluar $f\left(-\frac{b}{2a}\right)$ para obtener el valor óptimo
4. Interpretar el resultado en el contexto del problema