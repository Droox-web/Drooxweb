Preparados para 4ºESO

Ver: [[Sistemas de ecuaciones lineales]]

Enunciados en: [[4eso-Problemas de Gauss 4ºESO]]

---
### Problema 1
Un grupo de estudiantes financia su viaje de fin de curso con la venta de participaciones de lotería, por importe de 1, 2 y 5 euros. Han recaudado, en total, 600 euros y han vendido el doble de participaciones de 1 euro que de 5 euros. Si han vendido un total de 260 participaciones, calcula el número de participaciones que han vendido de cada importe.

**Planteamiento del sistema de ecuaciones:**
1. Sea $x$ el número de participaciones de 1 euro, $y$ el número de participaciones de 2 euros, y $z$ el número de participaciones de 5 euros.
2. Ecuaciones:
   - Total de participaciones: $x + y + z = 260$
   - Total recaudado: $1x + 2y + 5z = 600$
   - El doble de participaciones de 1 euro que de 5 euros: $x = 2z$

**Sistema de ecuaciones:**
$$
\left\lbrace\begin{array}{l}
x + y + z = 260 \\
x + 2y + 5z = 600 \\
x - 2z = 0 \\
\end{array}\right.
$$

**Resolución paso a paso con el método de Gauss:**

1. Escribe el sistema en forma de matriz aumentada:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 260 \\
   1 & 2 & 5 & | & 600 \\
   1 & 0 & -2 & | & 0 \\
   \end{pmatrix}
   $$

2. Restamos la primera fila a la segunda y a la tercera:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 260 \\
   0 & 1 & 4 & | & 340 \\
   0 & -1 & -3 & | & -260 \\
   \end{pmatrix}
   $$

3. Sumamos la segunda fila a la tercera:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 260 \\
   0 & 1 & 4 & | & 340 \\
   0 & 0 & 1 & | & 80 \\
   \end{pmatrix}
   $$

4. Sustituyendo $z = 80$ en la segunda fila:
   $$
   y + 4(80) = 340 \Rightarrow y = 20
   $$

5. Sustituyendo $y = 20$ y $z = 80$ en la primera fila:
   $$
   x + 20 + 80 = 260 \Rightarrow x = 160
   $$

**Solución:**
- $x = 160$, $y = 20$, $z = 80$

---

### Problema 2
En una sucursal de una agencia de viajes se vende un total de 60 billetes de avión con destino a Londres, París y Roma. Sabiendo que el número de billetes para París es el doble de los vendidos para los otros dos destinos conjuntamente y que para Roma se emiten dos billetes más que la mitad de los vendidos para Londres, ¿Cuántos billetes se han vendido para cada uno de los destinos?

**Planteamiento del sistema de ecuaciones:**
1. Sea $x$ el número de billetes para Londres, $y$ para París, y $z$ para Roma.
2. Ecuaciones:
   - Total de billetes: $x + y + z = 60$
   - El número de billetes para París es el doble de los vendidos para los otros dos destinos conjuntamente: $y = 2(x + z)$
   - Para Roma se emiten dos billetes más que la mitad de los vendidos para Londres: $z = \frac{x}{2} + 2$

**Sistema de ecuaciones:**
$$
\left\lbrace\begin{array}{l}
x + y + z = 60 \\
y - 2x - 2z = 0 \\
2z - x = 4 \\
\end{array}\right.
$$

**Resolución paso a paso con el método de Gauss:**

1. Escribe el sistema en forma de matriz aumentada:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 60 \\
   -2 & 1 & -2 & | & 0 \\
   -1 & 0 & 2 & | & 4 \\
   \end{pmatrix}
   $$

2. Multiplicamos la primera fila por 2 y la sumamos a la segunda y tercera filas:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 60 \\
   0 & 3 & 0 & | & 120 \\
   0 & 1 & 3 & | & 64 \\
   \end{pmatrix}
   $$

3. Dividimos la segunda fila entre 3:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 60 \\
   0 & 1 & 0 & | & 40 \\
   0 & 1 & 3 & | & 64 \\
   \end{pmatrix}
   $$

4. Se tiene que $y=40$ y podemos sustituir en la tercera para obtener z:
$$40+3z=64 \Rightarrow 3z=24 \Rightarrow z=8$$
   Ahora sustituimos en la primera para obtener $x$ $$
   x + 40 + 8 = 60 \Rightarrow x = 12
   $$

**Solución:**
- $x = 12$, $y = 40$, $z = 8$

---

### Problema 3
En un comercio de bricolaje se venden listones de madera de tres longitudes 90 cm, 1,5 m y 2,4 m, cuyos precios respectivos son 4 euros, 6 euros y 10 euros. Un cliente ha comprado 19 listones, con una longitud total de 30 m, que le han costado 126 euros en total. Calcula el número de listones de cada tipo que ha comprado el cliente.

**Planteamiento del sistema de ecuaciones:**
1. Sea $x$ el número de listones de 90 cm, $y$ de 1,5 m, y $z$ de 2,4 m.
2. Ecuaciones:
   - Total de listones: $x + y + z = 19$
   - Longitud total: $0.9x + 1.5y + 2.4z = 30$
   - Costo total: $4x + 6y + 10z = 126$

**Sistema de ecuaciones:**
$$
\left\lbrace\begin{array}{l}
x + y + z = 19 \\
0.9x + 1.5y + 2.4z = 30 \\
4x + 6y + 10z = 126 \\
\end{array}\right.
$$

**Resolución paso a paso con el método de Gauss:**

1. Multiplicamos la segunda ecuación por 10 para eliminar decimales:
   $$
   9x + 15y + 24z = 300
   $$

   La matriz aumentada es:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 19 \\
   9 & 15 & 24 & | & 300 \\
   4 & 6 & 10 & | & 126 \\
   \end{pmatrix}
   $$

2. Restamos 9 veces la primera fila a la segunda y 4 veces la primera fila a la tercera:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 19 \\
   0 & 6 & 15 & | & 129 \\
   0 & 2 & 6 & | & 50 \\
   \end{pmatrix}
   $$

3. Multiplicamos la tercera fila por 3:
   $$
   \begin{pmatrix}
   1 & 1 & 1 & | & 19 \\
   0 & 6 & 15 & | & 129 \\
   0 & 6 & 18 & | & 150 \\
   \end{pmatrix}
   $$

4. Restamos la segunda fila a la tercera:
   $$
      \begin{pmatrix}
   1 & 1 & 1 & | & 19 \\
   0 & 6 & 15 & | & 129 \\
   0 & 0 & 3 & | & 21 \\
   \end{pmatrix}
   
   $$

5. De lo que se tiene que $3z=21 \Rightarrow z=7$.
6. Sustituimos en la segunda $6y+15\cdot 7=129 \Rightarrow 6y=129-105 \Rightarrow y=4$
7. Sustituimos en la tercera $x+4+7=19 \Rightarrow x=8$
   
**Solución:**
- $x = 8$, $y = 4$, $z = 7$
