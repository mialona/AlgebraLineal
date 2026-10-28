---
title: Ortogonalidad en productos escalares
---
Si $(V,\langle\cdot,\cdot\rangle)$ es un [[Producto escalar|espacio con producto escalar]]. Si el espacio es [[Isometría y espacio euclídeo y unitario|euclídeo]] podemos definir el ==ángulo== entre dos vectores $u,v\in V$ como
$$
\angle(u,v)=\arccos\left(\dfrac{\langle u,v\rangle}{\lVert u\rVert\lVert v\rVert}\right).
$$
Esto está bien definido ya que la desigualdad de Cauchy-Schwarz nos garantiza que
$$
\dfrac{\langle u,v\rangle}{\lVert u\rVert\lVert v\rVert}\in[-1,1].
$$
Diremos que $u$ y $v$ son son ==ortogonales==, ==perpendiculares== si el ángulo que forman es recto, es decir, si
$$
\langle u,v\rangle=0.
$$
En este caso lo denotaremos por $u\perp v$.

Un conjunto $\{v_1,\dots,v_n\}\in V$ se dice ==ortonormal== si
$$
\langle v_i,v_j\rangle=\delta_{i,j}=\left\{\begin{split}
1\quad &\text{si }i=j\\
0\quad &\text{si }i\neq j
\end{split}\right.
$$
Si el conjunto original era una [[Base o sistema generador minimal|base]] entonces se llama ==base ortonormal== o ==base ortonormada==.

>[!warning] Observación
>La [[Matriz de Gram de un producto escalar|matriz de Gram]] del producto escalar en una base ortonormada es siempre la identidad $I_n$.

>[!abstract] Lema. Coordenadas en una base ortonormada
>Un vector $v\in V$ en una base ortonormada $\mathcal{B}=\{v_1,\dots,v_n\}$ de $V$ tiene [[Coordenadas en una base|coordenadas]]
>$$
>[v]_\mathcal{B}=(\langle v,v_1\rangle,\dots,\langle v,v_n\rangle).
>$$

>[!abstract] Lema. Cambios de base entre bases ortonormadas
>Dadas $\mathcal{B}$ y $\mathcal{B}'$ dos bases ortonormadas, la [[Cambio de base|matriz de cambio de coordenadas]] de $\mathcal{B}'$ a $\mathcal{B}$ cumple que
>$$
>P^t\overline{P}=I_n=\overline{P^t}P
>$$

Una matriz $P\in\mathcal{M}_n(\mathbb{C})$ tal que
$$
\overline{P^t}P=P^*P=I_n
$$
se llama ==matriz unitaria==. Y en este caso $P^{-1}=P*$. En caso que $P\in\mathcal{M}_n(\mathbb{R})$ y 
$$
P^tP=I_n
$$
se llamará ==matiz ortogonal== y en este caso $P^{-1}=P^t$.