---
tags:
  - 3D_Space
  - Vector_Analysis
  - Mathematics
  - Calculus
  - derivatives
cssclasses:
  - center-images
---
# Orthogonal Coordinate Systems 
- The coordinate systems for which their [[Vector#Unit Vector|unit vectors]] obey the relationship  $x_{i}x_{j}\delta_{ij}$, where $\delta$ is the [[Kronecker delta]]. In other worlds, the [[Vector Operations#Dot Product|dot product]] of any two vector in $0$ unless they are the same vector are called **orthogonal coordinate system**.
- Cartesian, cylindrical and polar are the most common example of orthogonal coordinate system which are only a subset if a large group of coordinate systems.
# Curvilinear Coordinates 
- Suppose we change from Cartesian coordinates $(x_{1},x_{2},x_{3})$  to curvilinear coordinates, which we denote $u_{i}$, each of which are functions of the $x_{i}$,$$
\begin{align}
u_{1} &= u_{1}(x_{1},x_{2},x_{3}) \\
u_{2} &= u_{2}(x_{1},x_{2},x_{3}) \\
u_{3} &= u_{3}(x_{1},x_{2},x_{3})
\end{align}$$where it is assumed that the correspondence is unique and that the inverse mapping exists.
- Reverse transformation is,$$
x_{i}=x_{i}(u_{1},u_{2},u_{3})$$A point may be referred to by its Cartesian coordinates $x_{i}$, or bu its curvilinear coordinates $u_{i}$.![[conformal map.png|247x480]]
- Now consider **coordinate surfaces** defined by keeping one coordinate constant.
	- The Cartesian coordinate surfaces ‘$x_{i}=$ constant’ are [[Equation of Plane|planes]], with constant [[Vector#Unit Vector|unit]] [[Tangent and Normal Vectors#Normal Vector|normal vectors]] $\hat{e}_{i}$ (or $\hat{e}_{1},\hat{e}_{2},\hat{e}_{3}$), intersecting at right angles.
	- The surfaces ‘$u_{i}=$ constant’ <u>do not</u>, in general, have constant unit normal vectors, nor in general they intersect at right angles.
	![[constant surfaces curviliinear.png]]
## Unit Vectors and Scale Factor 
- Suppose that point $P$ has position $\vec{r}=\vec{r}(u_{1},u_{2},u_{3})$. If we change $u_{1}$ by a small amount, $du_{1}$, then $\vec{r}$ moves to position $(\vec{r}+\vec{dr})$,$$ 
		\vec{dr}=\frac{ \partial \vec{r} }{ \partial u_{1} }\ du_{1} \equiv h_{1}\hat{e}_{1}\ du_{1}$$$$\vec{dr}=\sum_{i=1}^{3} \frac{ \vec{\partial}r }{ \partial u_{i} } \,du_{i}$$where we define the [[Vector#Unit Vector|unit vector]] $\hat{e_{i}}$ and the **scale factor** $h_{1}$ by $$h_{1}=\left\lvert  \frac{ \vec{\partial}r }{ \partial u_{1} }   \right\rvert \hspace{0.25in} \text{ and } \hspace{0.25in} \hat{e}_{1}=\frac{1}{h_{1}}\ \frac{ \vec{\partial}r }{ \partial u_{1} }$$ similarly, 
$${\displaystyle h_{i}={\sqrt {\left({\frac {\partial x_{1}}{\partial u_{i}}}\right)^{2}+\left({\frac {\partial x_{2}}{\partial u_{i}}}\right)^{2}+\left({\frac {\partial x_{3}}{\partial u_{i}}}\right)^{2}}}}$$
- The vector $\hat{e_{1}}$ is a unit vector in the *direction of increasing* $u_{1}$.
- The **scale factor** $h_{1}$ gives the [[Vector#Magnitude of A Vector|magnitude]] of $\vec{dr}$ when we make the change $u_{1}\to u_{1}+du_{1}$. That is what is the change in position vector in the Cartesian coordinate when we make a infinitesimally small change in the vector in the curvilinear coordinate system .
- Thus for an infinitesimal change of $u_{1}$, the change in $\vec{r}$ is,$$
|\vec{dr}|=h_{1}\,du_{1}$$similarly, we can define $h_{i}$ and $\hat{e_{i}}$. 
- The unit vectors $\hat{e_{i}}$ are <u>not constant vectors</u>. In general they are non-Cartesian [[basis]] vectors, they depend on the position vector $|\vec{r}|$, *i.e.* their directions change as the $u_{i}$ are varied.
- If $\hat{e}_{i}\cdot \hat{e}_{j}=\delta_{ij}$, then the $u_{i}$ are **orthogonal curvilinear coordinates**.
- For Cartesian coordinates, the scale factors are unity and the unit vector $\hat{e}_{i}$ reduce to the Cartesian [[basis]] vectors we know,$$
\vec{r}=x\, \hat{e}_{1}+y\, \hat{e}_{2}+z\, \hat{e}_{3}$$so that the scale factor becomes,$$
\begin{align}
	h_{1} &= \frac{1}{\hat{e}_{1}} \frac{ \partial \vec{r} }{ \partial x }  \\
&= \frac{1}{\hat{e}_{1}}\,\hat{e}_{1} = 1
\end{align}$$
# Displacement Vector / Line Element
- The general line element $d\vec{r}$ in curvilinear coordinates is give by [[Partial Derivatives#Chain Rule|chain rule]]. If we change all three coordinates $u_{i}$ by infinitesimal amounts $du_{i}$, then we have $$\begin{align}
\vec{dr} &= \frac{ \partial \vec{r} }{ \partial u_{1} }\,du_{1}+\frac{ \partial \vec{r} }{ \partial u_{2} }\, du_{2} + \frac{ \partial \vec{r} }{ \partial u_{3} } \, du_{3} = \sum_{i=1}^{3} \frac{ \vec{\partial}r }{ \partial u_{i} } \,du_{i} \\
&= h_{1}\,du_{1}\,\hat{e}_{1}+h_{2}\,du_{2}\,\hat{e}_{2}+h_{3}\,du_{3}\,\hat{e}_{3} = \sum_{i=1}^{3} h_{i}du_{i}\hat{e}_{i}
\end{align}$$as stated previously.
 
# Arc Length 
- The [[Differentials|differential]] of  [[Arc Length|arc length]] $ds$ is the length of the infinitesimal vector $\vec{dr}$,$$
(dl)^{2}=\vec{dr}\cdot \vec{dr}$$In Cartesian coordinates $$
(dl)^{2}=(dx)^{2}+(dy)^{2}+(dz)^{2}$$
- For the case of orthogonal curvilinear, because the basis vectors are orthogonal ($\hat{e}_{i}^{2}=1$) we have$$(dl)^{2}=h_{1}^{2}\,du_{1}^{2}+h_{2}^{2}\,du_{2}^{2}+h_{3}^{2}\,du_{3}^{2}$$
# Vector Area / Surface Element
- On the surface of constant $u_{1}$ the **vector area** bounded by $d\vec{r}_{2}=h_{2}du_{2}\hat{e}_{2}$ and $d\vec{r}_{3}=h_{3}du_{3}\hat{e}_{3}$,$$\begin{align}

d\vec{S}_{1}=(d\vec{r}_{2})\times(d\vec{r}_{3}) &=(h_{2}\,du_{2}\,\hat{e}_{2})\times(h_{3}\,du_{3}\,\hat{e}_{3}) \\
&=h_{2}\,h_{3}\,du_{2}\,du_{3}\,\hat{e}_{1}
\end{align}$$because $\hat{e}_{2}\times \hat{e}_{3}=\hat{e}_{1}$
# Volume Element 
- The volume contained in the parallelepiped with edges $d\vec{r}_{1},d\vec{r}_{2}$ and $d\vec{r}_{3}$, is $$\begin{align}
dV &= d\vec{r}_{1}\cdot d\vec{r}_{2}\times d\vec{r}_{3} \\
&= (h_{1}\,du_{1}\,\hat{e}_{1})\cdot(h_{1}\,du_{2}\,\hat{e}_{2})\times(h_{3}\,du_{3}\,\hat{e}_{3}) \\
&= h_{1}\,h_{2}\,h_{3}\,du_{1}\,du_{2}\,du_{3}
\end{align}$$because $\hat{e}_{1}*\hat{e}_{2}\times \hat{e}_{3}=1$
- By [[Vector Products#Scalar Triple Products|scalar triple product]] we can generalize the [[Change of Variable|change of variables]] to any coordinates,$$dV=\begin{vmatrix}		\dfrac{ \partial x }{ \partial u_{1}} & \dfrac{ \partial x }{ \partial u_{2} }  & \dfrac{ \partial x }{ \partial u_{3} } \\\dfrac{ \partial y }{ \partial u_{1}} & \dfrac{ \partial y }{ \partial u_{2} }  & \dfrac{ \partial y }{ \partial u_{3} } \\\dfrac{ \partial y }{ \partial u_{1}} & \dfrac{ \partial x }{ \partial u_{2} }  & \dfrac{ \partial y }{ \partial u_{3} } \\ \end{vmatrix}\, du_{1}\,du_{2}\,du_{3}$$ this is nothing but the [[Jacobian]] often denoted by,$$\frac{ \partial (x,y,z) }{ \partial (u_{1},u_{2},u_{3}) } $$
## See also

- [[Spherical Coordinate System]]
- [[Vector Products]]
- [[Vector Operations]]