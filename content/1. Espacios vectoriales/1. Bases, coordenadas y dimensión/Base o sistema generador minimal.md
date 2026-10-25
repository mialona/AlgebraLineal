---
title: Base o sistema generador minimal
---
Un [[Conjunto de elementos|conjunto]] $\mathcal{B} = \{v_1, \dots , v_n\}$ es ==base== (o sistema generador minimal) de $V$ si $V = \text{Gen}⟨v_1, \dots , v_n⟩$ y no existen vectores [[Familia libre|linealmente dependientes]] en $B$, es decir, el sistema
$$
\alpha_1 \cdot v_1 + \dots + \alpha_n \cdot v_n = 0
$$

 tiene por única solución que todos los $\alpha_i = 0$.

A su vez, diremos que las bases de dos [[Subespacio vectorial|subespacios vectoriales]] $V$ y $W$ son ==disjuntas== cuando los vectores que forman ambas bases no comparten ningún elemento entre sí, es decir, su intersección es el conjunto vacío:
$$
\mathcal{B}_U\cap \mathcal{B}_W=\varnothing
$$

>[!abstract] Lema
>Una [[Aplicación lineal|aplicación lineal]] está unívocamente determinada por la [[Imagen, preimagen y núcleo|imagen]] de los [[Conjunto de elementos|elementos]] de una base del espacio de salida.
