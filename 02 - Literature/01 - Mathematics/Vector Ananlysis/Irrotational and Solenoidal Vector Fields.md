---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Irrotational Vector Fields 
- [[Curl|Curl-less]] or **irrotational** fields are vector fields for which the curl is zero.
- They are also called [[Conservative Vector Fields and Potential|conservative vector fields.]] 
- The following conditions are <u>equivalent</u>, that is if one of them is true the all of them are true,
	1. $\nabla \times \vec{F}=\vec{0}$ everywhere.
	2. $\displaystyle\int_{a}^{b} \vec{F}\cdot d\vec{l}$ is independent of path, for any given end points.
	3. $\displaystyle\oint \vec{F}\cdot d\vec{l}=0$ for any closed loop.
	4. $\vec{F}$ is the gradient of some scalar function: $\vec{F}=-\nabla V$, where $V$ is called the [[Conservative Vector Fields and Potential#Scalar Potentials|scalar potential]] of $\vec{F}$.
- The potential is not unique, any constant can be added to V with impunity, since this will not affect its gradient.
- The proof of all the above is given exhaustively in [[Conservative Vector Fields and Potential#Scalar Potentials|scalar potential section]] .
# Solenoidal Fields
-  [[Divergence|Divergence-less]] or **solenoidal** fields are vector fields for which the divergence is zero.
- The following conditions are <u>equivalent</u>, that is if one of them is true the all of them are true,
	1. $\nabla\cdot \vec{F}=0$ everywhere. 
	2. $\displaystyle\iint \vec{F}\cdot d\vec{a}$ is independent if surface, for any given boundary line.
	3. $\displaystyle \oint \limits_{\mathcal{S}} \vec{F}\cdot d\vec{a}=o$ for any close surface $\mathcal{S}$.
	4. $\vec{F}$ is the curl of some vector function: $\vec{F}=\nabla \times \vec{A}$, where $\vec{A}$ is called the [[Vector Potential]] of $\vec{F}$.
- The [[Vector Potential|vector potential]] is not unique the [[Gradient|gradient]] of any scalar function can be added to $\vec{A}$ without affecting the [[curl]], since the [[Second Order Derivative in Multiple Variables|curl of a gradient]] is always zero.
# See also

- [[Helmholtz Decomposition Theorem]]
- 