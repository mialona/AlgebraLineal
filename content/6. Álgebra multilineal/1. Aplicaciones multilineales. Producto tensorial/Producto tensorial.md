---
title: Producto tensorial
---
Sean $V_1,\dots,V_n$ una serie de $\mathbb{F}$-[[Espacio vectorial|espacio vectoriales]]. Un par $(X,i)$ con $X$ un $\mathbb{F}$-espacio vectorial e
$$
i\colon V_1\times\cdots\times V_n\to X
$$
una [[Aplicación multilineal|aplicación multilineal]] se dice ==producto tensorial== de $V_1,\dots,V_n$ si para todo $(V,f)$ con $f\colon V_1\times\cdots\times V_n\to V$ multilineal existe una única $\overline{f}\colon X\to V$ [[Aplicación lineal|lineal]] tal que $f=\overline{f}\circ i$, es decir, el siguiente diagrama conmmuta

$$
\begin{array}{ccc}
 & & X \\
 & \overset{i}{\nearrow} &  \\
V_1 \times \cdots \times V_n &  & \downarrow \bar{f}\\
& \underset{f}{\searrow} &\\
&& V
\end{array}\quad\text{Propiedad Universal}
$$
Dos productos tensoriales $(X,i)$, $(Y,j)$ se dicen ==isomorfos== si existe $\varphi\colon X\to Y$ [[Aplicación lineal|isomorfismo]] tal que $j=\varphi\circ i$, es decir, el siguiente diagrama conmuta
$$
\begin{array}{ccc}
 & & X \\
 & \overset{i}{\nearrow} &  \\
V_1 \times \cdots \times V_n &  & \downarrow \varphi\\
& \underset{j}{\searrow} &\\
&& Y
\end{array}
$$
>[!example] Proposición. Unicidad
>En caso de existir, el producto tensorial es único salvo isomorfismo.

>[!quote] Teorema. Existencia
>El producto tensorial de cualesquiera $\mathbb{F}$-espacios vectoriales $V_1,\dots,V_n$ siempre existe.

Como este producto existe y es único salvo isomorfismo, sea cual sea el elegido lo denotaremos por
$$
V_1\otimes\cdots\otimes V_n.
$$
Y denotaremos también
$$
v_1\otimes\cdots\otimes v_n=i(v_1,\dots,v_n).
$$
