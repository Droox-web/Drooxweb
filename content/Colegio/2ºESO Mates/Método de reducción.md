El **método de reducción**, también conocido como **método de eliminación**, es una técnica utilizada para resolver [[Sistemas de ecuaciones lineales]]. El objetivo es eliminar una de las variables al combinar las ecuaciones de tal manera que se obtenga una nueva ecuación con solo una variable, que luego se puede resolver.

### Pasos para resolver un sistema de ecuaciones por el método de reducción:

1. **Multiplicar las ecuaciones (si es necesario)**:  
   Si las ecuaciones del sistema no están en forma que permita la eliminación directa de una de las variables, es posible que sea necesario multiplicar una o ambas ecuaciones por un número adecuado para que los coeficientes de una de las variables sean iguales o opuestos.

2. **Sumar o restar las ecuaciones**:  
   Una vez que los coeficientes de una de las variables son iguales o opuestos, sumamos o restamos las ecuaciones para eliminar esa variable. El resultado será una nueva ecuación con solo una variable.

3. **Resolver la ecuación resultante**:  
   Resolvemos la ecuación obtenida en el paso anterior para encontrar el valor de la variable restante.

4. **Sustituir el valor encontrado**:  
   Sustituimos el valor de la variable obtenida en una de las ecuaciones originales para encontrar el valor de la otra variable.

5. **Comprobar la solución**:  
   Comprobamos que los valores obtenidos para las variables satisfacen ambas ecuaciones del sistema.

### Ejemplo de resolución por el método de reducción:

Consideremos el siguiente sistema de ecuaciones:

$$
\begin{aligned}
2x + 3y &= 12 \\
4x - 3y &= 6
\end{aligned}
$$

**Paso 1: Multiplicar si es necesario**  
En este caso, los coeficientes de $y$ en ambas ecuaciones son opuestos ($+3$ y $-3$), por lo que podemos sumar las ecuaciones directamente para eliminar $y$.

**Paso 2: Sumar las ecuaciones**  
Sumamos las dos ecuaciones:

$$ (2x + 3y) + (4x - 3y) = 12 + 6 $$

Esto nos da:

$$ 6x = 18 $$

**Paso 3: Resolver para $x$**  
Ahora resolvemos para $x$:

$$ x = \frac{18}{6} = 3 $$

**Paso 4: Sustituir el valor de $x$**  
Sustituimos $x = 3$ en una de las ecuaciones originales, por ejemplo en la primera:

$$ 2(3) + 3y = 12 $$

$$ 6 + 3y = 12 $$

Restamos 6 de ambos lados:

$$ 3y = 6 $$

Ahora resolvemos para $y$:

$$ y = \frac{6}{3} = 2 $$

**Paso 5: Comprobar la solución**  
Comprobamos sustituyendo $x = 3$ y $y = 2$ en la segunda ecuación:

$$ 4(3) - 3(2) = 12 - 6 = 6 $$

La solución es correcta.

**Solución del sistema**:  
$$ x = 3, \, y = 2 $$

### Ventajas del método de reducción:
- Es eficiente cuando los coeficientes de las variables son fácilmente manipulables para la eliminación.
- Generalmente, es más rápido que el método de sustitución en sistemas con coeficientes que se pueden eliminar directamente.
- Es mucho más eficiente que los demás cuando tenemos más de dos variables.

