Las [[Ecuaciones|ecuaciones]] racionales son ecuaciones que involucran fracciones algebraicas. En general son de la forma $\frac{P(x)}{Q(x)}=0$ donde $P, Q$ son [[Polinomios]].

Para resolver una ecuación racional debemos buscar las soluciones de $P(x)=0$ teniendo en cuenta que dichas soluciones no cumplan a su vez que $Q(x)=0$.  En tal caso tendríamos una división por 0 y esta es una operación no definida.

**Veamos un ejemplo sencillo**:

$$\frac{x^2-1}{x+2}=0$$
Es una ecuación cuyas soluciones se obtienen de igualar $x^2-1=0$. Debemos tener en cuenta que la solución $x+2=0\rightarrow x=-2$ no sería válida. Buscamos sus soluciones: $$x^2-1=0$$
$$x^2=1$$
$$x=\pm \sqrt 1 =\pm 1$$
**Las soluciones son** $x=1, x=-1$.

Veamos un ejemplo más complicado; la ecuación $$\frac{2x}{x+3}+\frac{x}{x+2}=\frac{1}{x+3}$$
No está en la forma $\frac{P(x)}{Q(x)}=0$. Para colocarla en esta forma, operamos pasando al otro lado $$\frac{2x}{x+3}+\frac{x}{x+2}-\frac{1}{x+3}=0$$Y ahora realizamos la suma de fracciones algebraicas (ver [[Polinomios|polinomios]])

$$\frac{2x}{x+3}+\frac{x}{x+2}-\frac{1}{x+3}$$ Hacemos el denominador común$$\frac{2x(x+2)}{(x+3)(x+2)}+\frac{x(x+3)}{(x+2)(x+3)}-\frac{x+2}{(x+3)(x+2)}$$Y sumamos numeradores $$\frac{2x^2+4x+x^2+3x-x-2}{(x+3)(x+2)}$$Operamos$$\frac{3x^2+6x-2}{(x+3)(x+2)}$$
Luego la ecuación se queda $$\frac{3x^2+6x-2}{(x+3)(x+2)}=0$$Igualamos el numerador a 0, **teniendo en cuenta que las soluciones** $x=-3, x=-2$ **no valen** $$3x^2+6x-2=0$$Resolvemos con la fórmula de segundo grado y se tiene $x=\frac{-3-\sqrt{15}}{3}\simeq -2.29$ y  $x=\frac{-3+\sqrt{15}}{3}\simeq 0.29$
**Ambas son válidas**.

Más ejercicios en [[Ejercicios de ecuaciones racionales]]
