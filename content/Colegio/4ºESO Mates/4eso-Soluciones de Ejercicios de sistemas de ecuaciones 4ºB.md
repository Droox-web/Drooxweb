### Sistema 1
Resuelve el siguiente sistema:
$$
\begin{cases}
x + 2y + 3z = 14 \\
2x + y + z = 9 \\
x - y + z = 2
\end{cases}
$$

1. Escribimos el sistema en forma matricial:
   $$
\left(
\begin{array}{ccc|c}
  1 & 2 & 3 & 14 \\
   2 & 1 & 1 & 9\\
   1 & -1 & 1 & 2
\end{array}
\right)
   $$

2. Eliminamos $x$ de las ecuaciones 2 y 3 usando la ecuación 1:
   - 2$E_1$$-E_2$
     $$
     2(x + 2y + 3z) - (2x + y + z) \Rightarrow 3y + 5z = 19
     $$
   - $E_1-E_2$
     $$
     (x + 2y + 3z) - (x - y + z) \Rightarrow 3y + 2z = 12
     $$

   Ahora el sistema es:
$$\left(
\begin{array}{cc|c}
  3 & 5 & 19\\
   3 & 2 & 12
\end{array}
\right)
$$
   

3. $E_1-E_2$:
   $$   3y + 5z -(3y + 2z) \Rightarrow 3z = 7
$$ $$ \left(\begin{array}{c|c}
  3 & 7\\
\end{array}
\right)$$
   Resolviendo, obtenemos $z = 7/3$.

4. Sustituimos $z = 7/3$ en la ecuación 2:
   $$
   3y + 5(7/3) = 19 \Rightarrow y = 22/9
   $$

5. Sustituimos $y = 22/9$ y $z = 7/3$ en la ecuación 1:
   $$
   x + 2(22/9) + 3(7/3) = 14 \Rightarrow x = 19/9
   $$

**Solución**: $(x,y,z)=(\frac{19}{9}, \frac{22}{9}, \frac{7}{3})$.

---
### Sistema 2
$$
\begin{cases}
x + y - z = 3 \\
2x + 3y + 4z = 0 \\
3x - y - z = 7
\end{cases}
\ \ \ \ \ \ \
\text{Solución:} \ \ \ \

\left \lbrace \begin{aligned}
x &= 2 \\
y &= 0 \\
z &= -1
\end{aligned} \right .
$$

---
### Sistema 3

## Resolución mediante el método de Gauss

Dado el sistema:

$$
\begin{cases}
x + 2y - z = 2 \\
2x + y + 3z = 1  \\
3x - y + z = 0 
\end{cases}
$$

### Paso 1: Representar el sistema en forma de matriz aumentada

La matriz aumentada del sistema es:

$$
\begin{pmatrix}
1 & 2 & -1 & 2 \\
2 & 1 & 3 & 1 \\
3 & -1 & 1 & 0
\end{pmatrix}.
$$

### Paso 2: Realizar operaciones fila para triangular la matriz

#### (a) Eliminar los elementos debajo del pivote $a_{11} = 1$
Restamos $2 \cdot F_1$ de $F_2$ y $3 \cdot F_1$ de $F_3$:

$$
F_2 \to F_2 - 2F_1, \quad F_3 \to F_3 - 3F_1.
$$

Los cálculos son:

Para $F_2$:
$$
\begin{pmatrix}
2 & 1 & 3 & 1
\end{pmatrix}
-
2 \cdot 
\begin{pmatrix}
1 & 2 & -1 & 2
\end{pmatrix}
=
\begin{pmatrix}
0 & -3 & 5 & -3
\end{pmatrix}.
$$

Para $F_3$:
$$
\begin{pmatrix}
3 & -1 & 1 & 0
\end{pmatrix}
-
3 \cdot
\begin{pmatrix}
1 & 2 & -1 & 2
\end{pmatrix}
=
\begin{pmatrix}
0 & -7 & 4 & -6
\end{pmatrix}.
$$

La matriz queda como:

$$
\begin{pmatrix}
1 & 2 & -1 & 2 \\
0 & -3 & 5 & -3 \\
0 & -7 & 4 & -6
\end{pmatrix}.
$$

#### (b) Eliminar los elementos debajo del pivote $a_{22} = -3$
Dividimos $F_2$ por $-3$ para hacer que $a_{22} = 1$:

$$
F_2 \to \frac{F_2}{-3}.
$$

Para $F_2$:
$$
\begin{pmatrix}
0 & -3 & 5 & -3
\end{pmatrix}
\div (-3)
=
\begin{pmatrix}
0 & 1 & -\frac{5}{3} & 1
\end{pmatrix}.
$$

Luego, eliminamos el elemento $a_{32} = -7$ restando $7 \cdot F_2$ de $F_3$:

$$
F_3 \to F_3 - 7F_2.
$$

Para $F_3$:
$$
\begin{pmatrix}
0 & -7 & 4 & -6
\end{pmatrix}
-
7 \cdot
\begin{pmatrix}
0 & 1 & -\frac{5}{3} & 1
\end{pmatrix}
=
\begin{pmatrix}
0 & 0 & \frac{29}{3} & -13
\end{pmatrix}.
$$

La matriz queda como:

$$
\begin{pmatrix}
1 & 2 & -1 & 2 \\
0 & 1 & -\frac{5}{3} & 1 \\
0 & 0 & \frac{29}{3} & -13
\end{pmatrix}.
$$

#### (c) Simplificar el pivote $a_{33} = \frac{29}{3}$
Dividimos $F_3$ por $\frac{29}{3}$ para que $a_{33} = 1$:

$$
F_3 \to \frac{F_3}{\frac{29}{3}}.
$$

Para $F_3$:
$$
\begin{pmatrix}
0 & 0 & \frac{29}{3} & -13
\end{pmatrix}
\div \frac{29}{3}
=
\begin{pmatrix}
0 & 0 & 1 & -\frac{39}{29}
\end{pmatrix}.
$$

La matriz queda como:

$$
\begin{pmatrix}
1 & 2 & -1 & 2 \\
0 & 1 & -\frac{5}{3} & 1 \\
0 & 0 & 1 & -\frac{39}{29}
\end{pmatrix}.
$$

### Paso 3: Sustitución hacia atrás

1. De $F_3$: $z = -\frac{39}{29}$.

2. Sustituyendo $z$ en $F_2$:
$$
y - \frac{5}{3}z = 1.
$$
Sustituyendo $z = -\frac{39}{29}$:
$$
y - \frac{5}{3} \left(-\frac{39}{29}\right) = 1,
$$
$$
y + \frac{195}{87} = 1,
$$
$$
y = \frac{87}{87} - \frac{195}{87} = \frac{-108}{87} = \frac{18}{29}.
$$

3. Sustituyendo $y$ y $z$ en $F_1$:
$$
x + 2y - z = 2.
$$
Sustituyendo $y = \frac{18}{29}$ y $z = -\frac{39}{29}$:
$$
x + 2\left(\frac{18}{29}\right) - \left(-\frac{39}{29}\right) = 2,
$$
$$
x + \frac{36}{29} + \frac{39}{29} = 2,
$$
$$
x + \frac{75}{29} = 2,
$$
$$
x = 2 - \frac{75}{29} = \frac{58}{29} - \frac{75}{29} = \frac{7}{29}.
$$

### Solución final:

$$
\begin{cases}
x = \frac{7}{23}, \\
y = \frac{18}{23}, \\
z = -\frac{3}{23}.
\end{cases}
$$
