---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Uniqueness of Solution
- A [[Vector Fields|vector field]] is uniquely specified by giving its [[Divergence|divergence]] and its [[Curl|curl]] within a [[Curves and Regions#Simple Connected|simply connected region]] and its [[Tangent and Normal Vectors#Normal Vector|normal component]] on the boundary.
# Helmholtz Theorem
- A vector $\vec{F}$ with both source density ( [[Divergence|divergence]] ) and circulation density ( [[Curl|curl]] ) vanishing at infinity may be written as the sum of two parts, one of which is [[Irrotational and Solenoidal Vector Fields#Irrotational Vector Fields|irrotational]], the other of which is [[Irrotational and Solenoidal Vector Fields|solenoidal]].$$\vec{F}=-\nabla V+\nabla \times \vec{A}$$Where $V$ is a [[Conservative Vector Fields and Potential#Scalar Potentials|scalar potential]] and $\vec{A}$ is a [[Vector Potential|vector potential]].
- $\nabla V$ is irrotational as [[Second Order Derivative in Multiple Variables|curl of gradient]] is always zero: $\nabla \times(\nabla V)=\vec{0}$
- $\nabla \times \vec{A}$ is solenoidal as [[Second Order Derivative in Multiple Variables|divergence of curl]] is always zero: $\nabla\cdot(\nabla \times \vec{A})=0$
