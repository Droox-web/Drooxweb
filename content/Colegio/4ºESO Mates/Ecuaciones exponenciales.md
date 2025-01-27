Las [[Ecuaciones|ecuaciones]] exponenciales son aquellas ecuaciones en las cuales la incógnita está en el exponente de una potencia. El caso más sencillo es el de ecuaciones de la forma $$a^{f(x)}=b$$Dónde $a$ y $b$ son números reales y $f(x)$ una función que depende la variable $x$.

---

#### Veamos un ejemplo, 
$$2^x=17$$Es una ecuación exponencial de esta forma, para resolverla se aplica la operación inversa a la exponenciación, que es el logaritmo $$log_{2}(2^x)=log_2(17)$$Aplicando la propiedad c) de los [[Logaritmos|logaritmos]] ($log_a(a^n)=n$) a la parte izquierda de la ecuación queda $$x=log_217\simeq 4,09$$

---
Las ecuaciones exponenciales de la forma $$a^{n\cdot f(x)}+a^{f(x)}+b=0$$También podemos resolverlas, en este caso mediante el cambio de variable $f(x)=t$. Aunque nos centraremos en casos simples en los que $f(x)=x$, este método puede servirnos para cualquier $f(x)$.

---

#### Veamos un ejemplo,
$$2^{2x}+2^x-2=0$$Es una ecuación que bajo el cambio de variable $2^x=t$ queda $$t^2 +t -2=0$$Dónde hemos usado que $2^x=t$ y que $2^{2x}=(2^x)^2=t^2$. 

Tras este cambio, resolvemos la ecuación de segundo grado $t^2+t-2=0$ por el método preferido, en mi caso por **factorización** del polinomio $t^2+t-2=(t+2)(t-1)$ que deja $$(t+2)(t-1)=0$$
Cuyas soluciones son $t=-2$ y $t=1$. Deshacemos ahora el cambio de variable $$2^x=-2$$Que se resuelve aplicando logaritmos $$x=log_2(-2)\rightarrow \cancel{\exists} \text{sol}$$Y se obtiene que no tiene solución, ya que el logaritmo no está definido para números negativos.

Deshacemos ahora el cambio de variable para la otra solución $$2^x=1$$Que se resuelve aplicando logaritmos $$x=log_2{1}=0$$Y se obtiene que la solución es $x=0$, única solución en este caso de la ecuación.

Para más ejercicios ver [[Ejercicios de ecuaciones exponenciales]]
