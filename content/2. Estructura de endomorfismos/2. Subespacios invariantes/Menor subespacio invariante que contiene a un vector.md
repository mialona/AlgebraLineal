---
title: Menor subespacio invariante que contiene a un vector
---
>[!example] Proposición
>Sea $v\in V$ y $f\in\text{End}(V)$ un [[Aplicación lineal|endomorfismo]]. Se tiene que $\mathbb{F}[x](v)$ ([[Evaluar y órbitas|órbita]] de $v$) es el menor [[Subespacio vectorial|subespacio]] $f$.[[Subespacio invariante|invariante]] que contiene a $v$. 

>[!tip] Técnica: Menor invariante que contiene a un vector
>Una forma de calcular $\mathbb{F}[x](v)$ es aplicando la definición de ser el menor subespacio $f$-invariante que contiene a $v$. Para ello procedemos de la siguiente forma
>1. Empezamos definiendo $v_0=v$ y $S_0=\text{Gen}\langle v_0\rangle$. Si $v_1=f(v_0)\in S_0$ entonces hemos acabado y $S_0$ era el subespacio buscado.
>2. En cambio, si no, tomamos $S_1=\text{Gen}\langle v_0,v_1\rangle$. como $f(v_0)=v_1$, para ver si es invariante solo falta ver si $v_2=f(v_1)\in S_1$.
>Este segundo paso habrá que repetirlo hasta que sea invariante. Así, dado $S_i$, deberemos ver si $v_{i+1}=f(v_i)=f^i(v_0)=f^i(v)\in S_i$ y añadirlo para crear $S_{i+1}$ si no estuviese.
>Al concluir el proceso, que acabamos a lo sumo en $\text{dim}\, V$ pasos, tendremos un $S_k=\text{Gen}\langle v,f(v),\dots,f^k(v)\rangle=\mathbb{F}[x](f)(v).$