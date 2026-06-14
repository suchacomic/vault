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
- Let $\mathbf{F}$ be a conservative force and let $C_{1}$ and $C_{2}$ by any two paths connecting two points ${} \mathbf{x}_{1} {}$ and ${} \mathbf{x}_{2} {}$. Then by the definition of conservative force, $$\int_{C_{1}} \mathbf{F} \cdot d\mathbf{x} = \int_{C_{2}} \mathbf{F} \cdot d\mathbf{x}$$or $$\int_{C_{1}} \mathbf{F} \cdot d\mathbf{x} -\int_{C_{2}} \mathbf{F} \cdot d\mathbf{x} = \oint \mathbf{F} \cdot d\mathbf{x} = \mathbf{0}$$Thus if $\mathbf{F}$ is conservative, $\oint \mathbf{F} \cdot d\mathbf{x}  = 0$ around <u>any</u> closed path, for $\mathbf{x}_{1}$ and $\mathbf{x}_{2}$ are arbitrary.
- [[The Fundamental Theorem for Surface Integrals and Curls|Stokes' theorem]] is used to transform the closed line integral to a surface integral, giving $$\oint_{C} \mathbf{F} \cdot d\mathbf{x} = \iint_{\Sigma} (\nabla \wedge \mathbf{F}) \cdot d\mathbf{S}$$ where $\Sigma$ is any smooth surface bounded by the closed path $C$ of the [[Line Integrals|line integral]], and $d\mathbf{S}$ is the vector element of area in $\Sigma$. 
- Since the left hand is zero for every closed contour $C$, this for every $\Sigma$ $$\nabla \wedge \mathbf{F} = \mathbf{0}$$is a necessary condition for $\mathbf{F}$ to be conservative. 
- This equation may be recognized as the [[Integrability Condtion|integrability condition]] for the existence of a single [[Function|function]] that is a solution ${U}(\mathbf{x})$.
# Potential 
- From [[Conservative Vector Fields and Potential#Scalar Potentials| the property of conservative vector fields]] we can assert that there exists a scalar potential for the conservative force $\mathbf{F}(\mathbf{r})$, $$\mathbf{F}(\mathbf{r})=-\nabla U(\mathbf{r})$$where $U$ is called the [[Potential Energy and The Conservation of Mechanical Energy#Potential Energy|potential energy]] of the [[Dynamical Variables|dynamical system]] whose force $\mathbf{F}$ is a conservative force.
- Force can be defined as the [[Gradient|gradient]] of potential energy.

[^1]: see [[Conservative Vector Fields and Potential#Cross-Partial Test of Conservative Fields|Cross-partial test of conservative fields]]
