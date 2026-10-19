---
title: Base o sistema generador minimal
---
Un conjunto $B = \{v_1, \dots , v_n\}$ es ==base== (o sistema generador minimal) de $V$ si $V = \text{Gen}⟨v_1, \dots , v_n⟩$ y no existen ~~vectores linealmente dependientes~~ en $B$, es decir, el sistema
$$
\alpha_1 \cdot v_1 + \dots + \alpha_n \cdot v_n = 0
$$ tiene por única solución que todos los $\alpha_i = 0$.

>[!abstract] Lema
>Sea $V$ un $\mathbb{F}$-[[Espacio vectorial|espacio vectorial]] $n$-dimensional con [[Base o sistema generador minimal|base]] $B$, la [[Aplicación y matriz coordenada|aplicación coordenada]] $c_B : V \rightarrow F^n$ tal que $c_B(v) = [v]_B$ es [[Aplicación lineal|aplicación lineal biyectiva]].

>[!abstract] Lema
>Una [[Aplicación lineal|aplicación lineal]] está unívocamente determinada por la [[Imagen, preimagen y núcleo|imagen]] de los [[Conjunto de elementos|elementos]] de una [[Base o sistema generador minimal|base]] del espacio de salida.