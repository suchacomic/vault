---
tags:
  - Mathematics
  - Calculus
  - Vector_Analysis
  - derivatives
aliases:
  - divergence
---
# Divergence
- From the [[Differential Operator|definition]] of $\nabla$ we construct the **divergence**,$$\begin{align}
\nabla\cdot \vec{F} &= \left( \hat{x}\,\frac{ \partial}{ \partial x }+\hat{y}\,\frac{ \partial  }{ \partial y } +\hat{z}\,\frac{ \partial  }{ \partial z }   \right)\cdot(F_{x}\,\hat{x}+F_{y}\,\hat{y}+F_{z}\,\hat{z}) \\
&= \frac{ \partial F_{x} }{ \partial x }+\frac{ \partial F_{y} }{ \partial y } +\frac{ \partial F_{z} }{ \partial z }  
\end{align}$$
- It is also sometimes denoted as,$$\mathrm{div}\vec{F}=\nabla\cdot \vec{F}$$
- A vector is called **solenoidal** if $\nabla\cdot \vec{F}=0$.
- The name divergence is well chosen, for $\nabla\cdot \vec{F}$ is a measure if how much the [[Vector|vector]] $\vec{F}$ spreads out (diverges) from the point in question.
- If $\vec{F}$ is the velocity [[Vector Fields|field]] of a flowing fluid then $\nabla\cdot \vec{F}$ represents the mass of the fluid flowing from the point $(x,y,z)$ per unit volume, that is, divergence measures change in density at a point.
- If a vector field has large positive divergence the point is called a **source** and all the arrows appear to originate from the point. Whereas if the vector field has a negative divergence the point is called a **sink** and all the arrows appear to move into the point.![[divergence.png]]
- Positive divergence increases the fluid density, negative divergence decreases the fluid density and the density remains constant for zero divergence.
- The divergence of a [[Curl|curl]] is always zero,$$\nabla\cdot(\nabla \times \vec{F})=0$$
# Divergence in Curvilinear Coordinated
- Divergence in a [[Orthogonal Curvilinear Coordinates|orthogonal curvilinear coordinates]] for a vector field $\vec{F}(u_{1},u_{2},u_{3})$, with the curvilinear [[basis]] vectors as $\hat{e}_{1},\hat{e}_{2}$ and $\hat{e}_{3}$ and scaling factors $h_{1},h_{2}$ and $h_{3}$ is given by,$$\mathrm{div}\vec{F}=\nabla\cdot \vec{F}=\dfrac{1}{h_{1}h_{2}h_{3}}\left\{ \frac{ \partial }{ \partial u_{1} }(F_{1}h_{2}h_{3})+\frac{ \partial }{ \partial u_{2} } (F_{2}h_{3}h_{1})+\frac{ \partial}{ \partial u_{3} }(F_{3}h_{1}h_{2}) \right\}$$
## Divergence in Spherical Coordinates
- For [[Spherical Coordinate System|spherical coordinates]], the vector field is $\vec{F}(r,\theta,\phi)$, with the basis vectors $\hat{r},\hat{\theta},\hat{\phi}$ and scaling factors $h_{1}=1,h_{2}=r,$ and $h_{3}=r\sin\theta$,$$\begin{align}\nabla\cdot \vec{F} &= \dfrac{1}{r^{2} \sin\theta}\left\{  \frac{ \partial }{ \partial r}(F_{r}\cdot r\cdot r\sin\theta) +\frac{ \partial}{ \partial \theta } (F_{\theta}\cdot r\sin\theta\cdot 1)+\frac{ \partial }{ \partial \phi }(F_{\phi}\cdot 1 \cdot r)   \right\} \\ \\
\nabla\cdot \vec{F}&= \dfrac{1}{r^{2}}\frac{ \partial}{ \partial r }(r^{2}\,F_{r})+ \dfrac{1}{r\sin\theta}\frac{ \partial  }{ \partial \theta } (\sin\theta\, F_{\theta})+\dfrac{1}{r\sin\theta}\frac{ \partial }{ \partial \phi }(F_{r}) 
\end{align}$$
## Divergence in Cylindrical Coordinate System
- For [[Cylindrical Coordinate System|cylindrical coordinates]], the  [[Vector Fields|vector field]] is $\vec{F}(s,\phi,z)$, with basis vectors $\hat{s},\hat{\phi},\hat{z}$ and scaling factors $h_{1}=1,h_{2}=s,h_{3}=1$,$$\begin{align} \nabla\cdot \vec{F} &= \dfrac{1}{s}\left\{  \frac{ \partial  }{ \partial s }(F_{s}\cdot s \cdot 1)+\frac{ \partial }{ \partial \phi } (F_{\phi}\cdot 1\cdot 1) +\frac{ \partial }{ \partial z }(F_{z}\cdot 1 \cdot s)   \right\} \\ \\ \nabla\cdot \vec{F} &= \dfrac{1}{s}\frac{ \partial}{ \partial s }(s\,F_{s})+\dfrac{1}{s}\frac{ \partial  }{ \partial \phi } (F_{\phi})+\frac{ \partial  }{ \partial z }(F_{z}) \end{align}$$
# See also

- [[Partial Derivatives]]
- [[Curl]]
- [[Divergence]]