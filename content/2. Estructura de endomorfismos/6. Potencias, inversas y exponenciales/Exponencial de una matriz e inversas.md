---
title: Exponencial de una matriz e inversas
---
Dada una matriz $A\in\mathcal{M}_n(\mathbb{R})$, se define la ==exponencial== de $A$ como la matriz
$$
e^A=\sum_{n=0}^\infty \dfrac{A^n}{n!}.
$$
>[!example] Proposición
>Si tenemos una matriz de dimensión $k\times k$ cuya estructura es un [[Forma canónica de Jordan|bloque de Jordan]]
>$$
>J_\lambda=\begin{pmatrix}
>\lambda &0&\cdots&0&0\\
>1 &\lambda&\cdots&0&0\\
>\vdots &\vdots&\ddots&\vdots&\vdots\\
>0 &0&\cdots&\lambda&0\\
>0 &0&\cdots&1&\lambda\\
>\end{pmatrix}
>$$
>entonces
>$$
>J_\lambda^n=\begin{pmatrix}
>\lambda^n&0&0&\cdots&0&0\\
>\binom{n}{1}\lambda^{n-1}&|lambda^n&0&\cdots&0&0\\
>\binom{n}{2}\lambda^{n-2}&\binom{n}{1}\lambda^{n-1}&\lambda^n&\cdots&0&0\\
>\vdots&\vdots&\vdots&\ddots&\vdots\vdots\\
>\binom{n}{k-2}\lambda^{n-k+2}&\binom{n}{k-3}\lambda^{n-k+3}&\binom{n}{k-4}\lambda^{n-k+4}&\cdots&\lambda^n&0\\
>>\binom{n}{k-1}\lambda^{n-k+1}&\binom{n}{k-2}\lambda^{n-k+2}&\binom{n}{k-3}\lambda^{n-k+3}&\cdots&\binom{n}{1}\lambda^{n-1}&\lambda^n\\
>\end{pmatrix},
>$$
>$$
>e^{J_\lambda}=e^\lambda\begin{pmatrix}
>1&0&0&\cdots&0&0\\
>1&1&0&\cdots&0&0\\
>\frac{1}{2!}&1&1&\cdots&0&0\\
>\vdots&\vdots&\vdots&\ddots&\vdots&\vdots\\
>\frac{1}{(k-2)!}&\frac{1}{(k-3)!}&\frac{1}{(k-4)!}&\cdots&1&0\\
>\frac{1}{(k-1)!}&\frac{1}{(k-2)!}&\frac{1}{(k-3)!}&\cdots&1&1
>\end{pmatrix}
>$$
>y, si $\lambda\neq 0$, definiendo $\binom{n}{i}\lambda^{n-i}=0$ si $i>n$ tenemos que
>$$
>J_\lambda^{-1}=\begin{pmatrix}
>\lambda^{-1}&0&0&\cdots&0&0\\
>-\lambda^{-2}&\lambda^{-1}&0&\cdots&0&0\\
>\lambda^{-3}&-\lambda^{-2}&\lambda^{-1}&\cdots&0&0\\
>\vdots&\vdots&\vdots&\ddots&\vdots&\vdots&\\
>-(-\lambda)^{-(k-1)}&-(-\lambda)^{-(k-2)}&-(-\lambda)^{-(k-3)}&\cdots&\lambda^{-1}&0\\
>-(-\lambda)^{-k}&-(-\lambda)^{-(k-1)}&-(-\lambda)^{-(k-2)}&\cdots&-\lambda^{-2}&\lambda^{-1}
>\end{pmatrix}.
>$$

>[!warning] Observación
>Usando [[Polinomio|desarrollos de Taylor]] de otras funciones podemos definir otras funciones sobre matrices. Por ejemplo
>$$
>\sin x=\sum_{n=0}^\infty\dfrac{(-1)^nx^{2n+1}}{(2n+1)!},\quad \cos x=\sum_{n=0}^\infty\dfrac{(-1)^nx^{2n}}{(2n)!},\quad (1+x)^\alpha=\sum_{n=0}^\infty\binom{\alpha}{n}x^n,
>$$
>en la última expresión $\alpha\in\mathbb{R}$ y 
>$$
>\binom{\alpha}{n}=\dfrac{\alpha(\alpha-1)(\alpha-2)\cdots(\alpha-n+1)}{n!}.
>$$