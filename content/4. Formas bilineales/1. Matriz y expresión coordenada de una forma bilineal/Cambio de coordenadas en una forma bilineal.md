---
title: Cambio de coordenadas en una forma bilineal
---
Si $f\colon V\times V\to\mathbb{F}$ es una [[Forma bilieal|forma bilineal]], $\mathcal{B}$ y $\mathcal{B}'$ son [[Base o sistema generador minimal|bases]] de $V$ con $P=c_{\mathcal{B}\mathcal{B}'}$ la [[Cambio de base|matriz de cambio]] entre ellas, $[v]_\mathcal{B}=X^t$, $[w]_\mathcal{B}=Y^t$ y $[v]_{\mathcal{B}'}=\hat{X}^t$, $[w]_{\mathcal{B}'}=\hat{Y}^t$ las [[Coordenadas en una base|coordenadas]] de $v$ y $w$ y $M=[f]_\mathcal{B}$ y $M'=[f]_{\mathcal{B}'}$ las [[Forma bilineal|matrices de Gram]] de la forma bilineal. Entonces tenemos dos expresiones coordenadas para $f$:
$$
\begin{split}
f(v,w)&=\hat{X}^tM'\hat{Y},\\
f(v,w)&=X^tMY=(P\hat{X})^tM(P\hat{Y})=\hat{X}^tP^tMP\hat{Y}.
\end{split}
$$
Es decir, $M'=P^t MP$.

>[!abstract] Lema
>Si $M$ es la matriz coordenada de $f\colon V\times V\to\mathbb{F}$ respecto de la base $\mathcal{B}$ y $M'$ es la matriz coordenada de $f$ respeto de la base $\mathcal{B}'$ entonces $M'=P^t MP$ donde $P$ es la matriz de cambio de coordenadas de la base $\mathcal{B}'$ a la base $\mathcal{B}$. Por tanto, las matrices asociadas a una forma bilineal en distintas bases son [[Matrices congruentes y cambio de coordenadas|congruentes]].

Como con las [[Forma cuadrática|formas cuadrática]] que las matrices coordenadas sean congruentes nos permite definir el ==rango== de una forma bilineal como el rango de cualquiera de sus matrices coordenadas
$$
\text{rang}(f)=\text{rang}(M).
$$
Si además $\text{dim}\, V=n$ diremos que
- $f$ es ==degenerada== si $\text{rang}(f)\neq n$,
- $f$ es ==regular== o ==no degenerada== si $\text{rang}(f)=n$.