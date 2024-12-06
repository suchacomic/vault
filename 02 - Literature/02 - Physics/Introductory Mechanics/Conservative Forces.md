---
tags:
  - Physics
  - Introductory_Mechanics
  - integration
---
# Conservative Forces
- A [[Fundamental Forces|force]] $\mathbf{F}$ acting on a particle is [[Conservative Vector Fields and Potential#Conservative Vector Field|conservative]] if and only if it satisfies two conditions:
	1. $\mathbf{F}$ depends only on the particle’s position $\mathbf{r}$; that is, $\mathbf{F}=\mathbf{F}(\mathbf{r})$
	2. For any two points $1$ and $2$, the [[Work Energy Theorem#Work|work]]$(1\to{2})$ done by $\mathbf{F}$ is the same for all paths between $1$ and $2$.
- The [[Line Integrals|path integral]] of $\mathbf{\mathbf{F}}(\mathbf{r})$ is thus independent of path and only depends upon the starting and the ending position.
- The [[Line Integrals#Closed Loop Integrals|closed loop integral]] of $\mathbf{F}(\mathbf{r})$ is always zero.
- The [[Curl|curl]] of a conservative force is always zero.[^1]
# Potential 
- From [[Conservative Vector Fields and Potential#Scalar Potentials| the property of conservative vector fields]] we can assert that there exists a scalar potential for the conservative force $\mathbf{F}(\mathbf{r})$, $$\mathbf{F}(\mathbf{r})=-\nabla U(\mathbf{r})$$where $U$ is called the [[Potential Energy and The Conservation of Mechanical Energy#Potential Energy|potential energy]] corresponding to the conservative force.
- Force can be defined as the [[Gradient|gradient]] of potential energy

[^1]: see [[Conservative Vector Fields and Potential#Cross-Partial Test of Conservative Fields|Cross-partial test of conservative fields]]
