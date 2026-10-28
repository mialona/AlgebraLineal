---
title: Subespacios ortogonales
---
Sea $(V,\langle\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio euclídeo o unitario]]. Si $S\leq V$ es un [[Subespacio vectorial|subespacio]], su ==subespacio ortogonal== de define como
$$
S^\perp:=\{v\in V : \langle v,s\rangle=0\,\forall s\in S\}.
$$
Una suma $S_1+\cdots+S_2$ se dice ==suma ortogonal== si los subespacios $S_1,\dots,S_m$ son ortogonales dos a dos. Se denota por
$$
S_1\perp\cdots\perp S_m.
$$
>[!warning] Observación
>Si $S+T$ es suma ortogonal entonces es [[Suma directa|suma directa]]
>$$
>S\perp T\Rightarrow S\oplus T.
>$$

>[!example] Proposición
>Dado $S$ un subpespacio de $V$, entonces $S$ y $S^\perp$ con [[Subespacios complementarios|complementarios]]
>$$
>V=S\perp S^\perp.
>$$

Esta descomposición nos permite definir la [[Proyecciones paralelas|proyección]] sobre $S$ paralela a $S^\perp$. Si $V=s+s'$ con $s\in S$ y $s'\in S^\perp$ entonces
$$
\begin{split}
p_S\colon V&\to S\\
v=s+s'&\mapsto s
\end{split}
$$
A esta proyección se le llama ==proyección ortogonal== de $V$ sobre $S$.

>[!example] Proposición. Proyección ortogonal
>- Si $\{v_1,\dots,v_m\}$ es una [[Ortogonalidad en productos escalares|base ortonormada]] de $S$ entonces
>$$
>p_S(v)=\langle v,v_1\rangle v_1+\cdots+\langle v,v_m\rangle v_m.
>$$
>- $\lVert v-w\rVert>\lVert v-p_S(v)\rVert$ para todo $w\in S$ con $w\neq p_S(v)$.

>[!warning] Observación
>La última desigualdad nos dice que la proyección es el vector más "cercano" a $v$ dentro de los vectores de $S$. Además, podemos entender la distancia de $v$ a $S$ como ese mínimo $\lVert v-p_S(v)\rVert$.

