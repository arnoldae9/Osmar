---
title: "Física"
subtitle: "Cinemática"
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

# Cinemática - Resumen Completo

La **cinemática** es la rama de la mecánica que estudia el movimiento de los objetos sin considerar las fuerzas que lo causan. Se enfoca en describir la posición, velocidad y aceleración de los cuerpos en función del tiempo.

## 1. Movimiento Rectilíneo Uniforme (MRU)

El movimiento rectilíneo uniforme es aquel en el que un objeto se desplaza en línea recta con velocidad constante.

### Características:

- Velocidad constante (no hay aceleración)

- Trayectoria rectilínea

- Recorre distancias iguales en tiempos iguales

### Fórmulas principales:
\begin{formula}
$$x = x_0 + vt$$
$$v = \frac{\Delta x}{\Delta t} = \text{constante}$$
$$a = 0$$
\end{formula}

Donde:

- $x$ = posición final

- $x_0$ = posición inicial

- $v$ = velocidad

- $t$ = tiempo

- $a$ = aceleración

### Ejemplo:
Un automóvil viaja a 60 km/h por una carretera recta. Si parte del kilómetro 10, ¿en qué posición estará después de 2 horas?

**Solución:**

- $x_0 = 10$ km

- $v = 60$ km/h

- $t = 2$ h

- $x = 10 + (60)(2) = 130$ km

## 2. Movimiento Rectilíneo Uniformemente Acelerado (MRUA)

Es el movimiento en línea recta donde la velocidad cambia de manera constante debido a una aceleración uniforme.

### Características:

- Aceleración constante

- La velocidad cambia uniformemente

- Trayectoria rectilínea

### Fórmulas principales:

\begin{formula}
$$v = v_0 + at$$
$$x = x_0 + v_0t + \frac{1}{2}at^2$$
$$v^2 = v_0^2 + 2a(x - x_0)$$
\end{formula}

Donde:

- $v_0$ = velocidad inicial

- $v$ = velocidad final

- $a$ = aceleración

- $t$ = tiempo

### Ejemplo:
Un automóvil acelera desde el reposo a 3 m/s². ¿Qué velocidad tendrá y qué distancia habrá recorrido después de 5 segundos?

**Solución:**

- $v_0 = 0$ m/s

- $a = 3$ m/s²

- $t = 5$ s

Velocidad: $v = 0 + (3)(5) = 15$ m/s
Distancia: $x = 0 + (0)(5) + \frac{1}{2}(3)(5)^2 = 37.5$ m

## 3. Caída Libre de los Cuerpos

Es un caso especial del MRUA donde los objetos caen bajo la influencia únicamente de la gravedad.

### Características:

- Aceleración constante hacia abajo: $g = 9.8$ m/s²

- Movimiento vertical

- Se desprecia la resistencia del aire

### Fórmulas principales:

\begin{formula}
$$v = v_0 + gt$$
$$y = y_0 + v_0t + \frac{1}{2}gt^2$$
$$v^2 = v_0^2 + 2g(y - y_0)$$
\end{formula}

### Ejemplo:

Una pelota se deja caer desde una altura de 20 metros. ¿Con qué velocidad llega al suelo y cuánto tiempo tarda?

**Solución:**

- $y_0 = 20$ m

- $y = 0$ m

- $v_0 = 0$ m/s

- $g = 9.8$ m/s²

Para el tiempo: $0 = 20 + 0 \cdot t + \frac{1}{2}(-9.8)t^2$
Resolviendo: $t = \sqrt{\frac{40}{9.8}} = 2.02$ s

Para la velocidad: $v^2 = 0^2 + 2(-9.8)(0-20)$
$v = \sqrt{392} = 19.8$ m/s

## 4. Movimiento en un Plano

Análisis del movimiento en dos dimensiones, considerando componentes horizontales y verticales.

### Características:
- Movimiento en coordenadas $x$ e $y$
- Cada componente se analiza independientemente
- Uso de vectores para posición, velocidad y aceleración

