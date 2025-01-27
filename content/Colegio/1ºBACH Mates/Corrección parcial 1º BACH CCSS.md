Relacionado con [[Anualidades de capitalización]],[[Logaritmos]],[[Raíces]],[[Ecuaciones]]
1. Simplifica las raíces al máximo.

	a) $$\frac{\left( \sqrt[4]{3^4}\right)^2\cdot \sqrt[4]{\sqrt[5]{3^{25}}}}{\left [ \sqrt[9]{\sqrt[5]{3}}\right]^{15}\cdot 3}=\frac{3^2\cdot \sqrt[20]{3^{25}}}{\sqrt[45]{3^{15}}\cdot 3}=\frac{3^3\sqrt[20]{3^5}}{3^4}=\frac{\sqrt[4]{3}}{3}$$

	b) $$\frac{\left( \sqrt[4]{5^2}\right)^4\cdot \sqrt[4]{\sqrt[5]{5^{20}}}}{25\cdot\left  [ \sqrt[3]{\sqrt[5]{5}}\right]^{15}}=\frac{5^2\cdot \sqrt[20]{5^{20}}}{25\cdot\sqrt[15]{5^{15}}}=\frac{5^3}{5^3}=1$$

2. Realiza las sumas de radicales.

	a) $\sqrt 8 -\sqrt{50}- \frac12\sqrt{98}=2\sqrt2-5\sqrt2-\frac72\sqrt2=-\frac{13}{2}\sqrt 2$
	b) $\frac12\sqrt 3-\sqrt{12}-\frac34\sqrt75=\frac12\sqrt 3-2\sqrt 3-\frac{15}4\sqrt3 =-\frac{21}4\sqrt3$

3. Realiza las sumas de logaritmos.

	a) $log _39+log_3\sqrt{81}-log_3\sqrt[3]{27^2}=log_33^2-log_33^2-log_33^{6/3}=log_33^2=2$
	
	b) $log_216-log_232+log_2\left( 2^3\right)^2-log_2\sqrt 4=$
	$=log_22^4-log_22^5+log_22^6-log_22=4-5+6-1=4$

4. Resuelve las ecuaciones.

	a) $$\frac{x}{x+2}+\frac{6x+4}{x^2-4}=0$$
	Dado que el mcm es $x^2-4$ y este es $(x+2)(x-2)$ tenemos $$x(x-2)+6x+4=0$$ Operamos $$x^2-2x+6x+4=0$$	$$x^2+4x+4=0$$
	Cuyas soluciones son $x=-2$ doble. **No válida** al anular el denominador.

	b) $$\sqrt{x+2}-3=x+4$$
	Separamos $$\sqrt{x+2}=x+7$$ Elevamos al cuadrado $$x+2=x^2+14x+49$$ Resolvemos la ecuación de segundo grado resultante $x^2+13x+47=0$ con la fórmula: **no tiene solución real**. 

	c)$$4^x-2^{x+3}+9=0$$Operamos para prepararla para el cambio de variable $$\left(2^{x}\right)^2-2^3\cdot 2^x+9=0$$ $$\left(2^{x}\right)^2-8\cdot 2^x+9=0$$
	Con el cambio de variable $2^x=t$ queda $$t^2-8t+9=0$$ Resolvemos y se tiene $x\simeq 1.35$ y $x\simeq 6.64$. Deshacemos el cambio de variable: $$2^{x}=1.35 \rightarrow x=log_2(1.35)\simeq0.43$$
	$$2^x=6.64\rightarrow x=log_2(6.64)\simeq 2.73$$
	Que **no hace falta comprobar**.

	d)$$log_2(x^2+x)-log_23+log_22=2$$ Juntamos en un único logaritmo $$log_2\left( \frac{2(x^2+x)}{3}\right)=2$$Aplicamos el paso a potencia $$2^2= \frac{2(x^2+x)}{3}$$ Operamos $$12=2x^2+2x$$ $$2x^2+2x-12=0$$ Resolvemos con la fórmula $x=-3, \quad x=2$ . En este caso ambas valen pues dan logaritmos positivos.

5. Suponiendo que quisiera ahorrar para comprarme una casa de 250.000€ mediante un producto del tipo anualidad de capitalización calcula:

a) La mensualidad que tendría que aportar si el producto tiene un rédito del 6% anual y quiero comprarla dentro de 15 años. (1 punto)

>[!Solución]
>La expresión para anualidad de capitalización es $$C=\frac{A[(1+r)^{t+1}-(1+r)]}{r}$$ De donde despejamos A para obtener $$A=\frac{Cr}{[(1+r)^{t+1}-(1+r)]}$$ Recordemos utilizar los réditos mensuales y el tiempo en meses. $$M=\frac{250000\cdot 0.005}{[(1+0.005)^{180+1}-(1+0.005)]}=855, 36$$ Debemos aportar 855, 36€/mes.

b) El tiempo que me llevaría si mi capacidad de ahorro es de 250€/mes con el mismo rédito del apartado anterior. (1 punto)

>[! Solución]
>En este caso queremos hallar el tiempo, la expresión es $$t=\log_{1+r}\left(\frac{C\cdot r}{A}+1+r\right)-1$$ Colocando rédito y tiempo en meses se tiene $$t=\log_{1+0.005}\left(\frac{250000\cdot 0.005}{250}+1+0.005\right)-1=358,41$$ Es decir 358 meses y pico, lo que son 29,87 años (casi 30 años).








