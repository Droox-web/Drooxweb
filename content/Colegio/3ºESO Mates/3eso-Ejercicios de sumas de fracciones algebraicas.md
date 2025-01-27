Relacionado con [[Polinomios]]
##### Suma de fracciones algebraicas
Para sumar fracciones algebraicas, al igual que para sumar fracciones usuales, necesitamos que estas tengan denominador común (pues no se puede sumar o restar fracciones de distinto denominador). 

Para ello, haremos el mínimo común múltiplo de los denominadores y con ello buscaremos fracciones equivalentes para poder realizar la operación.

En general$$\frac{P(x)}{Q(x)}+\frac{R(x)}{S(x)}=\frac{P'(x)}{T(x)}+\frac{R'(x)}{T(x)}=\frac{P'(x)+R'(x)}{T(x)}$$Donde $T(x)$ es el $m.c.m\left[Q(x),S(x)\right]$. $P'(x)$ y $R'(x)$ son los polinomios que hacen que las fracciones $\frac{P(x)}{Q(x)}, \frac{R(x)}{S(x)}$ y $\frac{P'(x)}{T(x)}, \frac{R'(x)}{T(x)}$ sean equivalentes.

Veamos un ejemplo:$$\frac{1}{x}+\frac{2x}{x-1}$$Buscamos el $m.c.m. (x, x-1)$ que al ser factores distintos (ver factorización más arriba) es directamente su producto$$m.c.m. (x, x-1)=x\cdot (x-1)$$Por lo que las fracciones equivalentes serán$$\frac{x-1}{x\cdot (x-1)}+\frac{2x^2}{x\cdot (x-1)}$$Pues el primer numerador se multiplica por el $x-1$ que le faltaba al denominador y el segundo numerador se multiplica por la $x$ que le faltaba al denominador.

Ahora podemos sumar numeradores$$\frac{x-1+2x^2}{x\cdot (x-1)}=\frac{2x^2+x-1}{x\cdot (x-1)}$$Y finalmente, podríamos intentar simplificar la fracción. Para ello vemos si el numerador puede factorizarse en $x$ que ***no puede si no se puede sacar factor común*** o en $(x-1)$ ***usando el teorema del resto***$$\left .2x^2+x-1\right|_{x=1}=2+1-1=2\neq 0$$No es divisible, por lo que no se puede factorizar y por ende no se puede simplificar. Operamos el denominador $$x(x-1)=x^2-x$$y queda finalmente que la suma es$$\frac{1}{x}+\frac{2x}{x-1}=\frac{2x^2+x-1}{x^2-x}$$
#### Ejercicios

# Ejercicios de sumas de fracciones algebraicas

1. Simplifica la siguiente expresión:
   $$ \frac{2x}{x + 3} + \frac{3}{x + 3} $$

---

2. Simplifica la siguiente expresión:
   $$ \frac{4x}{x - 2} + \frac{5}{x + 2} $$

---

3. Simplifica la siguiente expresión:
   $$ \frac{3x + 2}{x^2 - 1} + \frac{x - 1}{x^2 - 1} $$

---

4. Simplifica la siguiente expresión:
   $$ \frac{x}{x + 4} + \frac{2x + 8}{x^2 - 16} $$

---

5. Simplifica la siguiente expresión:
   $$ \frac{2x + 1}{x - 3} + \frac{4x}{x + 3} $$

---

6. Simplifica la siguiente expresión:
   $$ \frac{5x}{x^2 - 9} + \frac{2}{x - 3} $$

---

7. Simplifica la siguiente expresión:
   $$ \frac{x^2 + 3x}{x + 1} + \frac{2x + 1}{x - 1} $$

---

8. Simplifica la siguiente expresión:
   $$ \frac{3x + 4}{x^2 - 4} + \frac{x - 2}{x + 2} $$

---

9. Simplifica la siguiente expresión:
   $$ \frac{2x + 3}{x - 5} + \frac{x^2 - 25}{x + 5} $$

---

10. Simplifica la siguiente expresión:
    $$ \frac{4x}{x^2 - 16} + \frac{6}{x + 4} $$

---

Soluciones en [[Soluciones de Ejercicios de sumas de fracciones algebraicas]]


