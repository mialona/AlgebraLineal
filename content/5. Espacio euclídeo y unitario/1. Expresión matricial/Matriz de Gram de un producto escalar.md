---
title: Matriz de Gram de un producto escalar
---
Dado un [[Producto escalar|producto escalar]] $\langle\cdot,\cdot\rangle\colon V\times V\to\mathbb{F}$ y una [[Base o sistema generador minimal|base]] $\mathcal{B}=\{v_1,\dots,v_n\}$ usando la [[Producto escalar|sesquilinealidad]] de la aplicación obtenemos que
$$
\langle v,w\rangle =\langle x_1v_1+\cdots+x_nv_n,y_1v_1+\cdot+y_nv_n\rangle=\sum_{i=1}^n\sum_{j=1}^nx_i\langle v_i,v_j\rangle \overline{y_j}=(x_1,\dots,x_n)\begin{pmatrix}
\langle v_1,v_1\rangle&\cdots&\langle v_1,v_n\rangle\\
\vdots&\ddots&\vdots\\
\langle v_n,v_1\rangle&\cdots&\langle v_n,v_n\rangle
\end{pmatrix}\begin{pmatrix}
\overline{y_1}\\\vdots\\ \overline{y_n}\end{pmatrix}.
$$
La matriz
$$
M=\begin{pmatrix}
\langle v_1,v_1\rangle &\cdots&\langle v_1,v_n\rangle\\
\vdots&\ddots&\vdots\\
\langle v_n,v_1\rangle&\cdots&\langle v_n,v_n\rangle
\end{pmatrix}
$$
se llama ==matriz de Gram== o ==matriz coordenada== del producto escalar respecto de la base $\mathcal{B}$. Además, si denotamos $X^t=(x_1,\dots,x_n)$ e $Y^t=(y_1,\dots,y_n)$ la expresión se puede escribir como
$$
\langle v,w\rangle=X^tM\overline{Y}.
$$
Como el producto escalar cumple que $\langle u,v\rangle=\overline{\langle v,u\rangle}$ entonces $\overline{M}^t=M$. Es decir, la matriz de Gram de un producto escalar es [[Matriz hermitiana|hermitiana]]. Al igual que con [[Forma cuadrática|formas cuadráticas]] y [[Forma bilineal|formas bilineales]] tenemos una fórmula de cambio de coordenadas para productos escalares.

>[!example] Proposición
>Si $M$ y $M'$ son matrices coordenadas de $\langle \cdot,\cdot\rangle$ respecto de las bases $\mathcal{B}$ y $\mathcal{B}'$ y $P$ es la [[Cambio de base|matriz del cambio de coordenadas]] de la base $\mathcal{B}'$ a base $\mathcal{B}$ entonces
>$$
>M'=P^tM\overline{P}.
>$$

>[!warning] Observación
>Muchas veces cambiaremos $P$ por $P^t$ para que la fórmula quede
>$$
>M'=PM\overline{P^t}=PMP^*.
>$$

