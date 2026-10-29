---
title: Movimientos y geometría
---
Dado $(V,\langle,\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio euclídeo o unitario]] con [[Norma de un vector|norma asociada]]
$$
\lVert v\rVert=\sqrt{\langle v,v\rangle}.
$$
Un ==movimiento== es una aplicación (no necesariamente [[Aplicación lineal|lineal]]) $\varphi\colon V\to V$ tal que
$$
\lVert\varphi(v)-\varphi(w)\rVert=\lVert v-w\rVert.
$$
Las [[Isometría y espacio euclídeo y unitario|isometrías]] son precisamente los movimientos que además son aplicaciones lineales. Otro ejemplo son las ==traslaciones==. Si tomamos $u\in V$ la traslación dada por $u$ es la aplicación
$$
\begin{split}
\varphi\colon V&\to V\\
v&\mapsto u+v
\end{split}
$$
Estas aplicaciones no son lineales excepto si $u=0$, por ese motivo, no tienen [[Aplicación y matriz coordenada|matrices coordenadas]]. Sin embargo, podemos modelarlas aún así mediante matrices, aumentando una dimensión. Por ejemplo, sea $\varphi$ la traslación en $\mathbb{R}^2$ dada por el vector $u=(a,b)$ entonces
$$
\varphi(x,y)=(x+a,y+b)
$$
Si consideramos la matriz
$$
A=\begin{pmatrix}
1&0&0\\
a&1&0\\
b&0&1\end{pmatrix}
$$
podemos observar que
$$
A\begin{pmatrix}1\\x\\y\end{pmatrix}=\begin{pmatrix}1\\x+a\\y+b\end{pmatrix}.
$$

Es decir, podemos encontrar el valor de $\varphi(x,y)$ si nos fijamos en las dos últimas coordenadas del vector. Algo similar ocurre en $\mathbb{R}^3$.
>[!tip] Técnica: Matrices lineales de traslaciones
>- En $(1,\mathbb{R}^2)$ la traslación por $u=(a,b)$ viene dada por la matriz $A_1$.
>- En $(1,\mathbb{R}^3)$ la traslación por $u=(a,b,c)$ viene dada por la matriz $A_2$.
>$$
>A_1=\left(\begin{array}{c|cc}
1&0&0\\\hline
a&1&0\\
b&0&1\end{array}\right),\quad A_2=\left(\begin{array}{c|ccc}
1&0&0&0\\\hline
a&1&0&0\\
b&0&1&0\\
c&0&0&1\end{array}\right).
$$

Un [[Subespacio vectorial|subespacio vectorial]] $S\leq\mathbb{R}^n$ o [[Subespacio trasladado|subespacio trasladado]] $u+S$ se llama
- ==punto== cuando $\text{dim}\, S=0,
- ==recta== cuando $\text{dim}\, S=1,
- ==plano== cuando $\text{dim}\, S=2,
- ==hiperplano== cuando $\text{dim}\, S=n-1,
El hecho de ser o no trasladado solo afecta a si pasa o no por el origen.

Un ==sistema de referencia ortonormal== es un par $(O,\mathcal{B})$ donde $O$ es un punto al que llamaremos ==origen== y $\mathcal{B}$ es una [[Ortogonalidad en productos escalares|base ortonormal]] que definirá nuestro sistema de ==ejes==.

Respecto a un sistema de referencia ortonormal un punto $P$ tendrá coordenadas $[P-O]_{\mathcal{B}}$.

Un punto $P$ se dice ==punto fijo== respecto a un movimiento $\varphi$ si $\varphi(P)=P$. En el caso de una isometría lineal los puntos fijos son [[Valor y vector propio|vectores propios]] de [[Valor y vector propio|valor propio]] $1$, pero en movimientos en general no es tan claro. Si estos puntos existen, se puede probar que el conjunto de puntos fijos es $u+S(1)$, donde $S(1)$ es el [[Valor y vector propio|subespacio fundamental]] de valor propio $1$ de la isometría lineal contenida en el movimiento. Pero también puede pasar que no haya, por ejemplo las traslaciones (salvo la dada por el vector $v=0$) no tienen ningún punto fijo.

En la asignatura de ==Geometría Afín y Euclídea== se estudiarán más a fondo este tipo de aplicaciones.