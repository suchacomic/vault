---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Vector Potential 
- If $\vec{F}$ is a [[Vector Fields|vector field]] whose [[Partial Derivatives#Higher Order Partial Derivatives|second order derivative]] is [[Continuity|continuous]], then it is called a [[Irrotational and Solenoidal Vector Fields#Solenoidal Fields|solenoidal vector field]] if the [[Double Integrals|surface integral]] is independent of the surface $\mathcal{S}$, for any given boundary curve and is determined entirely by the perimeter of the surface, $\mathcal{P}$.
- $\displaystyle \iint\limits_{\mathcal{S}}\vec{F}\cdot d\vec{a}$ is independent of the surface if, $$\iint\limits_{\mathcal{S}_{1}}\vec{F}\cdot d\vec{a}=\iint\limits_{\mathcal{S}_{2}}\vec{F}\cdot d\vec{a}$$for any two surfaces $\mathcal{S}_{1}$ and $\mathcal{S}_{2}$ enclosed by the same perimeter curve $\mathcal{P}$.
- The [[Double Integrals|closed surface integral]] of a [[Irrotational and Solenoidal Vector Fields#Solenoidal Fields|solenoidal vector field]] is always zero for any surface as it only depends upon the perimeter curve thus both limits to the integral old be the same curve at same points.
- The [[Divergence|divergence]] of solenoidal fields is zero, $$ \nabla\cdot \vec{F} = 0
$$and by the [[Second Order Derivative in Multiple Variables|the divergence of curl]] is always zero,$$\nabla\cdot(\nabla \times \vec{A})=0$$Hence, there exists a vector function $\vec{A}$ such that $\vec{F}=\nabla \times \vec{A}$
- The vector function $\vec{A}$ is called a **vector potential function** for the vector field $\vec{F}$.
- The Vector Potential is not unique, the [[Gradient|gradient]] of any scalar function can be added to $\vec{A}$ without affecting the curl, since the curl of a gradient is always zero.$$\vec{F}=\nabla \times \vec{A}-\nabla V$$where is $V$ is any arbitrary scalar function. 
# See also

- [[Conservative Vector Fields and Potential]]
- [[Curl]]
- [[Helmholtz Decomposition Theorem]]