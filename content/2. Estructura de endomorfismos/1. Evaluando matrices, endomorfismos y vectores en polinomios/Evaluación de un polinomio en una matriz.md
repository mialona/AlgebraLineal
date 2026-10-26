---
title: Evaluación de un polinomio en una matriz
---
Dado un [[Polinomio|polinomio]] $p(x)\in\mathbb{F}[x]$ y una matriz cuadrada $A$, si
$$
p(x)=a_nx^n+a_{n-1}x^{n-1}+\cdots+a_1x+a_0,
$$
definimos $p(A)$ como la matriz
$$
p(A)=a_nA^n+a_{n-1}A^{n-1}+\cdots+a_1A+a_0I_m.
$$

>[!abstract] Lema
>Si $p(x),q(x),r(x)$ son polinomios, $\alpha\in\mathbb{F}$ y $A$ es una matriz cuadrada entonces:
>1. Si $r(x)=p(x)+q(x)$, entonces $r(A)=p(A)+q(A)$.
>2. Si $r(x)=\alpha p(x)$, entonces $r(A)=\alpha p(A)$.
>3. Si $r(x)=p(x)\cdot q(x)$, entonces $r(A)=p(A)\cdot q(A)$.