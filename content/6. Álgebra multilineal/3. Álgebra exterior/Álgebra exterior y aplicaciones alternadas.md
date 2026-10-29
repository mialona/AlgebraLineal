---
title: Álgebra exterior y aplicaciones alternadas
---
Sean $V$ y $W$ dos $\mathbb{F}$-[[Espacio vectorial|espacios vectoriales]]. Una [[Aplicación multilineal|aplicación multilineal]] $f\colon V\times\cdots\times V\to W$ se dice ==alternada== si al evaluarse en dos componentes repetidas da cero, es decir 
$$
f(v_1,\dots,v_n)=0
$$
si $v_i=v_j$ para algún $i\neq j$.

>[!warning] Observación
>Este es un concepto que implica antisimetría. Así, en bilineal
>$$
>\begin{split}
>f(v,v)=0&\Rightarrow f(v_1+v_2,v_1+v_2)=0\\
>&\Rightarrow f(v_1,v_1)+f(v_1,v_2)+f(v_2,v_1)+f(v_2,v_2)=0\\
>&\Rightarrow f(v_1,v_2)=-f(v_2,v-1).
>\end{split}
>$$
>Y, si estamos en un [[Cuerpo|cuerpo]] de característica distinta de dos, tenemos el recíproco. Ya que $f(v,v)=-f(v,v)$, luego $2f(v,v)=0$ y $f(v,v)=0$.

Definimos ahora el ==álgebra exterior== $\Lambda^n V=V\wedge\cdots\wedge V$ como
$$
\dfrac{V\otimes\cdots\otimes V}{\langle v_1\otimes\cdots\otimes v\otimes\cdots\otimes v\otimes\cdots\otimes v_n : v,v_k\in V\rangle}
$$
De forma análoga tendríamos el ==álgebra simétrica== $S^n V$ como
$$
\dfrac{V\otimes\cdots\otimes V}{\langle v_1\otimes\cdots\otimes v_i\otimes\cdots\otimes v_j\otimes\cdots\otimes v_n-\langle v_1\otimes\cdots\otimes v_j\otimes\cdots\otimes v_i\otimes\cdots\otimes v_n : v_k\in V\rangle}
$$
Para el álgebra exterior tenemos la aplicación alternada
$$
\begin{split}
i\colon V\times\cdots\times V&\to\Lambda^nV\\
(v_1,\dots,v_n)&\mapsto v_1\wedge\cdots\wedge v_n:=[v_1\otimes \cdots\otimes v_n].
\end{split}
$$
>[!example] Proposición. Propiedad universal
>Dada $f\colon V\times \cdots\times V\to W$ multilineal alternada, existe una única $\overline{f}\colon\Lambda^n V\to W$ [[Aplicación lineal|lineal]] tal que el siguiente diagrama conmuta
>$$
>\begin{array}{ccc}
> & & \Lambda^n V \\
> & \overset{i}{\nearrow} &  \\
>V \times \cdots \times V &  & \downarrow \bar{f}\\
>& \underset{f}{\searrow} &\\
>&& W
>\end{array}
>$$
>Y además es única salvo [[Aplicación lineal|isomorfismo]], ya que si $(X,j)$ es otro par tal que cumple el punto anterior, entonces existe $\varphi\colon\Lambda^n V\to x$ isomorfismos tal que $\varphi\circ i=j$.

>[!example] Proposición. Propiedades
>1. Si $f\colon V\times \cdots\times V\to W$ es multilineal alternada y $\sigma\in S_n$ una [[Grupo simétrico|permutación]] entonces
>$$
>f(v_{\sigma(1)},\dots, v_{\sigma(n)})=\text{sig}(\sigma)\cdot f(v_1,\dots,v_n),
>$$
>donde $\text{sig}(\sigma)$ es la [[Grupo simétrico|signatura]] de $\sigma$.
>2. $v_{\sigma(1)}\wedge\cdots\wedge v_{\sigma(n)}=\text{sig}(\sigma)\cdot v_1\wedge\cdots\wedge v_n$.
>3. $v_1\wedge\cdots\wedge(\alpha v_i+\beta v_i')\wedge\cdots\wedge v_n=\alpha\cdot(v_1\wedge\cdots\wedge v_i\wedge\cdots\wedge v_n)+\beta\cdot(v_1\wedge\cdots\wedge v'_i\wedge\cdots\wedge v_n)$.

>[!quote] Teorema. Base de $\Lambda^n V$
>Sea $\{e_1,\dots,e_n\}$ una [[Base o sistema generador minimal|base]] de $V$. Se tiene que:
>1. Si $k>\text{dim}\, V$ entonces $\Lambda^k V=0$.
>2. Si $k\leq\text{dim}\, V$ entonces
>$$
>\{e_{i_i}\wedge\cdots\wedge e_{i_k} : 1\leq i_1<\cdots< i_k\leq n\}
>$$
>es base de $\Lambda^k V$. En particular,
>$$
>\text{dim}\,\Lambda^k V=\binom{n}{k}=\dfrac{n!}{k!(n-k)!}.
>$$

Trabajando con álgebras exteriores tenemos dos aplicaciones, no nulas, importantes
$$
\begin{split}
G\colon\Lambda^k V\times\Lambda^{n-k}V&\to\mathbb{F}\\
(v_1\wedge\cdots\wedge v_k,v_{k+1}\wedge\cdots\wedge v_n)&\mapsto\det(v_1,\dots,v_n),
\end{split}
$$
$$
\begin{split}
H\colon\Lambda^k V\times\Lambda^{k}(V^*)&\to\mathbb{F}\\
(v_1\wedge\cdots\wedge v_k,\varphi_1\wedge\cdots\wedge \varphi_n)&\mapsto\det(\varphi_i(v_j)).
\end{split}
$$
Como $\text{dim}\,\Lambda^k V=\text{dim}\,\Lambda^{n-k} V=\text{dim}\,\Lambda^k (V^*)=\text{dim}\,(\Lambda^k V)^*$ obtenemos isomorfismos
$$
\begin{split}
\varphi_G\colon\Lambda^{n-k}V&\to(\Lambda^k V)^*\\
v_{k+1}\wedge\cdots\wedge v_n&\mapsto \varphi_G(v_{k+1}\wedge\cdot\wedge v_n)\colon v_1\wedge\cdots\wedge v_k\mapsto G(v_1\wedge\cdots\wedge v_k,v_{k+1}\wedge\cdots\wedge v_n),
\end{split}
$$
$$
\begin{split}
\varphi_H\colon\Lambda^{k}(V^*)&\to(\Lambda^k V)^*\\
\varphi_{1}\wedge\cdots\wedge v\varphi_k&\mapsto \varphi_G(\varphi_{1}\wedge\cdot\wedge \varphi_k)\colon v_1\wedge\cdots\wedge v_k\mapsto H(v_1\wedge\cdots\wedge v_k,\varphi_{1}\wedge\cdots\wedge \varphi_k),
\end{split}
$$

>[!example] Proposición
>Las aplicaciones $G$ y $H$ anteriores inducen isomorfismos
>$$
>\Lambda^{n-k}V\cong (\Lambda^k V)^*\cong\Lambda^k(V^*).
>$$

