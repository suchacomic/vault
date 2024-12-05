---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
  - 3D_Space
---
# Gradient
- Gradient is the change in a scalar field $f$ when we let $\vec{r}\to \vec{r}+d\vec{r}$.
- The Gradient vector $\nabla f(x_{0},y_{0},z_{0})$ is orthogonal to the [[Vector Fields#Contour Lines|level curve]] $f(x,y)=k$ at the point $(x_{0},y_{0},z_{0})$.

- The gradient of $f$ or the gradient vector of $f$ is defined as, $$\nabla f=\langle f_{x},f_{y},f_{z} \rangle$$
Or, $$
\nabla f=f_{x}\ \hat{x}+f_{y}\ \hat{y}+f_{z}\ \hat{x}$$
# Gradient in Cartesian Coordinates
- Suppose we have a function of three variables say $f(x,y,z)$, then the [[Partial Derivatives#Chain Rule|theorem of partial derivatives ]]states that,$$df=\left( \frac{ \partial f }{ \partial x }  \right)\,dx+\left( \frac{ \partial f }{ \partial y }  \right)\,dy+\left( \frac{ \partial f }{ \partial z }  \right)\,dz$$This is reminiscent of a dot product,$$\begin{align}
df &= \left\langle  \frac{ \partial f }{ \partial x } \,\hat{x} +\frac{ \partial f }{ \partial y } \,\hat{y}+\frac{ \partial f }{ \partial z } \,\hat{z} \right\rangle \cdot \langle dx\,\hat{x}+ dy\,\hat{y}+dz\,\hat{z}\rangle \\
&= (\nabla f)\cdot d\vec{l}
\end{align}$$Where,$$\nabla f=\frac{ \partial f }{ \partial x }\,\hat{x}+\frac{ \partial f }{ \partial y } \,\hat{y}+\frac{ \partial f }{ \partial z } \,\hat{z} $$
- Gradient of the function $f$ is a vector that points in the direction of maximum increase of the function $f$  ( *steepest ascend* ).
- The magnitude $\lvert \nabla f \rvert$ gives the slope ( [[Rate of Change and Tangent Line|rate of increase]] ) along this maximal direction.
- The vector $\nabla f$ is perpendicular to the surface $f=$ constant
- The gradient of a scalar field gives us a [[Vector Fields|vector field]] called the **gradient vector field**.
- The [[Curl|curl]] of a gradient is always zero,$$\nabla \times(\nabla f)=\mathbf{0}$$
# Gradient in a General Curvilinear Coordinates
- Gradient in a [[Orthogonal Curvilinear Coordinates|orthogonal curvilinear coordinates]] for a scalar field $f(u_{1},u_{2},u_{3})$, with the curvilinear [[basis]] vectors as $\hat{e}_{1},\hat{e}_{2}$ and $\hat{e}_{3}$ and scaling factors $h_{1},h_{2}$ and $h_{3}$ is given by,$$\nabla f=\frac{1}{h_{1}}\frac{ \partial f }{ \partial u_{1} }+\frac{{1}}{h_{2}}\frac{ \partial f }{ \partial u_{2} }\hat{e}_{2} +\frac{1}{h_{3}}\frac{ \partial f }{ \partial u_{3} }\hat{e}_{3}$$
## Gradient in Spherical Coordinates
- For [[Spherical Coordinate System|spherical coordinates]], the scalar field is $f(r,\theta,\phi)$, with the basis vectors $\hat{r},\hat{\theta},\hat{\phi}$ and scaling factors $h_{1}=1,h_{2}=r,$ and $h_{3}=r\sin\theta$, $$\nabla f(r,\theta ,\phi)=\frac{ \partial f }{ \partial r } \hat{r}+\frac{1}{r}\frac{ \partial f }{ \partial \theta }\hat{\theta} +\frac{1}{r\sin\theta}\frac{ \partial f }{ \partial \phi } \hat{\phi}$$
## Gradient in Cylindrical Coordinates
- For [[Cylindrical Coordinate System|cylindrical coordinates]], the scalar field is $f(s,\phi,z)$, with basis vectors $\hat{s},\hat{\phi},\hat{z}$ and scaling factors $h_{1}=1,h_{2}=s,h_{3}=1$,$$
\nabla f(s,\phi,z)= \frac{ \partial f }{ \partial s } \hat{s}+\frac{1}{s} \frac{ \partial f }{ \partial \phi } \hat{\phi}+\frac{ \partial f }{ \partial z } \hat{z}$$
## See also

- [[Directional Derivatives]]
- [[Partial Derivatives]]
- [[Differential Operator]]
- [[Divergence]]
- [[Curl]]