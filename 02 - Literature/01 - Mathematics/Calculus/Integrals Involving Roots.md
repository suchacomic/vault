---
tags:
  - Calculus
  - integration
  - integration_techniques
  - Mathematics
---
- Sometimes, when an [[Integrals|integral]] contains $\sqrt[n]{g(x)}$, using $u=\sqrt[n]{g(x)}$ can be used to simplify.

- For example, $$
	\int \frac{2}{x-3\sqrt{x+10}} \, dx$$$$\begin{align}
 u = \sqrt{x+10} & & x = u^{2}-10 & & dx=2u\,du  
\end{align}$$$$\begin{align} \\
\int \frac{2}{x-3\sqrt{ x+10 }} \, dx & =\int \frac{2}{(u^{2}-10)-3(u)}(2u) \, du  \\
& = \int \frac{4u}{u^{2}-3u-19} \, du
\end{align}
$$
- This transformed integral can be solved using [[Integration by Partial Fractions|partial fractions]].
## See also

- [[Integration Techniques]]
- [[Integrals]]