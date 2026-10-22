---
title: Sistema generador
---
Diremos que un [[Conjunto de elementos|conjunto]] $\mathcal{B} = \{v_1, . . . , v_n\}$ es un ==sistema generador== de $V$ si todo $v_i \in V$ y, además, todo $v \in V$ se puede expresar como una ==combinación lineal de elementos== de $B$, es decir,
$$
v = \alpha_1 \cdot v_1 + \dots + \alpha_n \cdot v_n
$$
 con $\alpha_i \in \mathbb{F}$, es siempre un [[Sistema de ecuaciones lineales|sistema compatible]]. Esto se denota como $V = Gen⟨v_1, . . . , v_n⟩$.

>[!tip] Técnica: Sistema generador $\leftrightarrow$ Ecuaciones implícitas
>Sea $S = \text{Gen}⟨v_1, \dots, v_n⟩ \leq V$ un subespacio vectorial expresado vía un sistema generador, podemos obtener unas ecuaciones implícitas viendo cuándo
>$$
>	v = \alpha_1 \cdot v_1 + \cdot + \alpha_n \cdot v_n
>$$
> es un sistema compatible. Y al revés, para obtener un sistema generador a partir de unas ecuaciones implícitas debemos resolverlas y descomponer la solución como una combinación lineal.