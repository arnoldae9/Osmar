---
title: "Física"
subtitle: "Examen Cinemática"
author: "Prof. Arnoldo Del Toro Peña"
date: \today
subject: "Física"
grade: "Grado: 2° Año"
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
  - \fancyhead[L]{Física - Cinemática}
  - \fancyhead[R]{2° Grado}
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

## INSTRUCCIONES GENERALES
- Lee cuidadosamente cada pregunta antes de responder
- Muestra todos los procedimientos y fórmulas utilizadas
- Incluye las unidades en todas las respuestas numéricas
- Usa $g = 9.8$ m/s² para todos los cálculos de gravedad

---

## PARTE I: SELECCIÓN MÚLTIPLE (20 puntos)
*Selecciona la respuesta correcta. Cada pregunta vale 4 puntos.*

**1.** En el Movimiento Rectilíneo Uniforme (MRU), la característica principal es:

- a) La aceleración es constante

- b) La velocidad es constante

- c) La posición es constante

- d) El tiempo es constante

**2.** La fórmula para calcular la posición en el MRU es:

- a) $x = x_0 + v_0t + \frac{1}{2}at^2$

- b) $x = x_0 + vt$

- c) $v = v_0 + at$

- d) $v^2 = v_0^2 + 2a(x - x_0)$

**3.** En caída libre, un objeto que se deja caer desde el reposo tiene una velocidad inicial de:

- a) 9.8 m/s

- b) 0 m/s

- c) -9.8 m/s

- d) Depende de la altura

**4.** En el tiro parabólico, la componente horizontal de la velocidad:

- a) Aumenta constantemente

- b) Disminuye constantemente

- c) Permanece constante

- d) Varía según la gravedad

**5.** La unidad de la velocidad angular es:

- a) m/s

- b) rad/s

- c) m/s²

- d) rad/s²

---

## PARTE II: PROBLEMAS DE APLICACIÓN (50 puntos)
*Resuelve los siguientes problemas mostrando todo el procedimiento.*

### Problema 1: Movimiento Rectilíneo Uniforme (10 puntos)
Un tren viaja a velocidad constante de 80 km/h. Si en el momento inicial se encuentra en la posición $x_0 = 15$ km, determina:

- a) Su posición después de 3 horas (5 puntos)

- b) El tiempo que tardará en llegar a la posición $x = 300$ km (5 puntos)

### Problema 2: Movimiento Uniformemente Acelerado (15 puntos)

Un automóvil parte del reposo y acelera uniformemente a 2.5 m/s² durante 8 segundos. Calcula:

- a) La velocidad final alcanzada (5 puntos)

- b) La distancia recorrida durante este tiempo (5 puntos)

- c) La velocidad promedio durante el recorrido (5 puntos)

### Problema 3: Caída Libre (15 puntos)

Desde la azotea de un edificio de 45 metros de altura se deja caer una pelota. Determina:

- a) El tiempo que tarda en llegar al suelo (5 puntos)

- b) La velocidad con que impacta el suelo (5 puntos)

- c) La velocidad que tiene cuando ha caído la mitad de la altura (5 puntos)

### Problema 4: Tiro Parabólico (10 puntos)

Un proyectil se lanza desde el suelo con una velocidad inicial de 25 m/s formando un ángulo de 45° con la horizontal. Calcula:

- a) El alcance máximo horizontal (5 puntos)

- b) La altura máxima alcanzada (5 puntos)

---

## PARTE III: PREGUNTAS CONCEPTUALES (20 puntos)
*Responde de manera clara y concisa.*

### Pregunta 1 (5 puntos)

Explica la diferencia entre velocidad y aceleración. Proporciona un ejemplo de cada una.

### Pregunta 2 (5 puntos)

¿Por qué en el tiro parabólico la componente horizontal de la velocidad permanece constante mientras que la vertical cambia?

### Pregunta 3 (5 puntos)

En la cinemática rotacional, ¿cuál es la relación entre las magnitudes lineales y angulares? Menciona al menos dos ejemplos.

### Pregunta 4 (5 puntos)

Un objeto se mueve en línea recta con velocidad constante de 10 m/s. Después de 5 segundos, su velocidad es de 20 m/s. ¿Es esto un MRU o MRUA? Justifica tu respuesta y calcula la aceleración.

---

## PARTE IV: ANÁLISIS GRÁFICO (10 puntos)

*Observa la siguiente información y responde.*

### Problema de Análisis

Un objeto se mueve según la siguiente descripción:

- Primeros 4 segundos: velocidad constante de 6 m/s

- Siguientes 3 segundos: acelera uniformemente hasta alcanzar 15 m/s

- Últimos 2 segundos: velocidad constante de 15 m/s

**Preguntas:**

- a) Dibuja el gráfico velocidad vs tiempo (5 puntos)

- b) Calcula la distancia total recorrida (5 puntos)

---

## FÓRMULAS DE REFERENCIA

### MRU:

- $x = x_0 + vt$

- $v = \text{constante}$

### MRUA:

- $v = v_0 + at$

- $x = x_0 + v_0t + \frac{1}{2}at^2$

- $v^2 = v_0^2 + 2a(x - x_0)$

### Caída Libre:

- $v = v_0 + gt$

- $y = y_0 + v_0t + \frac{1}{2}gt^2$

- $v^2 = v_0^2 + 2g(y - y_0)$

### Tiro Parabólico:

- $v_{0x} = v_0\cos(\theta)$

- $v_{0y} = v_0\sin(\theta)$

- $R = \frac{v_0^2\sin(2\theta)}{g}$

- $H = \frac{v_0^2\sin^2(\theta)}{2g}$

### Cinemática Rotacional:

- $\omega = \omega_0 + \alpha t$

- $\theta = \theta_0 + \omega_0t + \frac{1}{2}\alpha t^2$

- $v = r\omega$

---
**Buena Suerte**
