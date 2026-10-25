---
title: Isomorfismo de espacios vectoriales
---
Sean $S, T \leq V$ [[Subespacios complementarios|subespacios complementarios]], entonces la [[Espacio cociente|proyección canónica paralela]] a $S$ restringida a $T$, es decir
$$
\begin{align*}
\pi_{S}|_T: T &\rightarrow V/S\\
t &\rightarrow t + S
\end{align*}
$$
es un ==isomorfismo de espacios vectoriales==.

>[!example] Proposición
>$$
>\text{dim }V = \text{dim }S + \text{dim}(V/S)
>$$
>
>Al valor de $\text{dim}(V/S)$ se le llama ==codimensión== de $S$ en $V$.

>[!tip] Técnica: Encontrar bases de V/S
>Todo [[Homomorfismos|isomorfismo]] lleva una [[Base o sistema generador minimal|base]] a una base. Así basta encontrar una base $\{t_1, \dots , t_n\}$ de $T$, complementario de $S$, para tener una base de $V/S$ que en este caso será $\{t_1 + S, \dots , t_n + S\}$.