---
aliases: 
tags:
  - Calculus
  - Mathematics
  - derivatives
cssclasses:
  - center-images
---
# Partial Derivatives
- The partial derivative of a function $z=f(x,y)$ is defined as 

$$\frac{ \partial }{ \partial x }f(x,y)=f_{x}(x,y)=f_{x}=D_{x}f=z_{x}=\lim_{ h \to 0 }\frac{{f(x+h,y)-f(x,y)}}{h}$$
$$\frac{ \partial  }{ \partial y }f(x,y)=f_{y}(x,y)=f_{y}=D_{y}f=z_{y}=\lim_{ h \to 0 } \frac{{f(x,y+h)-f(x,y)}}{h}$$

- Partial [[Derivatives|derivative]] $f_{x}(a,b)$ is the [[Rate of Change and Tangent Line#Tangent|slope]] of [[Vector Fields#Contour Lines|trace]] of $f(x,y)$ for the [[Equation of Plane|plane]] $y=b$ at the point $(a,b)$.
# Higher Order Partial Derivatives
- For a function of two variables there will be a total of four possible second derivatives.$$\begin{align}
({f_{x}})_{x} & = f_{x\ x}=\frac{ \partial }{ \partial x }\left( \frac{ \partial f }{ \partial x } \right) = & \frac{ \partial^{2} f }{ \partial x^{2} } \\
({f_{x}})_{y} & = f_{x\ y}=\frac{ \partial }{ \partial y }\left( \frac{ \partial f }{ \partial x } \right) = & \frac{ \partial^{2} f }{ \partial y \partial x } \\
({f_{y}})_{x} & = f_{y\ x}=\frac{ \partial }{ \partial x }\left( \frac{ \partial f }{ \partial y } \right) = & \frac{ \partial^{2} f }{ \partial x \partial y } \\
({f_{y}})_{y} & = f_{y\ y}=\frac{ \partial }{ \partial y }\left( \frac{ \partial f }{ \partial y } \right) = & \frac{ \partial^{2} f }{ \partial y^{2} } \\
\end{align}$$
# Clairaut’s Theorem
- Suppose that $f$ is defined on a disk $D$ that contains the point $(a,b)$. If the function $f_{xy}$ and $f_{yx}$ are [[Continuity|continuous]] on this disk then,$$f_{xy}(a,b)=f_{yx}(a,b)$$
- Clairaut’s theorem can be naturally extended to any function and mixed partial derivative. The only requirement being that each derivative we differentiate with respect to each variable the same number of time.$$f_{ssrtsrr}=f_{trsrssr}$$
# Chain Rule
- In one variable for $y=f(x)$ and $x=g(t)$,$$
\frac{dy}{dt}=\frac{dy}{dx}{\frac{dx}{dt}} 
$$

- For two variable [[Function|function]],
	1. **Case 1 :** $z=f(x,y),x=g(t),y=h(t)$$$\frac{dz}{dt}=\frac{ \partial f }{ \partial x } \frac{dx}{dt}+\frac{ \partial f }{ \partial y } \frac{dy}{dt}$$
	2. **Case 2 :** $z=f(x,y),x=g(s,t),y=h(s,t)$$$
\begin{align}
\frac{ \partial z }{ \partial s } &= \frac{ \partial f }{ \partial x } \frac{ \partial x }{ \partial s } +\frac{ \partial f }{ \partial y } \frac{ \partial y }{ \partial s } \\			\frac{ \partial z }{ \partial t } &= \frac{ \partial f }{ \partial x } \frac{ \partial x }{ \partial t } + \frac{ \partial f }{ \partial y } \frac{ \partial y }{ \partial t } 
\end{align}$$ ![[Partial Derivatives.png]]
- For function $z$ of $n$ variables, $x_{1},x_{2},\dots,x_{n}$, and each of these variables are in turn functions of $m$ variables, $t_{1},t_{2},\dots,t_{n}$. Then for any variable $t_{i}$,$i=1,2,\dots,m$ we have the following,$$\frac{ \partial z }{ \partial t_{i} } = \frac{ \partial z }{ \partial x_{1} }\frac{ \partial x_{1} }{ \partial t_{i} }+\frac{ \partial z }{ \partial x_{2} } \frac{ \partial x_{2} }{ \partial t_{i} } +\dots+\frac{ \partial z}{ \partial x_{n} } \frac{ \partial x_{n} }{ \partial t_{i} }$$

## See also

- [[Derivatives#Chain Rule|Chain Rule for one Variable]]
