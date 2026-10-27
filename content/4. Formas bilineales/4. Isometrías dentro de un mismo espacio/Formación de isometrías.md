---
title: Isometrías
---
Dado $(V,f)$ un [[Forma bilineal|espacio vectorial ortogonal]] y $v\in V$ un [[Ortogonalidad|vector anisotŕopico]], $f(v,v)\neq 0$. Definimos
$$
\begin{split}
S_v\colon V&\to V\\
w&\mapsto w-2\dfrac{f(v,w)}{f(v,v)}v.
\end{split}
$$
Esta aplicación se llama ==simetría== determinada por $v$.

>[!example] Proposición
>- $S_v$ es una [[Aplicación lineal|aplicación lineal]] y $S_v^2=\text{Id}$.
>- $S_v$ es una [[Isometrías|isometría]].
>- $S_v(v)=-v$ y $S_v(w)=w$ para todo $w$ [[Ortogonalidad|ortogonal]] a $v$.

>[!quote] Teorema
>Sea $(V,f)$ un espacio vectorial ortogonal y [[Ortogonalidad|regular]]. Se tiene que toda isometría dentro del mismo espacio es una composición de simetrías.

