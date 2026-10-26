---
title: Evaluar y órbitas
---
Sea $p(x)=a_0+a_1x+\cdots+a_nx^n\in\mathbb{F}[x]$ y sea $A\in\mathcal{M}_n(\mathbb{F})$, $f\in\text{End}(V)$ y $v\in V$, $S\leq V$, siendo $V$ un $\mathbb{F}$-[[Espacio vectorial|espacio vectorial]] definimos:
$$
\begin{split}
p(A)&:=a_0I_n+a_1A+\cdots+a_nA^n\in\mathcal{M}_n(\mathbb{F}),\\
p(f)&:=a_0\text{id}+a_1f+\cdots+a_nf^n\in\text{End}(V),\\
p(f)(v)&:=a_0\text{id}(v)+a_1f(v)+\cdots+a_nf^n(v)\in V,\\
p(f)(S)&:=\{p(f)(s) : s\in S\}\subseteq V.\\
\end{split}
$$
Y, evaluando sobre el [[Espacio vectorial|espacio]] de todos los [[Polinomio|polinomio]], tenemos:
$$
\begin{split}
\mathbb{F}[x](A)&:=\{p(A) : p\in\mathbb{F}[x]\}\leq\mathcal{M}_n(\mathbb{F}),\\
\mathbb{F}[x](f)&:=\{p(f) : p\in\mathbb{F}[x]\}\leq\text{End}(V),\\
\mathbb{F}[x](f)(v)&:=\{p(f)(v) : p\in\mathbb{F}[x]\}\leq V,\\
\mathbb{F}[x](f)(S)&:=\bigcup\{p(f)(S) : p\in\mathbb{F}[x]\}\leq V,\\
\end{split}
$$