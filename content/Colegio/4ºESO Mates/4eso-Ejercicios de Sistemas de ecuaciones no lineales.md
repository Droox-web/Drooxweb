Relacionado con [[Sistemas de ecuaciones no lineales]]

![[Pasted image 20241025091942.png#center]]

---

**e.** Despejamos y en la primera $y=\sqrt{x-6}-1$ y sustituimos en la segunda $$logx-log (\sqrt{x-6}-1)=1$$Aplicamos que la resta de logaritmos es la división de argumentos $$log{\frac{x}{\sqrt{x-6}+1}}=1$$Aplicando la definición de logaritmo (pasando a potencia) $$10^1=\frac{x}{\sqrt{x-6}+1}$$Pasamos al otro lado $$10\sqrt{x-6}+10=x$$Separamos y elevamos al cuadrado $$(10\sqrt{x-6})^2=(x-10)^2$$ $$100(x-6)=x^2-20x+100$$
$$100x-600=x^2-20x+100$$ $$x^2-120x+700=0$$ Resolvemos $x\simeq 6,15$ y $x\simeq 113,85$. Ambas son válidas al sustituir en $y=\sqrt{x-6}-1$ y en cada caso se obtiene $$y=\sqrt{6,15-6}-1\simeq-0.61$$
Solución 1: $(x,y)\simeq (6.15, -0.61)$
$$y=\sqrt{113.85-6}-1\simeq 9.38$$
Solución 2: $(x,y)\simeq (113.85, 9.38)$

---

**f.** Despejamos y en la primera $y=\sqrt{x-1}-2$ y sustituimos en la segunda $$logx-log (\sqrt{x-1}-2)=1$$Aplicamos que la resta de logaritmos es la división de argumentos $$log{\frac{x}{\sqrt{x-1}-2}}=1$$Aplicando la definición de logaritmo (pasando a potencia) $$10^1=\frac{x}{\sqrt{x-1}-2}$$Pasamos al otro lado $$10\sqrt{x-1}-20=x$$Separamos y elevamos al cuadrado $$(10\sqrt{x-1})^2=(x+20)^2$$ $$100(x-1)=x^2+40x+400$$
$$100x-100=x^2+40x+400$$ $$x^2-60x+500=0$$ Resolvemos $x=10$ y $x=50$. Ambas son válidas al sustituir en $y=\sqrt{x-1}-2$ y en cada caso se obtiene $$y=\sqrt{6,15-1}-2\simeq 0.27$$
Solución 1: $(x,y)\simeq (10, 0.27)$
$$y=\sqrt{50-1}-2= 5$$
Solución 2: $(x,y)\simeq (50, 5)$

---
**g.** Despejamos de la segunda $x=\frac{9+3y}{5}$ y sustituimos en la primera $$2^{\frac{9+3y}{5}+y}=32$$Factorizamos 32 $$2^{\frac{9+3y}{5}+y}=2^5$$E igualamos exponentes al ser de la misma base $$\frac{9+3y}{5}+y=5$$Resolvemos para $y$ $$9+3y+5y=25$$ $$8y=16\rightarrow y=2$$
Ahora en lo que hemos despejado $x=\frac{9+3y}{5}$ metemos $y=2$ para obtener $$x=\frac{9+6}{5}=3$$
Solución $(x,y)=(3,2)$

---
**h.** Esta es más rara. Aplicando la definición de logaritmo (pasando a potencia) en la segunda ecuación se tiene $$log_2(3^y-1)=x\rightarrow 2^x=3^y-1$$Ahora sustituimos en la primera el valor de $2^x$ $$3\cdot 2^x-2\cdot 3^y=6$$ $$3\cdot (3^y-1)-2\cdot 3^y=6$$ $$3\cdot 3^y-3-2\cdot 3^y=6$$ Operamos $3\cdot 3^y-2\cdot 3^y=3^y$ y queda $$3^y-3=6$$ $$3^y=9$$Factorizo $$3^y=3^2$$E igualamos exponentes $$y=2$$
 Sustituimos en la ecuación 2 $$log_2(3^y-1)=x$$ $$log_2(8)=x$$
 $$3=x$$
 Por tanto la solución es $$(x,y)=(3,2)$$