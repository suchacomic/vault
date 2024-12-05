---
tags:
  - Mathematics
  - derivatives
  - Calculus
  - Vector_Analysis
---
1. The [[Divergence|divergence]] of [[curl]], $$\begin{align} \nabla\cdot(\nabla f) &= \left \langle \hat{x}\,\dfrac{ \partial  }{ \partial x } +\hat{y}\,\dfrac{ \partial  }{ \partial y } +\hat{z}\,\dfrac{ \partial  }{ \partial z }  \right\rangle \cdot \left \langle \dfrac{ \partial f }{ \partial x }\,\hat{x}+\dfrac{ \partial f }{ \partial y }\,\hat{y} + \dfrac{ \partial f }{ \partial z }\,\hat{z} \right\rangle \\ &= \dfrac{ \partial^{2} f }{ \partial x^{2} }+\dfrac{ \partial^{2} f }{ \partial y } +\dfrac{ \partial^{2} f }{ \partial z }  \end{align}$$
	-  This object, which we write as $\nabla^{2}f$ for short, is called the [[Laplacian]] of $f$. The Laplacian of a scalar $f$ is a scalar.
	- The Laplacian of a [[Vector|vector]] , $\nabla^{2}\mathbf{F}$ means as a vector whose $x$-component is the Laplacian of $F_{x}$, and so on:$$\nabla^{2}\mathbf{F}=(\nabla^{2}F_{x})\ \hat{x}+(\nabla^{2}F_{y})\ \hat{y}+(\nabla^{2}F_{z})\ \hat{z}$$
1. The curl of a [[Gradient|gradient]] is always zero,$$\nabla \times(\nabla f)=\mathbf{0}$$
2. The gradient of the divergence, $$\nabla(\nabla\cdot \mathbf{F})$$ seldom occurs in physical applications.
3. The divergence of curl is always zero,$$\nabla\cdot(\nabla \times \mathbf{F})=0$$
4. The curl of a curl is,$$\nabla \times (\nabla \times \mathbf{F})=\nabla(\nabla\cdot F)-\nabla^{2}\mathbf{F}$$
	- This first term is just number $(3)$, and the second is the Laplacian of vector. 
	- This is often used to _define_ the Laplacian of a vector, in preference to the definition in number $(1)$, which makes explicit reference to the Cartesian coordinates.