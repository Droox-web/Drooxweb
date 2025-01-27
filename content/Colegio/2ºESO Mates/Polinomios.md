Un polinomio en matemáticas es un conjunto de letras y números relacionados entre sí a través de distintas operaciones aritméticas. Es un conjunto de monomios (elemento fundamental del álgebra) relacionados entre sí por sumas o restas.

## Monomios

Un monomio es una expresión algebraica que tiene letras y números relacionados entre sí únicamente mediante multiplicaciones.
$$M(x)=2x^3$$
Este monomio tiene 4 elementos multiplicados entre sí: $M(x)=2\cdot x \cdot x \cdot x$

- Al número (en este caso el $2$) se le llama *coeficiente*.
- A las letras, en este caso $x^3$ se le llama *parte literal*.

Puede hallarse el valor de un monomio si se conoce el valor de las variables. Los monomios (y polinomios) son especialmente útiles para tener **expresiones generales o fórmulas** que nos sirvan para múltiples casos. Por ejemplo, el área ($A$) de un rectángulo de base $b$ y altura $a$ puede ser descrita mediante el monomio:
$$A(a,b)=ab$$
De forma que si tratamos con un rectángulo de base 2 y altura 8 tendría un área $A(8,2)=8\cdot 2=16$ mientras que si tratásemos con otro de base 3 y altura 2 el área sería $A(2,3)=2\cdot 3 =6$.

### Operaciones con monomios

Para operar monomios es fundamental tener en cuenta que tanto coeficiente como parte literal son números, aunque la parte literal tiene la particularidad de ser un número no conocido aun.

De este modo, mientras que con coeficientes podremos operar sin problema, las partes literales tendrán que tratarse como potencias y seguirán las mismas propiedades de éstas.
#### Sumas y restas de monomios

Los monomios pueden sumarse o restarse cuando tienen la misma parte literal. En este caso, el resultado tiene la misma parte literal pero su coeficiente es la suma (o resta) de los coeficientes.

$$2x^2+4x^2=6x^2$$
$$\cancel{3x^4-2x^2}$$

Ejercicios en [[2eso-Ejercicios de sumas y restas de polinomios]]
#### Multiplicaciones de monomios

Los monomios pueden multiplicarse multiplicando los coeficientes y las partes literales por separado. Al ser números no conocidos, la parte literal se opera utilizando las propiedades de las potencias.

$$2x^2\cdot 5x^5=(2\cdot 5) \cdot (x^2\cdot x^5)=10x^7$$

[[3eso-Ejercicios de multiplicaciones y divisiones de monomios]]
#### Divisiones de monomios

Los monomios pueden dividirse dividiendo los coeficientes y las partes literales por separado. Al ser números no conocidos, la parte literal se opera utilizando las propiedades de las potencias. $$10x^5:2x^3=(10:2) \cdot (x^5:x^3)=5x^2$$
Para practicar visitar [[2eso-Ejercicios de operaciones con monomios]]
## Polinomios

Un polinomio puede denotarse como $P(x)$ donde $x$ indica la variable de la que depende el polinomio.

Ejemplo:

$$P(x)=2x^2-3$$
$$Q(y,z)=2yz-z+y^3$$
$$R(x,y)=x^y-2x$$

Si conocemos el valor de $x$, (por ejemplo si $x=2$) podemos hallar el valor del polinomio sin más que realizar la aritmética.

$$P(2)=2\cdot 2^2-3=8-3=5$$
### Operaciones con polinomios

Las operaciones entre polinomios que vamos a ver nos permiten operar con estas expresiones sin necesidad de conoces los valores de las incógnitas. Esto nos ayudará a simplificar y compactar expresiones complejas para que la fórmula final sea lo más práctica posible.
#### Suma y resta de polinomios

La suma y resta de polinomios solo puede llevarse a cabo cuando estos tienen la misma parte literal. En este caso, sumamos o restamos **únicamente** aquellos monomios que compartan parte literal. Veamos un ejemplo:

$$P(x)=2x^2-3; \quad S(x,y)=x^2-y^2+7$$
Como únicamente comparten parte literal los términos con $x^2$ y los términos de grado $0$ éstos serán los únicos que podremos restar entre sí (el término con $y^2$ queda sin operar)
$$P(x)-S(x,y)=(2x^2-3)-(x^2-y^2+7)=(2x^2-x^2)+(-3-7)+y^2$$
$$P(x)-S(x,y)=x^2-10+y^2$$

