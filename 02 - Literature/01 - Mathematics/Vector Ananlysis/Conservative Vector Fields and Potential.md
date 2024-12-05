---
tags:
  - integration
  - Mathematics
  - Vector_Analysis
  - Calculus
---
# Conservative Vector Field
- Suppose that $\vec{F}$ is a [[Continuity|continuous]] [[Vector Fields|vector field]] in some domain $D$ then $\vec{F}$ is a **conservative** ( [[Irrotational and Solenoidal Vector Fields#Irrotational Vector Fields|irrotational]] ) [[Vector|vector]] field if the [[Line Integrals|line integral]] is _independent_ of path and is determined entirely by the end points.
- $\displaystyle \int\limits_{\mathcal{P}}\vec{F}\cdot d\vec{l}$ is independent of path if, $$\displaystyle \int\limits_{\mathcal{P}_{1}}\vec{F}\cdot d\vec{l}=\int\limits_{\mathcal{P}_{2}}\vec{F}\cdot d\vec{l}$$for any two paths $\mathcal{P}_{1}$ and $\mathcal{P}_{2}$ in the $D$ with the same initial and final points.
# Scalar Potentials
- The [[Line Integrals#Closed Loop Integrals|closed loop integral]] of a conservative vector field is always zero for any path as it only depends upon end points. By [[The Fundamental Theorem for Line Integrals and Gradients#Corollaries|gradient theorem’s second corollary]], the closed path integral of a gradient vector field is also always zero. Thus, $$\oint (\,\nabla f\,)\cdot d\vec{l}=\oint \vec{F}\cdot d\vec{l}=0$$Hence, there exists a scalar function $f$ such that $\vec{F}=\nabla f$.
- The function $f$ is called a scalar **potential function** for the vector field.
- The potential is not unique, any constant can be added to $f$ with impunity, since it will not affect its gradient.
## Cross-Partial Property of Conservative Fields
- From [[The Fundamental Theorem for Surface Integrals and Curls|Stokes' theorem]], for a smooth surface $\mathcal{S}$ bounded by a [[Curves and Regions|simple, closed]], smooth boundary curve $\mathcal{P}$, then for a [[Vector Fields|vector field]] $\vec{F}$, $$\iint\limits_{\mathcal{S}}(\nabla \times \vec{F})\cdot d\vec{a}=\oint\limits_{\mathcal{P}}\vec{F}\cdot d\vec{l}$$but as stated previously, for a conservative vector field the closed loop integral for any path is zero. Thus, $$\begin{align}
\iint\limits_{\mathcal{S}}(\nabla \times \vec{F})\cdot d\vec{a} &=0 \\
\nabla \times \vec{F}=\mathbf{0}
\end{align}$$
- If the conservative vector field $\vec{F}=P\,\hat{x}+Q\,\hat{y}+R\,\hat{z}$ then the [[Curl|curl]] of $\vec{F}$ is,$$\nabla \times \vec{F}=\begin{vmatrix} 
\hat{x} & \hat{y} & \hat{z} \\
\dfrac{ \partial  }{ \partial x } & \dfrac{ \partial  }{ \partial y } & \dfrac{ \partial  }{ \partial z } \\
P & Q & R
\end{vmatrix}=0$$or,$$(R_{y}-Q_{z})\,\hat{x}+(P_{z}-R_{x})\,\hat{y}+(Q_{x}-P_{y})\,\hat{z}=\mathbf{0}$$
Thus for a conservative vector field $\vec{F}=\langle P,Q,R \rangle$,$$P_{y}=Q_{x},\hspace{0.15in}Q_{z}=R_{y},\hspace{0.15in}R_{x}=P_{z}$$
- This property can also be used as a test for determining if the vector field is conservative.

## Cross-Partial Test of Conservative Fields
- Let $\vec{F}=P\,\hat{x}+Q\,\hat{y}$ be a vector field on an open and [[Curves and Regions#Simple Connected|simply-connected region]] $D$. Then if $P$ and $Q$ have [[Continuity|continuous]] first order [[Partial Derivatives|partial derivatives]] in $D$ then the vector field $\vec{F}$ is conservative only and only if, $$\frac{ \partial P }{ \partial y } = \frac{ \partial Q }{ \partial x } $$
- In three dimensions with $\vec{F}=\langle P,Q,R \rangle$, the vector field is conservative in the region $D$ only and only if, $$ P_{y}=Q_{x},\hspace{0.15in}Q_{z}=R_{y},\hspace{0.15in}R_{x}=P_{z} $$
## Finding the Scalar Potential Function
- We have by the definition of scalar potential $f$,$$\begin{align}
\nabla f &= \vec{F} \\
\frac{ \partial f }{ \partial x } \,\hat{x}+\frac{ \partial f }{ \partial y } \,\hat{y} &= P\,\hat{x}+Q\,\hat{y}
\end{align}$$By setting components equal we have,$$\frac{ \partial f }{ \partial x } =P\hspace{0.5in}\text{and}\hspace{0.5in} \frac{ \partial f }{ \partial y } =Q $$
- [[Integrals|Integrating]] each of these components with respect to appropriate variable we arrive at the following two equations,$$f(x,y)=\int P(x,y) \, dx \hspace{0.25in}\text{or}\hspace{0.25in} f(x,y)=\int Q(x,y) \, dy $$# See also

- [[Partial Derivatives]]
- [[Gradient]]
- [[Irrotational and Solenoidal Vector Fields]] 
- [[Vector Potential]]