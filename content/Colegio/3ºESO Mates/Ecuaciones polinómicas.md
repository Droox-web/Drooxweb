Las [[Ecuaciones|ecuaciones]] polinómicas son ecuaciones de la forma $P(x)=0$ donde $P(x)$ es un [[Polinomios|polinomio]].
Dependiendo del grado de la ecuación la resolveremos de distintas formas.

# Ecuaciones polinómicas de grado 1.

Una ecuación polinómica de grado 1, también conocida como **ecuación lineal**, tiene la forma general:

$$ ax + b = 0 $$

Donde:
- $a$ es el coeficiente de $x$ (no puede ser igual a 0).
- $b$ es un término constante.
- $x$ es la incógnita que queremos encontrar.

## Pasos para resolver una ecuación de grado 1:

1. **Aislar el término con $x$**:  
   Mueve el término constante ($b$) al otro lado de la ecuación restando o sumando ambos lados de la ecuación:

   $$ ax + b = 0 $$  
   $$ ax = -b $$

2. **Despejar $x$**:  
   Ahora divide ambos lados de la ecuación por el coeficiente de $x$ ($a$) para despejar la incógnita:

   $$ x = \frac{-b}{a} $$

## Ejemplo:

Resolvamos la ecuación:

$$ 3x + 5 = 0 $$

- **Paso 1**: Mover el término constante ($5$) al otro lado:

  $$ 3x = -5 $$

- **Paso 2**: Dividimos ambos lados por el coeficiente de $x$ ($3$):

  $$ x = \frac{-5}{3} $$

Por lo tanto, la solución es $x = \frac{-5}{3}$.

# Ecuaciones polinómicas de grado mayor que 2

Para resolver una **ecuación polinómica de grado mayor que 2**, como una ecuación cúbica ($x^3$) o cuártica ($x^4$), se suelen usar una combinación de técnicas, dependiendo de la estructura del polinomio. Algunos de los métodos más comunes incluyen la **descomposición en factores** (como el **método de Ruffini**) y el uso de la **fórmula cuadrática** para reducir la ecuación una vez que se ha factorizado.

## Pasos para resolver una ecuación polinómica de grado mayor que 2

---
## 1. **Buscar factor común**

En caso de que el polinomio tenga algún factor común, podemos encontrar la solución $x=0$ extrayendo el factor común antes de nada.

$$x^3-x^2-2x=0 \rightarrow x\cdot (x^2-x-2)=0$$

De donde se tiene que una solución es $x=0$. Si el polinomio que queda entre paréntesis es de grado 2 como en este caso, lo resolvemos mediante la ecuación de segundo grado vista en el apartado anterior. $$x^2-x-2=0$$
Cuyas soluciones son $x=2$ y $x=-1$.

Es decir, $x^3-x^2-2x=0$ tiene como soluciones $x=0$, $x=2$ y $x=-1$.
## 2. **Buscar raíces evidentes o aplicar el método de Ruffini**

Si el polinomio dentro del paréntesis tras sacar factor común sigue siendo de grado mayor que 2 (o si no se puede sacar factor común) no podemos usar la fórmula de segundo grado. Primero, se pueden probar raíces mediante el **método de tanteo**, probando valores que sean divisores del término independiente. Para un polinomio de grado mayor que 2 de la forma:

$$ P(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_1x + a_0 = 0 $$

Se prueban las soluciones racionales posibles (que pueden ser divisores del término independiente $a_0$ divididos entre los divisores del coeficiente principal $a_n$). Si se encuentra una raíz $r$, entonces el polinomio se puede dividir por $x - r$ utilizando el **método de Ruffini**.

### Ejemplo:
Resolver la ecuación:

$$ x^3 - 4x^2 + 5x - 2 = 0 $$

- **Paso 1:** Probar posibles soluciones racionales: $\pm 1, \pm 2$ (divisores de $a_0 = -2$).
  Probamos $x = 1$:
  $$ P(1) = 1^3 - 4(1^2) + 5(1) - 2 = 1 - 4 + 5 - 2 = 0 $$
  Como $P(1) = 0$, $x = 1$ es una raíz (solución).

- **Paso 2:** Aplicar **Ruffini** para dividir el polinomio por $x - 1$:

| 1 | -4 | 5  | -2  |  
|---|----|----|-----|  
|   |  1 | -3 |  2  |  
|---|----|----|-----|  
| 1 | -3 | 2  |  0  |  

El cociente es $x^2 - 3x + 2$.

- **Paso 3:** Resolver el polinomio cuadrático resultante:
  $$ x^2 - 3x + 2 = 0 $$

  Factorizamos:
  $$ (x - 1)(x - 2) = 0 $$

  Las soluciones son $x = 1$ y $x = 2$.

- **Paso 4:** Las raíces de la ecuación original son:
  $$ x = 1, \quad x = 1, \quad x = 2 $$

---

## 2. **Uso de la fórmula cuadrática**

Después de usar el **método de Ruffini** para dividir el polinomio, si se reduce a un polinomio de grado 2, se puede aplicar la **fórmula cuadrática** para obtener las soluciones restantes, como se mostró en el ejemplo anterior.

---

## 3. **Factorización completa**

Si se puede factorizar completamente el polinomio, las raíces se obtienen resolviendo cada uno de los factores igualados a 0. Algunas técnicas de factorización útiles incluyen:

- **Sacar factor común**: Si todos los términos tienen un factor en común, se puede factorizar para reducir el grado de la ecuación.
- **Factorización por agrupación**: Se agrupan términos para simplificar la factorización.
- **Teorema del residuo** y **Ruffini**: Se utilizan para descomponer el polinomio una vez se ha encontrado una raíz.

---

## 4. **Raíces complejas**

Si después de factorización o aplicación de la fórmula cuadrática el discriminante es negativo, se obtendrán raíces complejas. Estas raíces tendrán la forma:

$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

con un discriminante negativo que produce números imaginarios.

---

### Ejemplo de polinomio de grado mayor a 2

Resolver:

$$ x^4 - 5x^3 + 6x^2 = 0 $$

- **Paso 1:** Sacar factor común:
  $$ x^2(x^2 - 5x + 6) = 0 $$

- **Paso 2:** Resolver $x^2 = 0$, que da $x = 0$ doble.

- **Paso 3:** Resolver el polinomio cuadrático:
  $$ x^2 - 5x + 6 = 0 $$

  Factorizamos:
  $$ (x - 2)(x - 3) = 0 $$

- **Paso 4:** Las soluciones finales son:
  $$ x = 0, \quad x = 2, \quad x = 3 $$

---

Con estos métodos combinados, se puede resolver cualquier polinomio de grado mayor que 2.

Ejercicios en [[Ejercicios ecuaciones polinómicas]]

