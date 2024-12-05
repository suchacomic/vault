---
tags:
  - Calculus
  - derivatives
  - Physics
  - Vector_Analysis
---
#
- The Calculation of [[Derivatives|ordinary derivatives]] is facilitated by multiple rules, such as, 
	1. [[Derivatives#Product and Quotient Rule|Products and quotient rules]]. $$\begin{align}\dfrac{d}{dx}(f\,g) &= f\dfrac{dg}{dx} +g\dfrac{df}{dx} \\ \dfrac{d}{dx}\left( \dfrac{f}{g} \right) &= \dfrac{{g\dfrac{df}{dx} - f\dfrac{dg}{dx}}}{g^{2}} \\ \end{align} $$
	2. [[Derivatives#General Properties|constant multiplication and sum rules]],$$\begin{align} \frac{d}{dx}(f+g) &= \frac{df}{dx} +\frac{dg}{dx}, \\ \frac{d}{dx}(kf) &= k\frac{df}{dx}\end{align}$$
- Similar relations hold for the vector derivatives. Thus,$$\begin{align} \nabla(f+g) &=\nabla f+\nabla g \\
\nabla\cdot(\mathbf{A}+\mathbf{B}) &=(\nabla\cdot \mathbf{A})+(\nabla\cdot \mathbf{B}) \\
\nabla \times(\mathbf{A}+\mathbf{B}) &= (\nabla \times \mathbf{A})+(\nabla \times \mathbf{B}) \end{align}$$and,$$\nabla(kf)=k\,\nabla f,\hspace{0.25in} \nabla\cdot(kA)=k(\nabla\cdot \mathbf{A}),\hspace{0.25in} \nabla \times(k\mathbf{A})=k(\nabla \times \mathbf{A})$$
- There are six product rules two for gradient, divergence and curl each.

- The product rules for [[Gradient|gradient]] are,
	1. Product of two scalar,$$\displaystyle \nabla(f\,g)=f\,\nabla g+g\,\nabla f$$
	2. Product of two [[Vector|vectors]],$$\nabla(\mathbf{A}\cdot \mathbf{B})=\mathbf{A}\times(\nabla \times \mathbf{B})+\mathbf{B}\times(\nabla \times \mathbf{A})+(\mathbf{A}\cdot \nabla)\mathbf{B}+(B\cdot \nabla)\mathbf{A}$$
- The product rules for [[Divergence|divergence]] are,
	1. Product of a scalar and vector,$$\nabla\cdot (f\mathbf{A})=f(\nabla\cdot \mathbf{A})+\mathbf{A}\cdot(\nabla f)$$
	2. Cross product of two vectors,$$\nabla\cdot(\mathbf{A}\times \mathbf{B})=\mathbf{B}\cdot(\nabla \times \mathbf{A})-\mathbf{A}\cdot(\nabla \times \mathbf{B})$$
- The product rules for [[Curl|curl]] are,
	1. Product of a scalar and a vector,$$\nabla \times(f\mathbf{A})=f(\nabla \times \mathbf{A})-\mathbf{A}\times(\nabla f)$$
	2. Cross product of two vectors,$$\nabla \times(\mathbf{A}\times \mathbf{B})=(\mathbf{B}\cdot \nabla)\mathbf{A}-(\mathbf{A}\cdot \nabla)\mathbf{B}+\mathbf{A}(\nabla\cdot \mathbf{B})-\mathbf{B}(\nabla\cdot \mathbf{A})$$
