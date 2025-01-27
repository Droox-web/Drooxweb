Relacionado con [[Polinomios]]
$$\frac{x^2+2x+1}{x^2-1}\cdot \frac{x+3}{x-1}\cdot \frac{x^2+1}{x^2+4x+3}$$
## Simplificación de la expresión
Simplificar la expresión:

$$\frac{x^2+2x+1}{x^2-1}\cdot \frac{x+3}{x-1}\cdot \frac{x^2+1}{x^2+4x+3}$$
### Solución

Dada la expresión:

$$
\frac{x^2+2x+1}{x^2-1}\cdot \frac{x+3}{x-1}\cdot \frac{x^2+1}{x^2+4x+3}
$$

1. **Factorizamos cada uno de los términos.**

   - $x^2 + 2x + 1 = (x + 1)^2$
   - $x^2 - 1 = (x - 1)(x + 1)$
   - $x^2 + 4x + 3 = (x + 1)(x + 3)$

   Reescribimos la expresión con las factorizaciones:

   $$
   \frac{(x + 1)^2}{(x - 1)(x + 1)} \cdot \frac{x + 3}{x - 1} \cdot \frac{x^2 + 1}{(x + 1)(x + 3)}
   $$

2. **Multiplicamos los factores que se pueden multiplicar.**

   Ahora tenemos:

   $$
   = \frac{(x + 1)(x + 1)(x + 3)(x^2 + 1)}{(x - 1)(x + 1)(x - 1)(x + 1)(x + 3)}
   $$

3. **Cancelamos términos comunes.**

   Cancelamos $(x + 1)$ y $(x + 3)$:

   $$
   = \frac{(x^2 + 1)}{(x - 1)(x - 1)}
   $$
4. **Expandimos los factores restantes.** El denominador, la potencia se expande como:  $$(x - 1)(x - 1) = x^2 - 2x + 1$$ 5. **Resultado final:** La expresión simplificada es: $$ = \frac{x^2 + 1}{x^2 - 2x + 1} $$
---

$$\frac{x^3+2x^2-x-2}{x^2-3x+2}:\frac{x^2+x-2}{x^2-4}$$
### Solución de la operación 
$$\frac{x^3+2x^2-x-2}{x^2-3x+2}:\frac{x^2+x-2}{x^2-4}$$

#### Paso 1: Cambiar la división a multiplicación
$$\frac{x^3+2x^2-x-2}{x^2-3x+2} \cdot \frac{x^2-4}{x^2+x-2}$$

#### Paso 2: Factorizar cada polinomio

1. **Numerador: $x^3+2x^2-x-2$**

   Para factorizarlo, buscamos raíces mediante prueba y error. Probamos con $x = -2$:

   $$(-2)^3 + 2(-2)^2 - (-2) - 2 = -8 + 8 + 2 - 2 = 0$$

   Por lo tanto, $x + 2$ es un factor. Usamos Ruffini para factorizar:

|     |  1  |  2  | -1  | -2  |
| :-: | :-: | :-: | :-: | :-: |
| -2  |     | -2  |  0  |  2  |
|     |  1  |  0  | -1  |  0  |

   Entonces, $x^3+2x^2-x-2 = (x+2)(x^2-1) = (x+2)(x-1)(x+1)$.

2. **Denominador: $x^2-3x+2$**

   Factorizamos:

   $$x^2-3x+2 = (x-1)(x-2)$$

3. **Numerador: $x^2-4$**

   Factorizamos:

   $$x^2-4 = (x-2)(x+2)$$

4. **Denominador: $x^2+x-2$**

   Factorizamos:

   $$x^2+x-2 = (x-1)(x+2)$$

#### Paso 3: Sustituir las factorizaciones en la operación
$$\frac{(x+2)(x-1)(x+1)}{(x-1)(x-2)} \cdot \frac{(x-2)(x+2)}{(x-1)(x+2)}$$

#### Paso 4: Multiplicar las 
fracciones
$$= \frac{(x+2)(x-1)(x+1)(x-2)(x+2)}{(x-1)(x-2)(x-1)(x+2)}$$

#### Paso 5: Cancelar términos
1. Cancelamos $(x+2)$.
2. Cancelamos $(x-1)$.
3. Cancelamos $(x-2)$.

#### Paso 6: Resultado final
$$= \frac{(x+1)(x+2)}{x-1}=\frac{x^2+3x+2}{x-1}$$





