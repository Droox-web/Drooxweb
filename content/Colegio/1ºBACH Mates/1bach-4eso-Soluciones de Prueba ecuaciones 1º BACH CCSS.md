Enunciados en [[Prueba ecuaciones 1º BACH CCSS]]
# Ejercicio 1
$$5x^4 - 40x = 0$$

## Paso 1: Factorizar
Factorizamos sacando $5x$ como factor común:
$$ 5x(x^3 - 8) = 0 $$

## Paso 2: Resolver cada factor
1. Para $5x = 0$, obtenemos:
   $$ x = 0 $$

2. Para $x^3 - 8 = 0$, resolvemos:
   $$ x^3 = 8 $$
   Tomando la raíz cúbica:
   $$ x = 2 $$
Las otras dos soluciones son imaginarias.
## Solución final:
$$ x = 0, 2 $$

---

# Ejercicio 2
$$x^4 - 5x^2 + 4 = 0$$

## Paso 1: Hacer el cambio de variable
Sea $y = x^2$, la ecuación se transforma en:
$$ y^2 - 5y + 4 = 0 $$

## Paso 2: Resolver la ecuación cuadrática
Aplicamos la fórmula general:
$$ y = \frac{-(-5) \pm \sqrt{(-5)^2 - 4(1)(4)}}{2(1)} $$
$$ y = \frac{5 \pm \sqrt{25 - 16}}{2} = \frac{5 \pm \sqrt{9}}{2} $$
$$ y = \frac{5 \pm 3}{2} $$

Esto da:
1. $y = \frac{5 + 3}{2} = 4$
2. $y = \frac{5 - 3}{2} = 1$

## Paso 3: Volver al valor original de $x$
1. Si $y = 4$, entonces $x^2 = 4 \Rightarrow x = \pm 2$
2. Si $y = 1$, entonces $x^2 = 1 \Rightarrow x = \pm 1$

## Solución final:
$$ x = -2, -1, 1, 2 $$

---

# Ejercicio 3
$$ \frac{x+1}{x-1} + \frac{x}{x+1} = \frac{2x}{x^2 - 1} $$

## Paso 1: Identificar denominadores comunes
El denominador $x^2 - 1$ puede factorizarse como $(x-1)(x+1)$.

La ecuación se convierte en:
$$ \frac{x+1}{x-1} + \frac{x}{x+1} = \frac{2x}{(x-1)(x+1)} $$

## Paso 2: Unificar fracciones en el lado izquierdo
Hacemos la suma en el lado izquierdo:
$$ \frac{(x+1)(x+1) + x(x-1)}{(x-1)(x+1)} = \frac{2x}{(x-1)(x+1)} $$

Multiplicamos los numeradores:
$$ \frac{(x+1)^2 + x(x-1)}{(x-1)(x+1)} = \frac{2x}{(x-1)(x+1)} $$

Expandiendo los términos del numerador:
$$ \frac{x^2 + 2x + 1 + x^2 - x}{(x-1)(x+1)} = \frac{2x}{(x-1)(x+1)} $$

Simplificando:
$$ \frac{2x^2 + x + 1}{(x-1)(x+1)} = \frac{2x}{(x-1)(x+1)} $$

## Paso 3: Igualar los numeradores
Igualamos los numeradores de ambas fracciones:
$$ 2x^2 + x + 1 = 2x $$

Reorganizamos la ecuación:
$$ 2x^2 - x + 1 = 0 $$

## Paso 4: Resolver la ecuación cuadrática
Aplicamos la fórmula general:
$$ x = \frac{-(-1) \pm \sqrt{(-1)^2 - 4(2)(1)}}{2(2)} $$
$$ x = \frac{1 \pm \sqrt{1 - 8}}{4} $$
$$ x = \frac{1 \pm \sqrt{-7}}{4} $$

No hay solución real para esta ecuación.

## Solución final:
No tiene solución real.

---

# Ejercicio 4
$$x - x^2 - 3 = \sqrt{x - 1}$$

## Paso 1: Aislar el término con la raíz
Aislamos el radical en un lado de la ecuación:
$$\sqrt{x - 1} = x - x^2 - 3$$

## Paso 2: Elevar ambos lados al cuadrado
Elevamos ambos lados al cuadrado para eliminar la raíz:
$$ (x - 1) = (x - x^2 - 3)^2 $$

## Paso 3: Expandir el cuadrado
Expandimos el cuadrado en el lado derecho:
$$(x - x^2 - 3)^2 = x^4 - 2x^3 + 7x^2 - 6x + 9$$

La ecuación queda:
$$ x - 1 = x^4 - 2x^3 + 7x^2 - 6x + 9 $$

## Paso 4: Llevar todos los términos a un lado
Pasamos todos los términos al lado derecho para igualar a 0:
$$ 0 = x^4 - 2x^3 + 7x^2 - 7x + 10 $$

## Paso 5: Resolver la ecuación
La ecuación resultante es una ecuación polinómica de cuarto grado que no tiene solución mediante Ruffini (de hecho no tiene solución real pero eso no podéis saberlo). Dado que no encontramos solución por Ruffini, decimos:

**No encuentro solución entera mediante el método de Ruffini y por tanto no puedo hallar su solución.**

---

# Ejercicio 5
$$ 3^{x+2} = 4 $$

## Paso 1: Aplicar logaritmos
Aplicamos logaritmos en ambos lados de la ecuación:
$$ \log(3^{x+2}) = \log(4) $$

Aplicamos la propiedad de los logaritmos:
$$ (x+2)\log(3) = \log(4) $$

## Paso 2: Despejar $x$
$$ x + 2 = \frac{\log(4)}{\log(3)} $$
$$ x = \frac{\log(4)}{\log(3)} - 2 $$

## Solución final:
$$ x = \frac{\log(4)}{\log(3)} - 2 = -0, 738140492857085125800945771314478291400828719736239144258690112 ...$$

---

# Ejercicio 6
$$ \log_4{(10x - 2)} - \log_4(4x) = -\log_4(2) $$

## Paso 1: Aplicar propiedades de logaritmos
Usamos la propiedad de los logaritmos $\log_b(a) - \log_b(c) = \log_b\left(\frac{a}{c}\right)$:
$$ \log_4\left(\frac{10x-2}{4x}\right) = -\log_4(2) $$
 Metemos el signo menos de la izquierda$$-log_4(2)=log_4(2^{-1})=log_4\left(\frac{1}{2}\right)$$$$ \log_4\left(\frac{10x-2}{4x}\right) = log_4\left(\frac{1}{2}\right)$$
## Paso 2: Igualar los argumentos
Igualamos los argumentos de los logaritmos
$$ \frac{10x - 2}{4x} = \frac{1}{2} $$

## Paso 3: Resolver la ecuación
Multiplicamos ambos lados por $4x$:
$$ 10x - 2 = 2x $$

Llevamos todos los términos a un lado:
$$ 10x - 2x = 2 $$
$$ 8x = 2 $$

Despejamos $x$:
$$ x = \frac{2}{8} = \frac{1}{4} $$

## Solución final:
$$ x = \frac{1}{4} $$
