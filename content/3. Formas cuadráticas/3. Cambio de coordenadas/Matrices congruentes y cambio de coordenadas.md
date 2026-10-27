---
title: Matrices congruentes y cambio de coordenadas
---
Si $Q$ es una [[Forma cuadrática|forma cuadrática]] en $V$, $\mathcal{B}$ y $\mathcal{B}'$ son [[Base o sistema generador minimal|bases]] de $V$ con $P=c_{\mathcal{B}\mathcal{B}'}$ la [[Cambio de base|matriz de cambio]] entre ellas, $[v]_\mathcal{B}=X^t$ y $[v]_{\mathcal{B}'}=\hat{X}^t$ las [[Coordenadas en una base|coordenadas]] de un vector y $A=[Q]_\mathcal{B}$ y $B=[Q]_{\mathcal{B}'}$ las [[Forma cuadrática|matrices de Gram]] de la forma cuadrática. Entonces tenemos dos expresiones coordenadas para $Q$:
$$
\begin{split}
Q(v)&=\hat{X}^tB\hat{X},\\
Q(v)&=X^tAX=(P\hat{X})^tA(PX)=\hat{X}^tP^tAPX.
\end{split}
$$
Es decir, $B=P^t AP$.

Dos matrices $A$ y $B$ se dicen ==congruentes== is existe $P$ invertible tal que 
$$
B=P^t AP.
$$Como las matrices de Gram de una forma cuadrática son todas congruentes, esto no permite definir el ==rango== de una forma cuadrática como el rango de cualquier matriz de Gram:
$$
\text{rang}(Q)=\text{rang}([Q]_\mathcal{B}).
$$