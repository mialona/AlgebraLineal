---
title: No unicidad del polinomio mínimo de vectores dentro de un invariante
---
Dentro del [[Subespacio invariante|invariante]] $\mathbb{F}[x](f)(v)$ no todos los vectores tiene el mismo [[Polinomio mínimo|polinomio mínimo]].

>[!example] Proposición
>Sea $v \in V$ y $p(x) \in \mathbb{F}[x]$ un polinomio cualquiera se tiene que
>$$
>m_{p(f)(v)}(x) = \frac{m_v(x)}{\text{mcd}(m_v(x), p(x))} = \frac{\text{mcm}(m_v(x), p(x))}{p(x)}.
>$$

>[!success] Corolario
>Si $m_v(x) = q_i(x)^j$, entonces en $\mathbb{F}[x](f)(v)$ habrá vectores cuyo polinomio mínimo sea $q_i(x)^k$ para todo $1 \leq k \leq j$. En concreto
>$$
>m_{q_i(f)^k(v)}(x) = q_i(x)^{j-k}.
>$$
