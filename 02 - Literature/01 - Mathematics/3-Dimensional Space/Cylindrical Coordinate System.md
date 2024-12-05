---
tags:
  - 3D_Space
  - Mathematics
  - Vector_Analysis
cssclasses:
  - center-images
---
# Cylindrical Coordinate System
 - Cylindrical coordinate system is a [[Orthogonal Curvilinear Coordinates|orthogonal curvilinear coordinate system]].
 - The spherical coordinates $(u_{1},u_{2},u_{3})$ are,$$u_{1}=s,\,u_{2}=\phi\text{ and }u_{3}=z$$where,
	 - $s$ is the distance from the $z$-axis
	 - $\phi$ is the angle around from the $x$-axis and is called the **azimuthal angle**.
	 - $z$ is the same as Cartesian $z$.
	 and,$$\begin{align}
s &\in(-\infty,\infty) \\
\phi &\in[0,2\pi] \\
z &\in(-\infty,\infty)
\end{align}$$![[cylindrical coordinates.png]]
- Their relation to Cartesian coordinates are,$$
x=s\cos \phi,\hspace{0.25in} y=\,\sin \phi,\hspace{0.25in} z=z$$$$\vec{r}=s\cos \phi \,\hat{x}+\,\sin \phi\,\hat{y}+z\,\hat{z}$$
- Inverse relations are,$$\begin{align}s &=\sqrt{ x^{2}+y^{2} } \\
\phi &= \tan^{-1}\left( \frac{y}{x} \right)  \\
z &= z\end{align}$$
- Calculating [[Orthogonal Curvilinear Coordinates#Unit Vectors and Scale Factor|scale factor]], $$h_{i}=\left\lvert  \frac{ \partial \vec{r} }{ \partial u_{i} }\right\rvert\hspace{0.25in}\&\hspace{0.25in} h_{1}\hat{e}_{1}=\frac{ \partial \vec{r} }{ \partial u_{i}}$$$$\begin{align}\frac{ \partial \vec{r} }{ \partial s } &=\cos \phi \,\hat{x}+ \sin \phi \,\hat{y} \\ \frac{ \partial \vec{r} }{ \partial \phi } &= -s\sin\phi \,\hat{x}+s\cos \phi \,\hat{y} \\ \frac{ \partial \vec{r} }{ \partial z } &=\hat{z} \end{align}$$Thus, $$\begin{align}h_{s} = \left\lvert  \frac{\partial \vec{r} }{ \partial s }\right\rvert=1,\hspace{0.25in} h_{\phi}=\left\lvert  \frac{ \partial \vec{r} }{ \partial \phi }\right\rvert =s\hspace{0.25in} h_{z} = \left\lvert \frac{ \partial \vec{r} }{ \partial z } \right\rvert =1 \end{align}$$  Therefore by $\displaystyle \hat{e}_{i}=\frac{ \partial \vec{r} }{ \partial u_{i} } \frac{1}{h_{i}}$,$$\begin{align}\hat{s}=\hat{e}_{s}&=\cos \phi \,\hat{x}+\sin \phi \,\hat{j} \\ \hat{\phi}=\hat{e}_{\phi} &=-\sin \phi \,\hat{x}+\cos \phi \,\hat{y} \\ \hat{z}=\hat{e}_{z} &= \hat{z} \end{align}$$ These [[Vector#Unit Vector|unit vectors]] are normal to the level surfaces. That are,
	1. $s=$ constant $\implies$ Cylinders at a radius $s$ 
	2. $\phi=$ constant $\implies$ [[Equation of Plane|Planes]] passing through the $z$-axis
	3. $z=$ constant $\implies$ Planes parallel to the $xy$-plane 
# Displacement Vector
- The [[Orthogonal Curvilinear Coordinates#Displacement Vector / Line Element|Displacement Vector]] (line element) is, $$\begin{align}
d\vec{r} &= \sum_{i=1}^{3} h_{i}du_{i}\hat{e}_{i} \\
&= (1)(ds)(\hat{s})+(s)(d\phi)(\hat{\phi})+(1)(dz)(\hat{z}) \\ \\
d\vec{r} &= ds\,\hat{s}+s \,d\phi \,\hat{\phi}+dz\,\hat{z}
\end{align}
$$
# Arc Length
- Arc length is given by,$$\begin{align}
(dl)^{2}&=d\vec{r}\cdot d\vec{r} \\
(dl)^{2}&=\sum_{i=1}^{3} (h_{i}du_{i}\hat{e}_{i})^{2} \\ \\ dl&=\sqrt{(ds)^{2}+s^{2}\,(d\phi)^{2}+(dz)^{2} }
\end{align}$$
# Surface Element
- - The [[Orthogonal Curvilinear Coordinates#Vector Area / Surface Element|surface element]] is,$$\begin{align}

d\vec{S}_{1}=(d\vec{r}_{2})\times(d\vec{r}_{3}) &=(h_{2}\,du_{2}\,\hat{e}_{2})\times(h_{3}\,du_{3}\,\hat{e}_{3}) \\
&=(h_{2}\,du_{2})(h_{3}\,du_{3})(\hat{e}_{2}\times \hat{e}_{3}) \\
d\vec{S}_{s}&=(sd\phi)(dz)(\hat{\phi}\times \hat{z}) \\
d\vec{S}_{r}&=s\,d\phi\,dz \,\vec{s}
\end{align}$$Similarly, $$
\begin{align}
d\vec{S}_{\phi} &= ds \,dz \,\hat{\phi} \\
d\vec{S}_{z}&=s \,ds \,d\phi \,\hat{z}
\end{align}$$
# Volume Element
 The [[Orthogonal Curvilinear Coordinates#Volume Element|volume element]] is given by,$$
\begin{align}
dV &= h_{1}\,h_{2}\,h_{3}\,du_{1}\,du_{2}\,du_{3} \\
&=(1)(s)(1)(ds)(d\phi)(dz) \\ \\
dV &= s \,ds\,d\phi\, dz
\end{align}$$
## See also

- [[Spherical Coordinate System]]
- [[Vector Operations]]