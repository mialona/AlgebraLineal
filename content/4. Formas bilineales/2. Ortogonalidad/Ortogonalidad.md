---
title: Ortogonalidad
---
Sea $f\colon V\times V\to \mathbb{F}$ una [[Forma bilineal]] simétrica o antisimétrica y $u,v,v_i\in V$:
- Dos vectores $u,v$ se dicen ==ortogonales==, y se denota $u\perp v$, si $f(u,v)=0$.
- $u$ se dice ==isótropo== si $f(u,u)=0$. En otro caso se dice ==anisótropo==.
- Un conjunto de vectores $\{v_1,\dots,v_r\}$ se dice ==ortogonal== si $f(v_i,v_j)=0$ siempre que $i\neq j$. Una [[Base o sistema generador minimal|base]] formada por vectores ortogonales se dice ==base ortogonal==.
Si además $S\leq V$:
- El ==subespacio ortogonal== de $S$ se define como
$$
S^\perp=\{u\in V : f(u,s)=0\, s\in S\}.
$$
- El suespacio ortogonal al total $V$, $V^\perp$, se llama ==radical== de $f$.
- $S$ se dice ==regular== si $S\cap S^{\perp}=\{0\}$.
- $S$ es un ==subespacio isotrópico== si contiene algún vector isótropo.
- $S$ es ==totalmente isotrópico== si todos sus vectores son isótropos, es decir $S\leq S^\perp$.

>[!warning] Observación
>Observa que si $f$ no es ni simétrica ni antisimétrica no tiene sentido hablar de ortogonalidad, puesto que puede ocurrir que $f(u,v)=0$ pero $f(v,u)\neq 0$.

>[!tip] Técnica: Calcular subespacios ortogonales
>Para calcular el subespacio ortogonal a $S$ basta calcular los vectores que son ortogonales a un [[Sistema generador|conjunto generador]], es decir, si $S=\text{Gen}\langle s_1,\dots,s_k\rangle$ entonces
>$$
>S^\perp=\{v\in V : f(v,s_1)=\cdots=f(v,s_k)=0\}.
>$$ 

>[!example] Proposición
>Sea $f\colon V\times V\to\mathbb{F}$ una forma bilineal simétrica o antisimétrica, $\mathcal{B}=\{v_1,\dots,v_n\}$ una base de $V$ y $M$ la [[Matriz de Gram de una forma bilineal|matriz coordenada]] de $f$ respecto de la base $\mathcal{B}$. Se tiene que $v\in V^\perp$ si y solamente si
>$$
>M\begin{pmatrix}x_1\\\vdots\\x_n\end{pmatrix}=0
>$$
>donde $[v]_\mathcal{B}=(x_1,\dots,x_n)$ son las [[Coordenadas en una base|coordenadas]] de $v$ en la base $\mathcal{B}$.

>[!quote] Teorema: Fórmula de la dimensión
>Sea $f\colon V\times V\to\mathbb{F}$ una forma bilineal simétrica o antisimétrica y $S$ un [[Subespacio vectorial|subespacio]] de $V$. Se tiene que
>$$
>\text{dim}\,S\text{dim}\,S^\perp=\text{dim}\,V+\text{dim}(S\cap V^\perp).
>$$
>En particular, si $S$ es un subespacio regular entonces $V=S\oplus S^\perp$.

>[!warning] Observación
>Se escribe $S\perp T$ la [[Suma directa|suma directa]] $S\oplus T$ cuando $f(s,t)=0$ para $s\in S$ y $t\in T$.