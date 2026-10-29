---
title: Grupo simétrico
---
El conjunto $\{\sigma\colon\{1,\dots,n\}\to\{1,\dots,n\} : \sigma\text{ es biyectiva}\}$ se llama ==grupo simétrico== de orden $n$ y se denota por $S_n$. Los elementos de $S_n$ se dicen ==permutaciones==.

Dada la [[Base canónica|base canónica]] $\{e_1,\dots,e_n\}$ de $\mathbb{F}^n$, se define la ==signatura== de $\sigma\in S_n$ como
$$
\text{sig}(\sigma)=\det(e_{\sigma(1)},\dots,e_{\sigma(n)}).
$$
Así, si $s$ es igual al número de cambios necesarios para pasar de $(\sigma(1),\dots,\sigma(n))$ a $(1,\dots,n)$ entonces
$$
\text{sig}(\sigma)=(-1)^s.
$$