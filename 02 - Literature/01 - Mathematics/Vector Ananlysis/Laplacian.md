---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Laplacian
- The **Laplace operator** of **Laplacian** is a [[Differential Operator|differential operator]] given by the [[Divergence|divergence]] of the [[Gradient|gradient]] of a scalar function. 
- Usually denoted by the symbols $\nabla\cdot \nabla$ or $\nabla^{2}$.
- The Laplacian of a function $f$ at a point $p$ measures by how much the average value of $f$ over small spheres centered at $p$ deviates from $f(p)$. 
- The solutions of Laplace's equation, $\nabla^{2}f=0$ are called harmonic functions.
- In Cartesian coordinates, $$\nabla^{2}f=\dfrac{ \partial^{2} f }{ \partial x^{2} }+\dfrac{ \partial^{2} f }{ \partial y } +\dfrac{ \partial^{2} f }{ \partial z }$$
- The Laplacian of a [[Vector|vector]] , $\nabla^{2}\mathbf{F}$ means as a vector whose $x$-component is the Laplacian of $F_{x}$, and so on:$$\nabla^{2}\mathbf{F}=(\nabla^{2}F_{x})\ \hat{x}+(\nabla^{2}F_{y})\ \hat{y}+(\nabla^{2}F_{z})\ \hat{z}$$
- Alternatively from the [[Second Order Derivative in Multiple Variables|curl of a curl]] the Laplacian independent of coordinate system can be defined as,$$\nabla^{2}\mathbf{F}=\nabla(\nabla\cdot \mathbf{F})-\nabla \times(\nabla \times \mathbf{F})$$
# Laplacian in Curvilinear Coordinates
- Laplacian in a [[Orthogonal Curvilinear Coordinates|orthogonal curvilinear coordinates]] for a scalar field $f(u_{1},u_{2},u_{3})$, with the curvilinear [[basis]] vectors as $\hat{e}_{1},\hat{e}_{2}$ and $\hat{e}_{3}$ and scaling factors $h_{1},h_{2}$ and $h_{3}$ is given by, $$\nabla^{2}f=\frac{1}{h_{1}h_{2}h_{3}}\left\{ \dfrac{ \partial }{ \partial u_{1}}\left( \frac{h_{2}h_{3}}{h_{1}}\dfrac{ \partial f }{ \partial u_{1} } \right)+ \dfrac{ \partial  }{ \partial u_{2} } \left( \frac{h_{3}h_{1}}{h_{2}}\dfrac{ \partial f }{ \partial u_{2} } \right) +\dfrac{ \partial  }{ \partial u_{3} } \left( \frac{h_{1}h_{2}}{h_{3}}\dfrac{ \partial f }{ \partial u_{3} }  \right) \right\} $$
## Laplacian in Spherical Coordinates
- For [[Spherical Coordinate System|spherical coordinates]], the scalar field is $f(r,\theta,\phi)$, with the basis vectors $\hat{r},\hat{\theta},\hat{\phi}$ and scaling factors $h_{1}=1,h_{2}=r,$ and $h_{3}=r\sin\theta$,$$\begin{align} \nabla^{2}f\,(r,\theta,\phi) &=\frac{1}{ r^{2}\sin\theta} \left\{ \dfrac{ \partial }{ \partial r}\left( {r^{2}}\dfrac{ \partial f }{ \partial r } \right)+ \dfrac{ \partial  }{ \partial \theta } \left(\sin\theta \dfrac{ \partial f }{ \partial \theta} \right) +\dfrac{ \partial  }{ \partial \phi} \left( \frac{1}{\sin\theta}\dfrac{ \partial f }{ \partial \phi }  \right) \right\} \\ &= \frac{1}{r^{2}}\dfrac{ \partial  }{ \partial r } \left( r^{2}\frac{ \partial f }{ \partial r }  \right) + \frac{1}{r^{2}\sin\theta} \frac{ \partial }{ \partial \theta } \left( \sin\theta \frac{ \partial f }{ \partial \theta }  \right) + \frac{1}{r^{2}\sin^{2}\theta} \left( \frac{ \partial^{2} f }{ \partial \phi^{2} }\right)\end{align}$$
## Laplacian in Cylindrical Coordinates
- For [[Cylindrical Coordinate System|cylindrical coordinates]], the scalar field is $f(s,\phi,z)$, with basis vectors $\hat{s},\hat{\phi},\hat{z}$ and scaling factors $h_{1}=1,h_{2}=s,h_{3}=1$,$$\begin{align} \nabla^{2}f(s,\phi,z) &= \frac{1}{s} \left\{ \dfrac{ \partial }{ \partial s }\left(s \dfrac{ \partial f }{ \partial s }  \right)+\dfrac{ \partial  }{ \partial \phi }\left( \frac{1}{s} \dfrac{ \partial f }{ \partial \phi } \right) +\dfrac{ \partial  }{ \partial z }\left( s \dfrac{ \partial f }{ \partial z } \right) \right\} \\ &= \frac{1}{s} \dfrac{ \partial }{ \partial s } \left(s\dfrac{\partial f }{ \partial s } \right)  +\frac{1}{s^{2}} \dfrac{ \partial^{2} f }{ \partial \phi^{2} } + \dfrac{ \partial^{2} f }{ \partial z^{2} }  \end{align}$$
# See also

- [[Curl]]
- [[Divergence]]
- [[Partial Derivatives]]