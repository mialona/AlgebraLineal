---
title: Endomorfismo raíz de un polinomio
---
Un [[Aplicación lineal|endomorfismo]] $f\colon V\to V$ es ==raíz== del [[Polinomio|polinomio]] $p(x)$ si al [[Evaluación de un polinomio en una matriz|evaluar]] $p(f)$ el resultado es la aplicación nula. Esto equivale a que p(A)=0 para cualquier [[Aplicación y matriz coordenada|matriz coordenada]] de $f$.

>[!example] Proposición
>Sean $A$ y $B$ matrices que representan al mismo en diferentes bases, es decir, [[Matrices semejantes|semejantes]], entonces $p_A(x)=p_B(x)$ y $m_A(x)=m_B(x)$. Además, A es [[Matriz raíz de un polinomio|raíz]] de $p(x)$ si y solo si lo es $B$.

La proposición permite definir el ==polinomio característico del endomorfismo== $f$ como el [[Polinomio característico|polinomio característico]] de cualquier matriz coordenada $A$, es decir,
$$
p_f(x)=p_A(x).
$$
De la misma forma, definimos el ==polinomio mínimo del endomorfismo== $f$ como el [[Polinomio mínimo|polinomio mínimo]] de cualquiera de sus matrices coordenadas,
$$
m_f(x)=m_A(x).
$$

