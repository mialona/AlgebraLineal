---
title: Forma bilineal
---
Dados $V$ y $W$ dos [[Espacio vectorial|espacios vectoriales]] sobre un [[Cuerpo|cuerpo]] $\mathbb{F}$, una aplicación $f\colon V\times W\to\mathbb{F}$ se dice ==forma bilineal== si para cualquier $u,v\in V$, $w,z\in W$ y $\alpha,\beta\in\mathbb{F}$ se cumplen las siguientes condiciones
- $f(\alpha u+\beta v,w)=\alpha f(u,w)+\beta(v,w)$,
- $f(u,\alpha w+\beta z)=\alpha f(u,w)+\beta f(u,z)$.
Estas condiciones equivalen a comprobar que la aplicación es [[Aplicación lineal|lineal]] en cada una de sus componentes.

Una forma bilineal $f\colon V\times V\to\mathbb{F}$
- es ==simétrica== si $f(u,v)=f(v,u)$, y
- es ==antisimétrica== $f(u,v)=-f(v,u)$.
El par $(V,f)$ se dice ==espacio vectorial ortogonal== o ==espacio métrico con geometría ortogonal== si $f$ es simétrica, y, ==espacio vectorial simpléctico== o ==espacio métrico con geometría simpléctica== si $f$ es antisimétrica.

> [!info] Ejemplo. Producto escalar usual en $\mathbb{R}^n$
> Tomando $V=W=\mathbb{R}^n$ y $\mathbb{F}=\mathbb{R}$ encontramos el ==producto escalar usual== de $\mathbb{R}^n$
> $$
> (x_1,\dots,x_n)\bullet (y_1,\dots,y_n)=x_1y_1+\cdots+x_ny_n.
> $$

> [!info] Ejemplo. Espacio vectorial simpléctico $(\mathbb{F}^3,f)$
> Sea $f\colon\mathbb{F}^3\times\mathbb{F}^3\to\mathbb{F}$ la forma bilineal antisimétrica dada por
> $$
> f((x_1,x_2,x_3),(y_1,y_2,y_3))=x_1y_2-x_2y_1+x_2y_3-x_3y_2.
> $$

> [!info] Ejemplo. Espacio de Minkowski
> En el ==espacio de Minkowski== $M_4=(\mathbb{R}^4,f)$ la forma bilineal $f$ aparece definida sobre la [[Base canónica|base canónica]] $\{e_1,e_2,e_3,e_4\}$ como 
> $$
> f(e_1,e_1)=f(e_2,e_2)=f(e_3,e_3)=1=-f(e_4,e_4)
> $$
> y $f(e_i,e_j)=0$ cuando $i\neq j$. Así, por linealidad
> $$
> f(x_1e_1+x_2e_2+x_3e_3+x_4e_4,y_1e_1+y_2e_2+y_3e_3+y_4e_4)=\sum_{i=1}^4\sum_{j=1}^4x_if(e_i,e_j)y_j=x_1y_1+x_2y_2+x_3y_3-x_4y_4.
> $$