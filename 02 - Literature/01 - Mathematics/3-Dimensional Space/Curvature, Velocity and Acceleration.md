---
tags:
  - 3D_Space
  - Mathematics
  - derivatives
  - Vector_Analysis
  - Physics
  - add_tags
---
# Curvature
- Curvature is the amount by which a curve deviates from being a [[Equation of Line#Equation of Line in 2-dimensions|straight line]] or by which a surface deviates from being a [[Equation of Plane|plane]].  
- For curvature of smooth curve we require $\vec{r}'(t)$ is [[Continuity|continuous]] and $\vec{r}'(t) \neq 0$.
- The formal definition of curvature is,$$
\kappa = \left\lvert  \frac{d\vec{T}}{ds}  \right\rvert $$where $\vec{T}$ is the [[Vector#Unit Vector|unit]] [[Tangent and Normal Vectors|tangent]] vector and $s$ is the arc length.
- Easier to use alternate forms are,$$
\kappa = \left\lvert  \frac{\overrightarrow{T}'(t)}{\vec{r}'(t)}  \right\rvert \hspace{1.0in} \kappa= \frac{{\lvert \vec{r}'(t)\times \vec{r}''(t) \rvert}}{\lvert \vec{r}'(t) \rvert^{3} }  $$where $\displaystyle \vec{T}={\frac{\vec{r}'(t)}{\lvert \vec{r}'(t) \rvert}}$
# Velocity and Acceleration 
- Suppose that the position of an object is given by the vector function $\vec{r}(t)$ then the velocity and acceleration of the object is given by,$$
\vec{v}(t)=\vec{r}'(t) \hspace{1.0in} \vec{a}(t)=\vec{r}''(t)$$
- The acceleration is composed of two components tangential component, $a_{T}$, and a normal  component , $a_{N}$. Hence acceleration can be written as,$$
	\vec{a}=a_{T}\vec{T}+a_{N}\vec{N}$$Where $\vec{T}$ and $\vec{N}$ are the [[Vector#Unit Vector|unit]] [[Tangent and Normal Vectors|tangent]] and unit [[ [[Tangent and Normal Vectors||normal]] vector respectively.
- If we define $v=\lvert\vec{v} (t)\rvert$ then the tangential and normal components of the acceleration are given by,$$
a_{T}=\dot{v}=\frac{{\vec{r}'(t)\cdot \vec{r}''(t)}}{\lvert \vec{r}'(t) \rvert } \hspace{0.25in} a_{n}=\kappa v^{2}=\frac{{\lvert \vec{r}'(t)\times \vec{r}''(t) \rvert }}{\lvert \vec{r}'(t) \rvert }$$
where $\kappa$ is the curvature for the position function.