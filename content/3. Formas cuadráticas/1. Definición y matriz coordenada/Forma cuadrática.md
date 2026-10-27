---
title: Forma cuadrática
---
Sea $V$ un $\mathbb{F}$-[[Espacio vectorial|espacio vectorial]] y $\mathcal{B}$ una [[Base de cadenas de bloques|base]] de $V$. Una aplicación
$$
\begin{split}
Q\colon V&\to\mathbb{F}\\
v&\mapsto Q(v)=\sum_{i=1}^n\sum_{j=1}^n\alpha_{ij}x_ix_j
\end{split},
$$
donde las [[Coordenadas en una base|coordenadas]] son $[v]_\mathcal{B}=(x_1,\dots,x_n)$, se dice ==forma cuadrática==.

>[!bug] Test
>Siempre que trabajemos con formas cuadráticas asumiremos que en el cuerpo $\mathbb{F}$ se cumple que $1+1\neq 0$, es decir, que la característica del [[Cuerpo|cuerpo]] no es dos.

>[!warning] Observación
>Podemos suponer que $\alpha_{ij}=\alpha_{ji}$ puesto que también se cumple
>$$
>Q(v)=\sum_{i=1}^n\sum_{j=1}^n\dfrac{\alpha_{ij}+\alpha_{ji}}{2}x_ix_j,
>$$
>luego podemos cambiar $\alpha_{ij}$ y $\alpha_{ji}$ por $\frac{\alpha_{ij}+\alpha_{ji}}{2}$.

Podemos expresar el valor de $Q(v)$ como un producto de matrices de la siguiente forma
$$
Q(v)=\sum_{i=1}^n\sum_{j=1}^n\alpha_{ij}x_ix_j=(x_1,\dots,x_n)\begin{pmatrix}
\alpha_{11}&\cdots&\alpha_{1n}\\
\vdots&\ddots&\vdots\\
\alpha_{n1}&\cdots&\alpha_{nn}
\end{pmatrix}\begin{pmatrix}
x_1\\
\vdots\\
x_n
\end{pmatrix}.
$$
Esta es la ==expresión coordenada== de $Q$ en base $\mathcal{B}$. Se suele escribir
$$
Q(v)=X^tAX,
$$
donde $X^t=[v]_{\mathcal{B}}=(x_1,\dots,x_n)$. Cuando la matriz $A$ es simétrica, es decir, $\alpha_{ij}=\alpha_{ji}$ llamamos a dicha matriz ==matriz de Gram== de $Q$ y lo denotaremos como
$$
A=[Q]_\mathcal{B}.
$$