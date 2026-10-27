---
title: Forma canónica de Jordan
---
>[!quote] Teorema: Forma canónica de Jordan
>Sea $f : V \rightarrow V$ una [[Aplicación lineal|aplicación lineal]] cuyo [[Polinomio característico|polinomio característico]] es de la forma $(x - λ_1)^{e_1} \dots (x - \lambda_k)^{e_k}$. Existe una [[Base o sistema generador minimal|base]] de $V$ de modo que la [[Aplicación y matriz coordenada|matriz coordenada]] de $f$ está formada por bloques diagonales de la forma
>$$
> \begin{pmatrix}  
> \lambda_j & 0 & 0 & \dots & 0 & 0\\  
> 1 & \lambda_j & 0 & \dots & 0 & 0\\
> 0 & 1 & \lambda_j & \dots & 0 & 0\\
> \vdots & \vdots & \vdots & \ddots & \vdots & \vdots\\
> 0 & 0 & 0 & \dots & \lambda_j & 0\\
> 0 & 0 & 0 & \dots & 1 & \lambda_j
> \end{pmatrix}
>$$
>El número de bloques que tienen a $\lambda_j$ en la diagonal es $\text{dim ker}(f - \lambda_j Id)$. El número de bloques de tamaño $i$ que tienen a $\lambda_j$ en la diagonal es
>$$
>2\text{ dim ker}(f - \lambda_j Id)^i - \text{dim ker}(f - \lambda_j Id)^{i+1} - \text{dim ker}(f - \lambda_j Id)^{i-1}
>$$

>[!warning] Observación
>El número de bloques, tamaños y valores en la diagonal son únicos en la forma canónica de Jordan, no así su ordención que es la que uno desee.
