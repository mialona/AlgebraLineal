---
title: Cadenas conjugadas
---
Si $V$ es un $\mathbb{R}$-[[Espacio vectorial|espacio vectorial]], $f\colon V\to V$ un [[Aplicación lineal|endomorfismo]] y $p_f(x)$ su [[Endomorfismo raíz de un polinomio|polinomio característico]], sus raíces en $\mathbb{C}$ son conjugadas, es decir, si $\lambda=a+bi$ es una raíz, $\bar{\lambda}=a-bi$ también lo es. Si $\mathcal{B}=\{u_1,\dots,u_m\}$ es una $\mathbb{R}$-[[Base o sistema generador minimal|base]] de $V$, podemos extender los escalares y crear un espacio vectorial $V_{\mathbb{C}}$ con la misma base y considerar el mismo endomorfismo. En este nuevo espacio podemos conjugar vectores
$$
v=\lambda_1u_1+\cdots+\lambda_mu_m\Rightarrow \bar{v}=\bar{\lambda_1}u_1+\cdots+\bar{\lambda_m}u_m.
$$
Como las raíces de $p_f(x)$ son conjugadas, lo mismo es cierto para los [[Valor y vector propio|valores propios]] de $f$. Si ahora $\{v_1,\dots,v_n\}$ es una [[Base de cadenas de bloques|cadena]] para el valor propio $\lambda=a+bi$, entonces $\{\bar{v_1},\dots,\bar{v_n}\}$ es una cadena para $\bar{\lambda}$. Si nos quedamos ahora con la parte real e imaginaria de estos vectores, obtenemos que
$$
\begin{split}
f(\text{Re}(v_j))&=a\text{Re}(v_j)-b\text{Im}(v_j)+\text{Re}(v_{j+1}),\\
f(\text{Im}(v_j))&=b\text{Re}(v_j)+a\text{Im}(v_j)+\text{Im}(v_{j+1}).
\end{split}
$$
Al cambiar de la base $\mathcal{B}=\{v_1,\dots,v_n,\bar{v_1},\dots,\bar{v_n}\}$ a la nueva base $\mathcal{B}'=\{\text{Re}(v_1),\text{Im}(v_1),\dots,\text{Re}(v_n),\text{Im}(v_n)\}$ la estructura de la matriz pasa a ser
$$
\left(\begin{array}{ccc|ccc}
\lambda&0&0&0&0&0\\
1&\lambda&0&0&0&0\\
0&1&\lambda&0&0&0\\\hline
0&0&0&\bar{\lambda}&0&0\\
0&0&0&1&\bar{\lambda}&0\\
0&0&0&0&1&\bar{\lambda}
\end{array}\right)\Rightarrow\left(\begin{array}{cc|cc|cc}
a&b&0&0&0&0\\
-b&a&0&0&0&0\\\hline
1&0&a&b&0&0\\
0&1&-b&a&0&0\\\hline
0&0&1&0&a&b\\
0&0&0&1&-b&a
\end{array}\right).
$$
Es decir, dos cadenas conjugadas de tamaño $3$ se han unido en una cadena de bloques $2\times 2$ de tamaño $3$.