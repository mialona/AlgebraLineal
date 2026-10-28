---
title: Aplicaciones autoadjuntas
---
>[!example] Proposición
>Sea $(V,\langle\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio euclídeo o unitario]]. La [[Aplicación lineal|aplicación lineal]] $f\colon V\to V$ es [[Aplicación adjunta|autoadjunta]] si y solamente si la [[Aplicación y matriz coordenada|matriz coordenada]] de $f$ respecto de una [[Ortogonalidad en productos escalares|base ortonormada]] es [[Matriz hermitiana|hermitiana]] ($\overline{A^t}=A$).

>[!example] Proposición
>Los [[Valor y vector propio|valores propios]] de una matriz hermitiana son siempre reales.

>[!example] Proposición
>Los [[Valor y vector propio|subespacios fundamentales]] de una aplicación autoadjunta son siempre [[Subespacios ortogonales|ortogonales]] entre sí.

>[!quote] Teorema espectral para aplicaciones autoadjuntas
>Dada una aplicación lineal $f\colon V\to V$ autoadjunta existe una base ortonormada donde la matriz coordenada de $f$ es diagonal.

>[!success] Corolario
>- Si $A\in\mathcal{M}_n(\mathbb{C})$ es una matriz hermitiana entonces existe una matriz $P$ [[Ortogonalidad en productos escalares|unitaria]] tal que
>$$
>PA\overline{P^t}=\text{diag}(\alpha_1,\dots,\alpha_n)
>$$
>con $\alpha_i\in\mathbb{R}$.
>- Si $A\in\mathcal{M}_n(\mathbb{R})$ es una matriz simétrica entonces existe una matriz $P$ [[Ortogonalidad en productos escalares|ortogonal]] tal que
>$$
>PAP^t=\text{diag}(\alpha_1,\dots,\alpha_n)
>$$
>con $\alpha_i\in\mathbb{R}$.

>[!warning] Observación
>Las matrices simétricas reales son [[Matrices congruentes y cambio de coordenadas|congruentes]] y [[Matrices semejantes|semejantes]] a su forma diagonal de los valores propios. Por eso, estudiar su [[Ley de inercia de Sylvester|signatura]] equivale a estudiar los signos de los valores propios.

>[!warning] Observación
>El [[Mínimos cuadrados|método de mínimos cuadrados]] nos proporciona matrices simétricas cuando consideramos $A^t A$ en $\mathbb{R}$ y hermitianas en $\mathbb{C}$ al tomar $\overline{A^t}A$.