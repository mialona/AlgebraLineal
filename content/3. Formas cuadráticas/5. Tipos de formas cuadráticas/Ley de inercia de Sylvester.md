---
title: Ley de inercia de Sylvester
---
>[!quote] Teorema: Ley de inercia de Sylvester
>Sea $\mathbb{F}=\mathbb{R}$ y sean $\mathcal{B}$ y $\mathcal{B}'$ dos [[Base ortogonal y completar cuadrados|bases ortogonales]] de $V$ tales que la [[Forma cuadrática|forma cuadrática]] $Q$ tiene las expresiones
>$$
>\begin{split}
>Q(v)&=\alpha_1x_1^2+\cdots+\alpha_rx_r^2\quad\text{si }[v]_{\mathcal{B}}=(x_1,\dots,x_n),\\
>Q(v)&=\beta_1y_1^2+\cdots+\beta_ry_r^2\quad\text{si }[v]_{\mathcal{B'}}=(y_1,\dots,y_n).
>\end{split}
>$$
>Se tiene que $\lvert\{\alpha_i :  \alpha_i>0\}\rvert=\lvert\{\beta_i :  \beta_i>0\}\rvert$. Llamamos ==signatura== de $Q$ a
>$$
>\text{sig}(Q)=\lvert\{\alpha_i :  \alpha_i>0\}\rvert-\lvert\{\alpha_i :  \alpha_i<0\}\rvert.
>$$

>[!success] Corolario
>Sean $A,B\in\mathcal{M}_n(\mathbb{F})$ matrices simétricas, existe $R\in\mathcal{M}_n(\mathbb{F})$ regular tal que
>$$
>R^t AR=\text{diag}(\alpha_1,\dots,\alpha_r,0,\dots,0)
>$$
>con $\alpha_1\cdots\alpha_r\neq 0$. Además,
>- Si $\mathbb{F}=\mathbb{R}$ entonces
>$$
>R^t AR=\text{diag}(1,\dots,1,-1,\dots,-1,0,\dots,0).
>$$
>- Si $\mathbb{F}=\mathbb{C}$ entonces
>$$
>R^t AR=\text{diag}(1,\dots,1,0,\dots,0).
>$$
>En estos casos:
>- Si $\mathbb{F}=\mathbb{R}$ y $A$ es congruente con una matriz $\text{diag}(\alpha_1,\dots,\alpha_r,0,\dots,0)$ entonces $\lvert\{\alpha_i : \alpha_i>0\}\rvert$ queda unívocamente determinado por $A$. Llamaremos ==signatura== de $A$ a 
>$$
>\text{sig}(A)=\lvert\{\alpha_i :  \alpha_i>0\}\rvert-\lvert\{\alpha_i :  \alpha_i<0\}\rvert.
>$$
>Y entonces $A$ y $B$ son congruentes si y solamente si $\text{rang}(A)=\text{rang}(B)$ y $\text{sig}(A)=\text{sig}(B)$.
>- si $\mathbb{F}=\mathbb{C}$ entonces $A$ y $B$ son congruentes si y solo si $\text{rang}(A)=\text{rang}(B)$.