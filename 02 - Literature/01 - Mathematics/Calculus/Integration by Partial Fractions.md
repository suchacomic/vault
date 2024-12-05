---
tags:
  - Calculus
  - integration
  - integration_techniques
  - Mathematics
---
- For polynomials in form $\displaystyle \int \frac{f'(x)}{f(x)} \, dx$ or $\displaystyle \int f(x)f'(x) \, dx$, we can simply use [[Integration by Substitution|substitution]].

- For rational expression in the form $$\displaystyle f(x)=\frac{P(x)}{Q(x)}$$
 where both $P(x)$ and $Q(x)$ are polynomials and the degree of $P(x)$ is smaller than the degree of $Q(X)$.

| Factors in denominator |                                                  Term in partial fraction decomposition                                                  |
|:----------------------:|:----------------------------------------------------------------------------------------------------------------------------------------:|
|         $ax+b$         |                                                             $\frac{A}{ax+b}$                                                             |
|      $(ax+b)^{k}$      |                       $\frac{A_{1}}{ax+b}+\frac{A_{2}}{(ax+b)^{2}}+\dots+\frac{A_{k}}{(ax+b)^{k}},\,k=1,2,3,\dots$                       |
|     $ax^{2}+bx+c$      |                                                       $\frac{{Ax+B}}{ax^{2}+bx+c}$                                                       |
|  $(ax^{2}+bx+c)^{k}$   | $\frac{A_{1}x+B_{1}}{{ax^2+bx+c}}+\frac{{A_{2}x+B_{2}}}{(ax^{2}+bx+c)^{2}}+\dots+\frac{{A_{k}x+B_{k}}}{(ax^{2}+bx+c)^k},\,k=1,2,3,\dots$ |
# Heavside’s Cover-up Method

$$\frac{{x-7}}{(x-1)(x+2)} = \frac{A}{x-1}+\frac{B}{x+2}$$

- To determine $A$, on the LHS we mentally cover-up the factor $(x-1)$ associated with $A$ and substitute $x=1$ in whats left; this gives us $A$, $$
\frac{{x-7}}{(\dots)(x+2)}\Bigg|_{x=1} = \frac{{1-7}}{1+2}=-2=A

$$
- Similarly $B$ is obtained by covering up the factor $(x+2)$ on the LHS and substituting $x=-2$, $$
\frac{{x-7}}{(x-1)(\dots)}\Bigg|_{x=-2}=\frac{{-2-7}}{-2-1}=3=B
$$

- Thus we get, $$
\frac{{x-7}}{(x-1)(x+2)}=-\frac{2}{x-1}+\frac{3}{x+2}

$$
## See also

- [[Integration Techniques]]
- [[Integrals]]