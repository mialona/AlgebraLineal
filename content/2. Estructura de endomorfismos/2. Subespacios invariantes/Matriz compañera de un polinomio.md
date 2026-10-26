---
title: Matriz compañera de un polinomio
---
>[!example] Proposición
>Sea $v\in V$ un vector no nulo con [[Polinomio mínimo de un vector|polinomio mínimo]] $m_v(x)=a_0+a_1x+\cdots+a_{k-1}x^{k-1}+x^k$, entonces $\mathcal{B}=\{v,f(v),\dots,f^{k-1}(v)\}$ es una [[Base o sistema generador minimal|base]] de $\mathbb{F}[x](f)(v)$, en particular $\text{dim}\,\mathbb{F}[x](f)(v)=\text{deg}\, m_v(x)=k$. Además, en dicha base, el [[Aplicación lineal|endomorfismo]] restringido a $\mathbb{F}[x](f)(v)$ tiene por [[Aplicación y matriz coordenada|matriz coordenada]]
>$$
>C_{m_v(x)}=\begin{pmatrix}
>0&0&\cdots&0&-a_0\\
>1&0&\cdots&0&-a_1\\
>0&1&\cdots&0&-a_2\\
>\vdots&\vdots&\ddots&\vdots&\vdots\\
>0&0&\cdots&1&-a_{k-1}
>\end{pmatrix}
>$$
>A esta matriz se le llama ==matriz compañera== del [[Polinomio|polinomio]] $m_v(x)$.

