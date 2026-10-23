---
title: Suma de subespacios
---
Dados dos [[Subespacio vectorial|subespacios]] $S$ y $T$, la ==suma== de $S$ y $T$ se define como
$$
S + T := \{s + t : s \in S, t \in T\}.
$$

>[!example] Proposición
>$S + T$ es el subespacio más pequeño que contiene a $S$ y $T$.

>[!example] Proposición
>Si $S = \text{Gen}⟨u_1, \dots , u_n⟩$ y $T = \text{Gen}⟨v_1, \dots , v_m⟩$ entonces 
>$$
>S + T = \text{Gen}⟨u_1, \dots , u_n, v_1, \dots , v_m⟩.
>$$

>[!tip] Técnica: Hacer una suma de espacios vectoriales
>Dados dos subespacios $S, T \leq V$ para calcular $S + T$ hacemos: 
>1. Expresar $S$ y $T$ como [[Sistema generador|sistemas generadores]]. 
>2. Formar un sistema generador con la unión de ambos generadores.
>3. Eliminar elementos [[Familia libre|dependientes]] para obtener una base (de forma opcional, según nos pidan o necesitemos).