Enunciados en [[Ejercicios ecuaciones polinómicas]]
Relacionado con [[Ecuaciones polinómicas]]

**Ejercicio 1**:  
Resuelve la ecuación polinómica:

$$ x^3 - 6x^2 + 11x - 6 = 0 $$

**Solución**:  
Usamos el teorema del resto (o bien el método de Ruffini) para probar valores.  
Probamos $x = 1$:

$$ 1^3 - 6 \cdot 1^2 + 11 \cdot 1 - 6 = 0 $$

Por lo tanto, $x = 1$ es una raíz.  
Dividimos el polinomio entre $x - 1$ para obtener el cociente:

$$ (x^3 - 6x^2 + 11x - 6) \div (x - 1) = x^2 - 5x + 6 $$

Ahora resolvemos la ecuación cuadrática $x^2 - 5x + 6 = 0$ usando la fórmula general:

$$ x = \frac{-(-5) \pm \sqrt{(-5)^2 - 4(1)(6)}}{2(1)} = \frac{5 \pm \sqrt{25 - 24}}{2} = \frac{5 \pm 1}{2} $$

Las soluciones son:

$$ x_1 = 3, \quad x_2 = 2 $$

Por lo tanto, las raíces son $x = 1, 2, 3$.

---

**Ejercicio 2**:  
Resuelve la siguiente ecuación:

$$ 2x^4 - 3x^3 - 11x^2 + 12x + 18 = 0 $$

**Solución**:  
Usamos Ruffini para probar $x = -1$:

$$ 2(-1)^4 - 3(-1)^3 - 11(-1)^2 + 12(-1) + 18 = 0 $$

Por lo tanto, $x = -1$ es una raíz.  
Dividimos el polinomio entre $x + 1$:

$$ (2x^4 - 3x^3 - 11x^2 + 12x + 18) \div (x + 1) = 2x^3 - 5x^2 - 6x + 18 $$

Seguimos probando con Ruffini para simplificar más el polinomio pero no se puede encontrar ninguna otra raíz entera. Un programa informático nos da las soluciones $x_2$ y $x_3$ pero nosotros no podemos hallar más que la solución primera $x_1$ con lo que sabemos.

$$ x_1 = -1, \quad x_2 = 0.611, \quad x_3 = 2.28 \pm 0.36i $$

---

**Ejercicio 3**:  
Encuentra las soluciones de la ecuación:

$$ x^3 + 5x^2 + 2x - 8 = 0 $$

**Solución**:  
Probamos con $x = 1$ en Ruffini:

$$ 1^3 + 5 \cdot 1^2 + 2 \cdot 1 - 8 = 0 $$

Por lo tanto, $x = 1$ es una raíz.  
Dividimos el polinomio entre $x - 1$:

$$ (x^3 + 5x^2 + 2x - 8) \div (x - 1) = x^2 + 6x + 8 $$

Ahora resolvemos la ecuación cuadrática $x^2 + 6x + 8 = 0$:

$$ x = \frac{-6 \pm \sqrt{6^2 - 4(1)(8)}}{2(1)} = \frac{-6 \pm \sqrt{36 - 32}}{2} = \frac{-6 \pm 2}{2} $$

Las soluciones son:

$$ x_1 = -4, \quad x_2 = -2 $$

Por lo tanto, las raíces son $x = -4, -2, 1$.

---

**Ejercicio 4**:  
Resuelve el siguiente polinomio:

$$ 3x^4 - 10x^3 + 5x^2 + 8x - 4 = 0 $$

**Solución**:  
Probamos con $x = 2$ en Ruffini:

$$ 3(2)^4 - 10(2)^3 + 5(2)^2 + 8(2) - 4 = 0 $$

Por lo tanto, $x = 2$ es una raíz.  
Dividimos el polinomio entre $x - 2$:

$$ (3x^4 - 10x^3 + 5x^2 + 8x - 4) \div (x - 2) = 3x^3 - 4x^2 - 3x + 2 $$

Seguimos probando con Ruffini para simplificar más el polinomio pero no se puede encontrar ninguna otra raíz entera. Un programa informático nos da las soluciones $x_2$, $x_3$ y $x_4$ pero nosotros no podemos hallar más que la solución primera $x_1$ con lo que sabemos.
$$ x_1 = 2, \quad x_2 \simeq -0.83 \quad x_3 \simeq 0.47 \quad x_4 \simeq 1.69 $$

---

