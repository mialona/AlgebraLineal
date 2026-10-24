---
title: Suma directa
---
Sean $S_1,\dots,S_n\leq V$. Se dice que la [[Suma de subespacios|suma]] $S_1+\cdots+S_n$ es una ==suma directa== y se denota como $S_1\oplus\cdots\oplus S_n$ si las [[Proyecciones paralelas|proyecciones]] son únicas, es decir, si
$$
s_1+\cdots+s_n=s_1'+\cdots+s_n'
$$
con $s_i,s_i'\in S_i$ implica que $s_i=s_i'$ para todo $i=1,\dots, n$.

>[!tip] Técnica: Comprobar si una suma es directa
>Dados $S_1,\dots,S_n\leq V$, se tiene que la suma $S_1+\cdots+S_n$ es directa si y solo si 
>$$
>0=s_1+\cdots+s_n
>$$
>con $s_i\in S_i$, tiene por única solución (proyección) $s_i=0$.

>[!example] Proposición
>$S,T\leq V$ son [[Subespacios complementarios|complementarios]] si y solo si $V=S\oplus T$.

>[!quote] Teorema
>Sean $S_1,\dots,S_n\leq V$ y $\mathcal{B}_i$ [[Base o sistema generador minimal|bases]] de $S_i$. Son equivalentes:
>1. $V=S_1\oplus\cdots\oplus S_n$,
>2. $\mathcal{B}_1,\dots,\mathcal{B}_n$ son disjuntas y $\mathcal{B}_1\cup\cdots\cup\mathcal{B}_n$ es una base de $V$.
>
>En particular, $\text{dim}(S_1\oplus\cdots\oplus S_n)=\text{dim}\, S_1+\cdots+\text{dim}\, S_n$.