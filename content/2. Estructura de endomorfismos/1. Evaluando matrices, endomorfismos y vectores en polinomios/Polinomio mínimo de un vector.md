---
title: Polinomio mínimo de un vector
---
Dado $v\in V$, $f\in\text{End}(V)$ y un [[Polinomio|polinomio]] $p(x)$, diremos que $v$ es ==raíz== de $p(x)$ si la [[Evaluar y órbitas|evaluación]] $p(f)(v)=0$. Definimos el ==polinomio mínimo== de $v$ (relativo a $f$) como el polinomio [[Polinomio|mónico]] de menor grado para el cual $v$ es raíz. Denotamos dicho polinomio por $p_v(x)$.

>[!warning] Observación
>Para cualquier $v\in V$ y cualquier [[Aplicación lineal|endomorfismo]] $f\colon V\to V$ el polinomio mínimo de $v$ divide al [[Endomorfismo raíz de un polinomio|polinomio mínimo]] de $f$ y este último divide al [[Endomorfismo raíz de un polinomio|polinomio característico]] de $f$:
>$$
>m_v(x)\mid m_f(x)\mid p_f(x).
>$$