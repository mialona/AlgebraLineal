---
title: Aplicación multilineal
---
Sean $V_1,\dots,V_n,V$ una serie de $\mathbb{F}$-[[Espacio vectorial|espacios vectoriales]]. Decimos que una aplicación $f\colon V_1\times\cdots\times V_n\to V$ es ==multilineal== si
$$
\begin{split}
f(v_1,\dots,v_{i-1},\alpha v_i+\beta v_i',v_{i+1},\dots,v_n)
=&\alpha f(v_1,\dots,v_{i-1},v_i,v_{i+1},\dots,v_n)\\
+&\beta f(v_1,\dots,v_{i-1},v'_i,v_{i+1},\dots,v_n),
\end{split}
$$
para todo $\alpha,\beta\in\mathbb{F}$, $i,j\in\{1,\dots,n\}$, $v_j\in V_j$, $v_i,v_i'\in V_i$. Es decir, la aplicación es [[Aplicación lineal|lineal]] en cada componente.

>[!warning] Observación
>Las [[Aplicación lineal|aplicaciones lineales]] y [[Forma bilineal|formas bilineales]] son un caso particular de aplicaciones multilineales.

> [!info] Ejemplo. Aplicación bilineal
> La aplicación $f\colon\mathbb{R}^2\times\mathbb{R}^2\to\mathbb{R}^2$ definida como $f((x,y),(a,b))=(ax,by)$ es bilineal ya que
> $$
> \begin{split}
> f(\alpha(x_1,y_1)+\beta(x_2,y_2),(a,b))&=\alpha f((x_1,y_1),(a,b))+\beta f((x_2,y_2),(a,b)),\\
> f((x,y),\alpha(a_1,b_1)+\beta(a_2,b_2))&=\alpha f((x,y),(a_1,b_1))+\beta f((x,y),(a_2,b_2)),.
> \end{split}
> $$
> Y es simétrica porque $f((x,y),(a,b))=f((a,b),(x,y))$. Pero no es una forma bilineal, ya que el espacio de llegada no es en el [[Cuerpo|cuerpo]] $\mathbb{R}$ sino otro espacio vectorial $\mathbb{R}^2$.

> [!info] Ejemplo. Producto vectorial
> El ==producto vectorial== $\times\colon\mathbb{R}^3\times\mathbb{R}^3\to\mathbb{R}^3$ definido como
> $$
> (a,b,c)\times(x,y,z)=(bz-cy,cx-az,ay-bx),
> $$
> es una aplicación bilineal. Y es antisimétrica porque $(a,b,c)\times(x,y,z)=-(x,y,z)\times(a,b,c)$.

