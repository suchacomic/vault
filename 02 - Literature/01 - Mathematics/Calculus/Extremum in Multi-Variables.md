---
tags:
  - Calculus
  - derivatives
  - Mathematics
cssclasses:
  - center-images
---
# Critical Points
- The point $(a,b)$ is a **critical point** or a [[Extremum in one Variable#Stationary Points|stationary point]] of $f(x,y)$ provided one of the following is true,
	1. $\displaystyle \nabla f(a,b)=\vec{0}$ (that is equivalent to $f_{x}(a,b)=0$ and $f_{y}(a,b)=0$),
	2. $f_{x}(a,b)$ and/or $f_{y}(a,b)$ doesn't exists. 

- If the point $(a,b)$ is a [[Extremum in one Variable#Relative / Local|relative extrema]] of the function $f(x,y)$ and the first order [[Partial Derivatives|derivative]] if $f(x,y)$ exists at $(a,b)$ then $(a,b)$ is also a critical point of $f(x,y)$ an in fact we’ll have $\nabla f(a,b)=\vec{0}$.
# Saddle Point
- A saddle point or minimax point is a point on the surface of the graph of a function where the [[Rate of Change and Tangent Line#Tangent|slopes]] in orthogonal directions are all zero (a critical point), but which is not a relative extremum of the function.
- A saddle point (in red) on the graph of $z=x^{2}-y^{2}$

![[saddle point.png]]
# Relative Extremum
- The two relative extremum is defined as, 
	1. A [[function]] $f(x,y)$ has a **relative minimum** at the point $(a,b)$ if $f(x,y)\geq f(a,b)$ for all points $(x,y)$ in some region around $(a,b)$.
	2. A function $f(x,y)$ has a **relative maximum** at the point $(a,b)$ if $f(x,y)\leq f(a,b)$ for all points $(x,y)$ in some region around $(a,b)$.

- Suppose that $(a,b)$ is a critical point of $f(x,y)$ and that the second order partial derivative are [[Continuity|continuous]] in some region that contains $(a,b)$. Next define,$$D=D(a,b)=f_{x\ x}(a,b)\ f_{y\ y}(a,b)-[f_{x\ y}(a,b)]^{2}$$
We then have the following classifications of the stationary point.
	1. if $D>0$ and $f_{x\ x}(a,b)>0$ then there is a relative minimum at $(a,b).$
	2. if $D>0$ and $f_{x\ x}(a,b)<0$ then there is a relative maximum at $(a,b).$
	3. if $D<0$ then the point $(a,b)$ is a **saddle point**.
	4. If $D=0$ then the point $(a,b$) may be a relative minimum, relative maximum or a saddle point. Other techniques would need to be used to classify the critical point.
# Finding Absolute Extremum
1. Find all the critical points of the function that lie the region $D$ and determine the function value at each of these points.
2. Find all extrema of the function on the boundary.
3. The largest and the smallest values found in the first two steps are he absolute minimum and the absolute maximum of the function.
# Hessian Matrix 
- The $D$ calculated is called the **Hessian Matrix** denoted by $H$,$$
D= H=\begin{vmatrix}
f_{xx} & f_{xy} \\ \\
f_{xy} & f_{yy}
\end{vmatrix}$$