### Fórmulas principales:
\begin{formula}
$$\vec{r} = x \hat{i} + y \hat{j}$$
$$\vec{v} = v_x \hat{i} + v_y \hat{j}$$
$$\vec{a} = a_x \hat{i} + a_y \hat{j}$$
$$|\vec{v}| = \sqrt{v_x^2 + v_y^2}$$
$$\theta = \arctan\left(\frac{v_y}{v_x}\right)$$
\end{formula}

### Ejemplo:
Un objeto se mueve con velocidad $v_x = 4$ m/s y $v_y = 3$ m/s. ¿Cuál es su velocidad total y dirección?

**Solución:**
$|\vec{v}| = \sqrt{4^2 + 3^2} = \sqrt{25} = 5$ m/s
$\theta = \arctan\left(\frac{3}{4}\right) = 36.87°$

## 5. Cinemática Rotacional

Estudio del movimiento de rotación de los objetos alrededor de un eje fijo.

### Características:
- Análogo al movimiento lineal pero con magnitudes angulares
- Velocidad angular y aceleración angular

### Fórmulas principales:
\begin{formula}
$$\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$$
$$\omega = \omega_0 + \alpha t$$
$$\omega^2 = \omega_0^2 + 2\alpha(\theta - \theta_0)$$
\end{formula}

**Relaciones lineales-angulares:**
$$s = r\theta$$
$$v = r\omega$$
$$a = r\alpha$$

Donde:

- $\theta$ = ángulo (radianes)

- $\omega$ = velocidad angular (rad/s)

- $\alpha$ = aceleración angular (rad/s²)

- $r$ = radio

### Ejemplo:
Una rueda gira desde el reposo con aceleración angular de 2 rad/s². ¿Qué velocidad angular tendrá después de 3 segundos?

**Solución:**

- $\omega_0 = 0$ rad/s

- $\alpha = 2$ rad/s²

- $t = 3$ s

- $\omega = 0 + (2)(3) = 6$ rad/s

## 6. Tiro Parabólico

Movimiento de proyectiles que siguen una trayectoria curva bajo la influencia de la gravedad.

### Características:

- Combinación de MRU horizontal y MRUA vertical

- Trayectoria parabólica

- Aceleración solo en dirección vertical ($g$)

### Fórmulas principales:

**Componente horizontal:**

\begin{formula}
$$x = x_0 + v_{0x}t$$
$$v_x = v_{0x} = \text{constante}$$
\end{formula}

**Componente vertical:**

\begin{formula}
$$y = y_0 + v_{0y}t - \frac{1}{2}gt^2$$
$$v_y = v_{0y} - gt$$
\end{formula}

**Velocidad inicial:**

\begin{formula}
$$v_{0x} = v_0\cos(\theta)$$
$$v_{0y} = v_0\sin(\theta)$$
\end{formula}

**Alcance máximo:**

\begin{formula}
$$R = \frac{v_0^2\sin(2\theta)}{g}$$
\end{formula}

**Altura máxima:**

\begin{formula}
$$H = \frac{v_0^2\sin^2(\theta)}{2g}$$
\end{formula}

### Ejemplo:
Un proyectil se lanza con velocidad inicial de 20 m/s a 30° sobre la horizontal. Calcular el alcance y la altura máxima.

**Solución:**

- $v_0 = 20$ m/s

- $\theta = 30°$

- $g = 9.8$ m/s²

Componentes de velocidad inicial:

- $v_{0x} = 20 \cdot \cos(30°) = 17.32$ m/s

- $v_{0y} = 20 \cdot \sin(30°) = 10$ m/s

Alcance: $R = \frac{20^2 \cdot \sin(60°)}{9.8} = 35.35$ m

Altura máxima: $H = \frac{20^2 \cdot \sin^2(30°)}{2 \cdot 9.8} = 5.10$ m

---

## Conceptos Clave

1. **Posición**: Ubicación de un objeto en el espacio

2. **Desplazamiento**: Cambio de posición (vector)

3. **Velocidad**: Razón de cambio de la posición

4. **Aceleración**: Razón de cambio de la velocidad

5. **Trayectoria**: Camino seguido por el objeto

6. **Sistema de referencia**: Marco desde el cual se observa el movimiento