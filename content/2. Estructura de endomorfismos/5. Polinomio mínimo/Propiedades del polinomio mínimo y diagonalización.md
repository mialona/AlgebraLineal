---
title: Propiedades del polinomio mínimo y diagonalización
---
>[!example] Proposición
>Sea $\mathcal{B} = \{v_1, \dots , v_n \}$ [[Base o sistema generador minimal|base]] de $V$ , se tiene que el [[Evaluación de un endomorfismo en una matriz|polinomio mínimo]] de $f$ cumple
>$$
>m_f(x)=\text{mcm}(m_{v_1}(x),\dots,m_{v_n}(x)).
>$$

>[!warning] Observación
>Esta proposición no requiere que $\{v_1 , \dots , v_n \}$ sea base, basta con que [[Sistema generador|genere]] $V$. Es decir, llevado al extremo $m_f(x)=\text{mcm}\{m_v(x) : v\in V\}$.

>[!quote] Teorema
>Una aplicación lineal $f\colon V\to V$ es [[Diagonalización|diagonalizable]] si y solo si su polinomio mínimo es de la forma $(x-\lambda_1)\cdots(x-\lambda_k)$ donde $\lambda_1,\dots,\lambda_n$ son distintos.

>[!example] Proposición
>Dados $v,w\in V$ y $f\in\text{End}(V)$ tal que $\ker m_v(x)\cap\ker m_w(x)=\{0\}$, se tiene que para $u=\alpha v+\beta w$, con $\alpha\beta\neq 0$, el [[Polinomio mínimo de un vector|polinomio mínimo]] de $u$ es
>$$
>m_u(x)=\text{mcm}(m_v(X),m_w(x)).
>$$
