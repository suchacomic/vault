---
aliases:
  - curl
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Curl
- From the [[Differential Operator|definition]] of $\nabla$ we construct curl:$$\nabla \times \vec{F}=\begin{vmatrix} 
\hat{x} & \hat{y} & \hat{z} \\
\dfrac{ \partial  }{ \partial x } & \dfrac{ \partial  }{ \partial y } & \dfrac{ \partial  }{ \partial z } \\
F_{x} & F_{y} & F_{z}
\end{vmatrix}$$
- The curl of a [[Vector Fields|vector field]] is a measure of how much the [[Vector|vectors]] swirl around the point in question.
- The direction of the swirl determines if the curl is positive or negative, as the [[Right-Hand Rule|right-hand rule]]  suggests.
- Just as [[Gradient|gradient]] points in the direction of “steepest” ascend, curl “points” in the “direction of greatest rotation”.
- If curl of a vector is zero, that is $\nabla \times \vec{F}=\vec{0}$, the vector field is called **irrotational**.
- The if $f(x,y,z)$ ha [[Continuity|continuous]] second order [[Partial Derivatives|partial derivatives]] then  then curl of [[Gradient]] is zero,$$\nabla \times(\nabla f) =\mathbf{0}$$
- The divergence of a curl, like the curl of a gradient, is zero,$$\nabla\cdot(\nabla \times \vec{F})=0$$
# Curl in Curvilinear Coordinates
- Curl in a [[Orthogonal Curvilinear Coordinates|orthogonal curvilinear coordinates]] for a [[Vector Fields|vector field]] is $\vec{F}(u_{1},u_{2},u_{3})$, with the curvilinear [[basis]] vectors as $\hat{e}_{1},\hat{e}_{2}$ and $\hat{e}_{3}$ and scaling factors $h_{1},h_{2}$ and $h_{3}$ is given by,
$$\nabla \times \vec{F}=\dfrac{1}{h_{1}h_{2}h_{3}}\begin{vmatrix}
h_{1}\hat{e}_{1} & h_{2}\hat{e}_{2} & h_{3}\hat{e}_{3} \\
\dfrac{ \partial  }{ \partial u_{1} }  & \dfrac{ \partial  }{ \partial u_{2} }  & \dfrac{ \partial  }{ \partial u_{3} } \\
h_{1}F_{1}  & h_{2}F_{2} & h_{3}F_{3}
\end{vmatrix}$$
$${\displaystyle {\begin{aligned}&(\operatorname {curl} \mathbf {F} )_{1}={\frac {1}{h_{2}h_{3}}}\left({\frac {\partial (h_{3}F_{3})}{\partial u_{2}}}-{\frac {\partial (h_{2}F_{2})}{\partial u_{3}}}\right),\\[5pt]&(\operatorname {curl} \mathbf {F} )_{2}={\frac {1}{h_{3}h_{1}}}\left({\frac {\partial (h_{1}F_{1})}{\partial u_{3}}}-{\frac {\partial (h_{3}F_{3})}{\partial u_{1}}}\right),\\[5pt]&(\operatorname {curl} \mathbf {F} )_{3}={\frac {1}{h_{1}h_{2}}}\left({\frac {\partial (h_{2}F_{2})}{\partial u_{1}}}-{\frac {\partial (h_{1}F_{1})}{\partial u_{2}}}\right).\end{aligned}}}$$
- The equation for each component can be obtained by exchanging each occurrence of a subscript 1, 2, 3 in cyclic permutation:1->2, 2->3, 3->1 

## Gradient in Spherical Coordinates
- For [[Spherical Coordinate System|spherical coordinates]], the  [[Vector Fields|vector field]] is $\vec{F}(r,\theta,\phi)$, with the basis vectors $\hat{r},\hat{\theta},\hat{\phi}$ and scaling factors $h_{1}=1,h_{2}=r,$ and $h_{3}=r\sin\theta$, $$\nabla \times \vec{F}=\dfrac{1}{r^{2}\sin\theta}\begin{vmatrix}
(1) \cdot \hat{r} & (r)\cdot \hat{\theta} & (r\sin\theta) \cdot \hat{\phi} \\ \dfrac{ \partial  }{ \partial r }  & \dfrac{ \partial  }{ \partial \theta }  & \dfrac{ \partial  }{ \partial \phi }  \\ (1)\cdot F_{r} & (r)\cdot F_{\theta} & (r\sin\theta)\cdot F\phi
\end{vmatrix}$$
$$\nabla \times \vec{F}=\dfrac{1}{r^{2}\sin\theta}\begin{vmatrix}
\hat{r} & r\,\hat{\theta} & r\sin\theta \, \hat{\phi} \\ \dfrac{ \partial  }{ \partial r }  & \dfrac{ \partial  }{ \partial \theta }  & \dfrac{ \partial  }{ \partial \phi }  \\ F_{r} & r\, F_{\theta} & r\sin\theta\, F\phi
\end{vmatrix}$$
## Gradient in Cylindrical Coordinates
-  For [[Cylindrical Coordinate System|cylindrical coordinates]], the  [[Vector Fields|vector field]] is $\vec{F}(s,\phi,z)$, with basis vectors $\hat{s},\hat{\phi},\hat{z}$ and scaling factors $h_{1}=1,h_{2}=s,h_{3}=1$,$$\nabla\cdot \vec{F}=\frac{1}{s}\,\begin{vmatrix} \hat{s} & s\hat{\phi}  & \hat{z} \\ \dfrac{ \partial  }{ \partial s }  & \dfrac{ \partial  }{ \partial \phi } & \dfrac{ \partial  }{ \partial z }  \\
F_{r} & s\,F_{\phi} & F_{z} \end{vmatrix}$$
# See also

- [[Gradient]]
- [[Divergence]]
- [[Partial Derivatives]]