Para practicar visitar: [[2eso-Ejercicios de sumas y restas de polinomios]]
#### División de polinomios

La división de polinomios puede hacerse mediante un método similar al de la caja que se usa en las divisiones de números habituales. Sin embargo, por su dificultad a la hora de escribirla en el editor de texto en el que estoy haciendo estos apuntes, voy a dejar un vídeo explicativo de la misma [aquí](https://www.youtube.com/watch?v=f2Gzfua7z9s).

Existe un caso especial de división de polinomios, en el que el divisor es de la forma $(x\pm a)$ donde $a\in \mathcal{R}$. En este caso, la división puede llevarse a cabo mediante Ruffini.  #ToDo

#### Multiplicación de polinomios

La multiplicación de polinomios se realiza utilizando la propiedad distributiva, que consiste en multiplicar cada término de un polinomio por cada término del otro polinomio.

- Utiliza la propiedad distributiva para multiplicar cada término de un polinomio por cada término del otro polinomio. Por ejemplo, para multiplicar los polinomios:   $$ P(x) = (2x + 3) \quad \text{y} \quad Q(x) = (x^2 + x + 1) $$Se multiplica cada término de $P(x)$ por cada término de $Q(x)$:$$(2x + 3)(x^2 + x + 1)$$
   - **Multiplicando $2x$**:
     - $2x \cdot x^2 = 2x^3$
     - $2x \cdot x = 2x^2$ 
     - $2x \cdot 1 = 2x$

   - **Multiplicando 3:
     -  $3 \cdot x^2 = 3x^2$
     - $3 \cdot x = 3x$
     - $3 \cdot 1 = 3$

3. **Combina términos semejantes**: Una vez que has multiplicado todos los términos, combina los términos semejantes para simplificar el resultado. En el ejemplo anterior, sumamos los términos:  $$2x^3 + (2x^2 + 3x^2) + (2x + 3x) + 3 = 2x^3 + 5x^2 + 5x + 3$$ Veamos un ejemplo. Multiplicamos los polinomios:
$$(2x + 3)(x^2 + x + 1)$$

1. **Distribuir**:

   $$
   2x(x^2) + 2x(x) + 2x(1) + 3(x^2) + 3(x) + 3(1)
   $$

2. **Multiplicar**:

   $$
   2x^3 + 2x^2 + 2x + 3x^2 + 3x + 3
   $$

3. **Combinar términos semejantes**:

   $$
   2x^3 + (2x^2 + 3x^2) + (2x + 3x) + 3 = 2x^3 + 5x^2 + 5x + 3
	$$

Ejercicios en [[2eso-Ejercicios de multiplicación de polinomios]]

### Factorización de polinomios

La factorización de polinomios es una de las cuestiones más importantes a la hora de simplificar y operar con expresiones de este tipo. Factorizar un polinomio por una parte nos ayuda a ver sus raíces (valores de $x$ que anulan -hace que valga 0- el polinomio) y por otra nos ayuda a simplificar polinomios *siempre que tengan raíces comunes*.

Existen distintos métodos para factorizar polinomios y estos dependen del grado del mismo. La gran mayoría de polinomios no pueden factorizarse en factores sencillos y solo pueden factorizarse de forma aproximada, sin embargo, nos centraremos en factorizar aquellos que sean más asequibles.

Factorizar un polinomio $P(x)$ es escribirlo como producto de expresiones del tipo $(x\pm a)$. Por ejemplo el polinomio $x^2+5x+6$ puede factorizarse como producto de dos de éstas expresiones $$x^2+5x+6=(x+2)(x+3)$$En términos generales, un polinomio de grado #ToDo 

Ejercicios en [[3eso-Ejercicios de factorización de polinomios]]

### Fracciones algebraicas

Las fracciones algebraicas son expresiones de la forma $\frac{P(x)}{Q(x)}$ donde $P(x)$ y $Q(x)$ son polinomios.

Por ejemplo:$$\frac{x-2}{x^2-4x+4}$$es una fracción algebraica.

Las fracciones algebraicas pueden operarse entre sí siguiendo las reglas que rigen las operaciones de fracciones con la salvedad de que estas operaciones se realizan entre polinomios.

##### Simplificación de fracciones algebraicas
Para simplificar fracciones algebraicas, debemos factorizar los polinomios que la componen y comprobar si tienen alguno en común, en tal caso, dicho factor podrá ser simplificado.

Por ejemplo:$$\frac{x-2}{x^2-4x+4}$$tiene un polinomio sin factorizar en el denominador. Mediante identidades notables se tiene$$x^2-4x+4=(x-2)^2=(x-2)(x-2)$$Por lo que queda$$\frac{x-2}{(x-2)(x-2)}$$Y podemos simplificar los factores$$\frac{\cancel{x-2}}{(\cancel{x-2})(x-2)}$$Igual que haríamos en una fracción con números, simplificando factores comunes$$\frac{1}{x-2}$$
Ejercicios en [[3eso-Ejercicios de simplificación de fracciones algebraicas]]
##### Suma de fracciones algebraicas
Para sumar fracciones algebraicas, al igual que para sumar fracciones usuales, necesitamos que estas tengan denominador común (pues no se puede sumar o restar fracciones de distinto denominador). 

Para ello, haremos el mínimo común múltiplo de los denominadores y con ello buscaremos fracciones equivalentes para poder realizar la operación.

En general$$\frac{P(x)}{Q(x)}+\frac{R(x)}{S(x)}=\frac{P'(x)}{T(x)}+\frac{R'(x)}{T(x)}=\frac{P'(x)+R'(x)}{T(x)}$$Donde $T(x)$ es el $m.c.m\left[Q(x),S(x)\right]$. $P'(x)$ y $R'(x)$ son los polinomios que hacen que las fracciones $\frac{P(x)}{Q(x)}, \frac{R(x)}{S(x)}$ y $\frac{P'(x)}{T(x)}, \frac{R'(x)}{T(x)}$ sean equivalentes.

Veamos un ejemplo:$$\frac{1}{x}+\frac{2x}{x-1}$$Buscamos el $m.c.m. (x, x-1)$ que al ser factores distintos (ver factorización más arriba) es directamente su producto$$m.c.m. (x, x-1)=x\cdot (x-1)$$Por lo que las fracciones equivalentes serán$$\frac{x-1}{x\cdot (x-1)}+\frac{2x^2}{x\cdot (x-1)}$$Pues el primer numerador se multiplica por el $x-1$ que le faltaba al denominador y el segundo numerador se multiplica por la $x$ que le faltaba al denominador.

Ahora podemos sumar numeradores$$\frac{x-1+2x^2}{x\cdot (x-1)}=\frac{2x^2+x-1}{x\cdot (x-1)}$$Y finalmente, podríamos intentar simplificar la fracción. Para ello vemos si el numerador puede factorizarse en $x$ que ***no puede si no se puede sacar factor común*** o en $(x-1)$ ***usando el teorema del resto***$$\left .2x^2+x-1\right|_{x=1}=2+1-1=2\neq 0$$No es divisible, por lo que no se puede factorizar y por ende no se puede simplificar. Operamos el denominador $$x(x-1)=x^2-x$$y queda finalmente que la suma es $$\frac{1}{x}+\frac{2x}{x-1}=\frac{2x^2+x-1}{x^2-x}$$Ejercicios en [[3eso-Ejercicios de sumas de fracciones algebraicas]]

Más ejercicios en [[2eso-Ejercicios de sumas de fracciones algebraicas]]

#### Multiplicación de fracciones algebraicas

Para multiplicar fracciones algebraicas, debemos recordar que se multiplican fracciones en línea. De esta forma $$\frac{P(x)}{Q(x)}\cdot \frac{R(x)}{S(x)}=\frac{P(x)\cdot R(x)}{Q(x)\cdot S(x)}$$
Por ejemplo, $$\frac{x^2-1}{x^2+3}\cdot \frac{x-2}{x+2}=\frac{(x^2-1)(x-2)}{(x^2+3)(x+2)}$$
Si efectuamos estas multiplicaciones
- $(x^2-1)(x-2)=x^3-2x^2-x+2$
- $(x^2+3)(x+2)=x^3+2x^2+3x+6$

Queda $$\frac{x^3-2x^2-x+2}{x^3+2x^2+3x+6}$$
En ocasiones, el resultado podrá simplificarse. Esto ocurre cuando los polinomios resultantes tienen algún [[3eso-Ejercicios de factorización de polinomios]]. 

[[3eso-Ejercicios de multiplicación y división de fracciones algebraicas]]


#ToDo 