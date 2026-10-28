---
title: Valor y vector propio
---
Sea $f : V \rightarrow V$ una [[Aplicación lineal|aplicación lineal]] (endomorfismo) decimos que $\lambda$ es un ==valor propio== de $f$ si existe $v \neq 0$ tal que $f(v) = \lambda v$. A los vectores $v$ que cumplen esa condición se le denomina ==vectores propios== asociados al valor propio $\lambda$. Además al [[Subespacio vectorial|subespacio vectorial]]
$$
S(\lambda)=\ker(f-\lambda\text{Id})=\{v\in V : f(v)=\lambda v\},
$$
se le llama ==subespacio fundamental== asociado al valor propio $\lambda$.

>[!tip] Técnica: Buscar los valores propios
>Para buscar los valores propios vemos cuándo $(\lambda I_n − A)$ es [[Sistema de ecuaciones lineales|indeterminado]], es decir, el [[Rango y traza de una matriz|rango]] no es máximo luego $|\lambda I_n − A| = 0$.

>[!tip] Técnica: Buscar los vectores propios
>Para cada valor propio $λ$ hacemos
>$$
>\text{ker}(\lambda Id - f) = \{v \in V : (\lambda Id - f)(v) = 0\} = \{v \in V : f(v) = \lambda v\}.
>$$
>En términos de [[Aplicación y matriz coordenada|matrices coordenadas]], hacemos
>$$
>\text{Nul}(\lambda I_n - A) = \{x \in \mathbb{F}^n : (\lambda I_n - A)x = 0\} = \{x \in \mathbb{F}^n: Ax = \lambda x\}.
>$$