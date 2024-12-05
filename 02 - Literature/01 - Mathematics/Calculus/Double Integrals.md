---
tags:
  - Calculus
  - integration
  - Mathematics
  - 3D_Space
aliases:
  - surface integral
cssclasses:
  - center-images
---
# Analog to Definite Integral in One Variable
- The [[Area Under the Curve|area under the curve]] for a function of single variable in $\mathbb{R}$ when the number of sub-intervals in Riemann sum goes to infinity gives us the definition of [[Integrals|integration]],$$
\int_{a}^{b} f(x) \, dx = \lim_{ n \to \infty } \sum_{i=1}^{n} f(x_{i}^*)\Delta x 
$$
- With functions of one variable we integrated over an interval i.e. a one-dimensional space and so it makes sense that when integrating a function of two variables over a region of $\mathbb{R}^2$ (two-dimensional space).
# Double Integral 
- Also known as surface integrals.
- We start by assuming that the region in $\mathbb{R}^{2}$ is a rectangle which we will denote as follows,$$
R = [a,b]\times{c,d}
$$
- For $f(x,y)\geq 0$ we get the graph of the surface $S$, 
	![[area under surface.png]]
- We now approximate the volume as we approximate for one-dimensional problem by dividing up $a\leq x\leq b$ into $n$ sub-intervals and $c\leq y\leq d$ into $m$ sub-intervals.
- This will divide $u$ $R$ into a series of smaller rectangles and from each of these we will choose a point $(x_{i}^*,y_{j}^*)$ and then construct a box whose height is given by $f(x_{i}^*,y_{j}^*)$.
	![[double integral.png]]
- Each of the rectangles has a base area $\Delta A$ and height of $f(x_{i}^*,y_{j}^*)$ so the volume under the surface $S$ is approximately,$$
V \approx \sum_{i=1}^{n} \sum_{i=1}^{m} f(x_{i}^*,y_{j}^*)\Delta A
$$
- To get a exact volume we take the [[Limits|limit]] as both $n$ and $m$ goes to infinity,$$
\begin{align}
V &= \lim_{ n,m \to \infty } \sum_{i=1}^{n} \sum_{i=1}^{m} f(x_{i}^*,y_{j}^*)\Delta A \\ &= \iint\limits_{R}f(x,y)\, \mathrm{d}A
\end{align}
$$
- Thus we get the definition of a double integral, $${V =\iint\limits_{R}f(x,y)\, \mathrm{d}A}$$
- For some [[Vector Functions|vector function]] $\vec{v}$, the integral is specified over a region $\mathcal{S}$ , and an $d\vec{a}$ is an infinitesimal patch of area that is orthogonal to the surface $\mathcal{S}$, $$flux=\iint\limits_{ \mathcal{S} }\vec{v}\cdot d\vec{a}$$
# Double Integrals Over General Regions
- **Case 1:** $$D=\{ x,y\,|\,a\leq x\leq b,\,g_{1}(x)\leq y\leq g_{2}(x)\}$$![[D int over region case 1.png]]$$\iint\limits_{D}f(x,y)=\int_{a}^{b} \int_{g_{1}(x)}^{g_{2}(x)} f(x,y) \, dy  \, dx $$
- **Case 2:** $$
D=\{ x,y\,|\,h_{1}(y) \leq x\leq h_{2}(y),\,c\leq y\leq d \}$$![[D int over general region case 2.png]]$$\iint\limits_{D}f(x,y)=\int_{a}^{b} \int_{h_{1}(y)}^{h_{2}(y)} f(x,y) \, dx  \, dy $$
- If the region $D$ can be split into two separate regions $D_{1}$ and $D_{2}$ then the integral can be written as,$$\iint\limits_{D}f(x,y)\,dA=\iint\limits_{D_{1}}f(x,y)\,dA+\iint\limits_{D_{2}}f(x,y)\,dA$$ 
# Double Integrals in Polar Coordinates 
- For [[Spherical Coordinate System|polar]] [[Orthogonal Curvilinear Coordinates|curvilinear]] coordinates the area element can be written as,$$dA=(h_{1}du_{1})(h_{2}du_{2})=r \,dr\, d\theta$$with $x=r\cos\theta$ and $y=r\sin\theta$.
- Our general region will be define by inequalities $$\alpha\leq\theta\leq\beta ,\hspace{0.5in}  h_{1}(\theta)\leq r\leq h_{2}(\theta)$$ ![[polar D int.png]]
$$\iint\limits_{D}f(x,y)\,dA=\int_{\alpha}^{\beta} \int_{h_{1}(\theta)}^{h_{2}(\theta)} f(r\cos\theta,r\sin\theta)\,r \, dr  \, d\theta $$
- [[Change of Variable|Change of variables]] to any arbitrary coordinate system can be done by employing a [[Jacobian]] as,$$dA=\frac{ \partial (x,y,x) }{ \partial (u,v,w) } $$  

## See also
- [[Iterated Integrals]]
- [[Triple Integrals]]