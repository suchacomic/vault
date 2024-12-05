---
tags:
  - Mathematics
  - Calculus
  - derivatives
  - integration
  - Vector_Analysis
aliases:
  - Stokes' theorem
  - circulation
---
# The Fundamental Theorem for Surface Integrals and Curls
- The fundamental theorem for [[Curl|curls]] goes by a special name of **Stokes’ theorem**.
- The theorem states that if we have a smooth oriented surface $\mathcal{S}$ bounded by a [[Curves and Regions|simple, closed]], smooth boundary curve $\mathcal{P}$ with positive orientation, then for a [[Vector Fields|vector field]] $\vec{F}$,$$\iint\limits_{\mathcal{S}}(\nabla \times \vec{F})\cdot d\vec{a}=\oint\limits_{\mathcal{P}}\vec{F}\cdot d\vec{l}$$
- The [[Double Integrals|surface integral]] of a [[Curl|curl]] over a region, in this case it is a surface $\mathcal{S}$, is equal to the value of the function at the boundary. The boundary of a surface is its perimeter curve denoted here by $\mathcal{P}$. 
## Geometric Interpretation 
- The curl measures the “twist” of the [[Vector|vectors]] $\vec{F}$, now the integral of curl over some surface represents the “total amount of swirl”, as is done on the left side. We can determine that just as well going around the edge and find out how much the flow is following the boundary, as the [[Line Integrals|path integral]] is doing. 
- The term $\oint\limits_{\mathcal{P}} \vec{F}\cdot d\vec{l}$ is sometimes called the **circulation** of $\vec{F}$. 
# Corollaries 
1. $\displaystyle \int(\nabla \times \vec{F})\cdot d\vec{a}$ depends only on the boundary line, not the particular surface used.
2. $\displaystyle \oint(\nabla \times \vec{F})\cdot d\vec{a}=0$ for any closed surface, since the boundary line, like the mouth of the balloon, shrinks down to a point, and hence the line integral vanishes.
# See also

- [[The Fundamental Theorem for Line Integrals and Gradients]]
- [[The Fundamental Theorems for Volume Integrals and Divergence]]
- [[Conservative Vector Fields and Potential]]