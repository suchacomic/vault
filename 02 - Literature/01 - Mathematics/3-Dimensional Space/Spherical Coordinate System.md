---
tags:
  - 3D_Space
  - Mathematics
  - Vector_Analysis
cssclasses:
  - center-images
---
# Spherical Coordinate System
- Spherical coordinate system is a [[Orthogonal Curvilinear Coordinates|orthogonal curvilinear coordinate system]].
- The spherical coordinates $(u_{1},u_{2},u_{3})$ are,$$u_{1}=r,\,u_{2}=\theta\text{ and }u_{3}=\phi$$where,
	- $r$ is the distance from the origin, the magnitude of position vector $\vec{r}$.
	- $\theta$ is the angle down from the $z$-axis and is called the **polar angle**.
	- $\phi$ is the angle around from the $x$-axis and is called the **azimuthal angle**.
	and,$$\begin{align}
r &\in (-\infty ,\infty) \\
\theta & \in [0,\pi] \\
\phi & \in [0,2\pi]
\end{align}$$![[spherical.png]]
- Their relation to Cartesian coordinates are $$
x =r\sin\theta \cos \phi,\hspace{0.25in} y =r\sin\theta \sin \phi,\hspace{0.25in} z =r\cos\theta$$$$\vec{r}=r\sin\theta \cos \phi\, \hat{x}+r\sin\theta \sin \phi\, \hat{y}+r\cos\theta\, \hat{z}$$
- Inverse relation is,$$\begin{align}
r &= \sqrt{ x^{2}+y^{2}+z^{2} } \\
\theta &= \cos ^{-1}\left( \frac{z}{\sqrt{ x^{2}+y^{2}+z^{2} }} \right) = \cos ^{-1}\left( \frac{z}{r} \right)\\
\phi &= \tan ^{-1}\left( \frac{y}{x} \right)
\end{align}$$
- Calculating [[Orthogonal Curvilinear Coordinates#Unit Vectors and Scale Factor|scale factor]],$$h_{i}=\left\lvert  \frac{ \partial \vec{r} }{ \partial u_{i} }\right\rvert\hspace{0.25in}\&\hspace{0.25in} h_{1}\hat{e}_{1}=\frac{ \partial \vec{r} }{ \partial u_{i} } $$$$\begin{align}
\frac{ \partial \vec{r} }{ \partial r } &= \sin\theta \cos \phi\, \hat{x}+\sin\theta \sin \phi\, \hat{y}+\cos\theta\,\hat{z} \hspace{0.56in} \implies \hspace{0.2in}  \left\lvert  \frac{ \partial \vec{r} }{ \partial r }   \right\rvert =h_{r}=1 \\
\frac{ \partial \vec{r} }{ \partial \theta } &=r\cos\theta \cos \phi\, \hat{x}+r\cos\theta \sin \phi\,\hat{y}-r\sin\theta\, \hat{z} \hspace{0.2in}  \implies \hspace{0.2in} \left\lvert  \frac{ \partial \vec{r} }{ \partial \theta }   \right\rvert =h_{\theta} = r \\
\frac{ \partial \vec{r} }{ \partial \phi } &= -r\sin\theta \sin \phi\, \hat{x} + r\sin\theta \cos \phi\, \hat{y} \hspace{0.9in} \implies \hspace{0.2in}  \left\lvert  \frac{ \partial \vec{r} }{ \partial \phi }   \right\rvert =h_{\phi}=r\sin\theta
\end{align}$$
- Thus, $$\begin{align}\hat{r} =\hat{e}_{r} &= \sin\theta\cos \phi\,\hat{x}+\sin\theta \sin \phi\,\hat{y}+\cos\theta\,\hat{z} \\ \hat{\theta}=\hat{e}_{\theta} &= \cos\theta \sin \phi\,\hat{x}+\cos\theta \sin \phi\,\hat{y}-\sin\theta\,\hat{z} \\ \hat{\phi}=\hat{e}_{\phi}&=-\sin\phi \,\hat{x}+\cos\phi\,\hat{y}\end{align}$$These [[Vector#Unit Vector|unit vectors]] are normal to the level surfaces. That are,
	1. $r=$ constant $\implies$ spheres centered at origin, with unit normal $\hat{e}_{r}$.
	2. $\theta=$ constant $\implies$ cones of the semi-angle $\theta$ and axis along the $z$-axis with unit normal $\hat{e}_{\theta}$.
	3. $\phi =$ constant $\implies$ [[Equation of Plane|planes]] passing through the $z$-axis with unit normal vectors $\hat{e}_{\phi}$ .
- These surfaces are <u>not</u> all planes, but they do intersect at right angles.
# Summary of Transformations
- The [[Orthogonal Curvilinear Coordinates#Unit Vectors and Scale Factor|scaling factors]],$$h_{r}=1\hspace{0.5in} h_{\theta}=r \hspace{0.5in} h_{\phi}=r\sin\theta$$
- Cartesian coordinates,$$
\begin{align}
x &= r\sin\theta \cos \phi \\
y &=r\sin\theta \sin \phi \\
z &=r\cos\theta
\end{align}$$
- Unit vectors,$$
\begin{align}
\hat{r} &= \sin\theta \cos \phi\,\hat{x}+\sin\theta \sin \phi\, \hat{y}+\cos\theta\,\hat{z} \\
\hat{\theta} &= \cos\theta \cos \phi\,\hat{x}+\cos\theta \sin \phi\,\hat{y}-\sin\theta\,\hat{z} \\
\hat{\phi} &= -\sin\phi\,\hat{x}+\cos \phi\,\hat{y}
\end{align}$$
# Displacement Vector
- The [[Orthogonal Curvilinear Coordinates#Displacement Vector / Line Element|Displacement Vector]] (line element) is,$$
\begin{align}
d\vec{r} &= \sum_{i=1}^{3} h_{i}du_{i}\hat{e}_{i} \\
	&= (1)(dr)(\hat{r})+(r)(d\theta)(\hat{\theta})+(r\sin\theta)(d\phi)(\hat{\phi})
 \\ \\
d\vec{r} &= dr\,\hat{r}+rd\theta\, \hat\theta+r\sin\theta\, \hat{\phi}
\end{align}$$
# Arc Length
- From [[Orthogonal Curvilinear Coordinates#Arc Length| general orthogonal curvilinear coordinate result]],$$\begin{align}
(dl)^{2} &= h_{1}^{2}\,du_{1}^{2}+h_{2}^{2}\,du_{2}^{2}+h_{3}^{2}\,du_{3}^{2} \\
(dl)^{2} &=(1)^{2}(dr)^{2}+(r)^{2}(d\theta)^{2}+(r\sin\theta)^{2}(d\phi^{2}) \\ \\
dl&=\sqrt{ (dr)^{2}+r^{2}(d\theta)^{2}+r^{2}\sin\theta^{2}(d\phi)^{2}}

 \end{align}$$

# Surface Element
- The [[Orthogonal Curvilinear Coordinates#Vector Area / Surface Element|surface element]] is,$$\begin{align}

d\vec{S}_{1}=(d\vec{r}_{2})\times(d\vec{r}_{3}) &=(h_{2}\,du_{2}\,\hat{e}_{2})\times(h_{3}\,du_{3}\,\hat{e}_{3}) \\
&=(h_{2}\,du_{2})(h_{3}\,du_{3})(\hat{e}_{2}\times \hat{e}_{3}) \\
\vec{d}S_{r}&=(rd\theta)(r\sin\theta d\phi) \\
d\vec{S}_{r} &= r^{2}\sin\theta\,d\theta \,d\phi (d\hat{\theta}\times d\hat{\phi}) \\
 \\
d\vec{S}_{r}&=r^{2}\sin\theta \, d\theta \, d\phi\,d\vec{r}
\end{align}$$Similarly,$$\begin{align}
d\vec{S}_{\theta} &= (r\sin\theta \,d\phi)(dr)(d\vec{\phi}\times d\vec{r})=r\sin\theta \,dr\,d\phi \,d\hat{\theta} \\
	d\vec{S}_{\phi} &= (dr)(r\, d\theta)(d\vec{r}\times d\vec{\theta})= r\,dr\,d\theta\,d\hat{\phi}
\end{align}$$
# Volume Element
- The [[Orthogonal Curvilinear Coordinates#Volume Element|volume element]] is given by,$$
\begin{align}
dV &= h_{1}\,h_{2}\,h_{3}\,du_{1}\,du_{2}\,du_{3} \\
&=(1)(r)(r\sin\theta)(dr)(d\theta)(d\phi) \\ \\
dV &= r^{2}\sin\theta \,dr\,d\theta\,d\phi
\end{align}$$

## See also

- [[Cylindrical Coordinate System]]
- [[Vector Operations]]