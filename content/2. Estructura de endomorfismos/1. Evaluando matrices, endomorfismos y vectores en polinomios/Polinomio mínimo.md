---
title: Polinomio mínimo
---
El [[Polinomio|polinomio mónico]] de menor grado para el cual una matriz cuadrada $A$ es [[Matriz raíz de un polinomio|raíz]] se llama ==polinomio mínimo== de $A$ y lo denotamos por $m_A(x)$.

>[!example] Proposición
>Si $p(x)$ es un polinomio tal que $p(A)=0$ entonces $p(x)$ es un múltiplo de $m_A(x)$. En particular, el [[Polinomio característico|polinomio característico]] es múltiplo del polinomio mínimo.

>[!tip] Técnica: Calcular el polinomio mínimo
>Basta encontrar la primera potencia de $A$ que sea [[Sistema generador|combinación lineal]] de potencias anteriores, tomando que $A^0=\text{Id}$. Es decir, calculamos
>$$
>A^0=\text{Id},\, A^1=A,\,\dots,A^{n-1},\dots
>$$
>hasta que encontremos la primera $A^n$ que sea combinación lineal de las anteriores
>$$
>A^n=\lambda_{n-1}A^{n-1}+\cdots+\lambda_1A+\lambda_0\text{Id}.
>$$
>En este caso el polinomio mínimo será
>$$
>m_A(x)=x^n-\lambda_{n-1}x^{n-1}-\dots-\lambda_1x-\lambda_0.
>$$