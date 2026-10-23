>[!example] Proposición. Fórmula de la [[Dimensión de un espacio vectorial|dimensión]]
>$$\text{dim}(S+T)=\text{dim}\,S+\text{dim}\,T-\text{dim}(S\cap T).$$

>[!success] Corolario
>Sean $S,T\leq V$ tenemos que:
>- $\text{dim}(S+T)\leq\text{dim}\,V$,
>- $\text{dim}(S\cap T)\geq \text{dim}\,S+\text{dim}\,T-\text{dim}\,V$.

>[!tip] Técnica: [[Base o sistema generador minimal|Base]] de la suma a partir de base de la intersección
>Una forma de encontrar una base de $S+T$ es:
>1. Calcular una base de $S\cap T$.
>2. Ampliar esta base hasta $S$ y hasta $T$.
>3. Unir, eliminando repetidos, ambas ampliaciones.
>De paso, esto nos da las dimensiones de cada parte.