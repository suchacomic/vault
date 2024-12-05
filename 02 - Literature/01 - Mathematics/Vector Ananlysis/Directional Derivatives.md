---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Definition of Directional Derivative
- The rate of change of $f(x,y)$ in the direction of a [[Vector#Unit Vector|vector]] $\vec{u}=\langle a,b \rangle$ is called the **directional derivative** and is demoted by $D_{\vec{u}}f(x,y)$. The definition of the directional derivative is, $$
D_{\vec{u}}f(x,y)=\lim_{ h \to 0 } \frac{{f(x+ah,y+bh)-f(x,y)}}{h}$$
- This is basically is we were to move in the direction of $\vec{u}$ what is the [[Derivatives|rate change]] of $f(x,y)$. 
- The directional [[Derivatives|derivative]] of $f(x,y,z)$ in the direction of the unit vector $\vec{u}=\langle a,b,c \rangle$ is given by, $$
\begin{align}
D_{\vec{u}}{f(x,y,z)} &= f_{x}(x,y,z)a+f_{y}(x,y,z)b+f_{z}(x,y,z)c \\
	&= \frac{ \partial f }{ \partial x }\ a+\frac{ \partial f }{ \partial y }\ b +\frac{ \partial f }{ \partial z }\ c \\
&= \langle f_{x},f_{y},f_{z}\rangle \cdot \langle a,b,c \rangle   \\ \\

D_{\vec{u}}{f(x,y,z)}&= {\nabla f\ \cdot}\  \vec{u}
\end{align}
$$
# Theorems
 - The maximum value of $D_{\vec{u}}f(\vec{x})$ (and hence then the maximum [[Rate of Change and Tangent Line#Rate of Change|rate of change]] of the function $f(\vec{x})$) is given by $\lVert \nabla f(\vec{x}) \rVert$ and will occur in the direction given by $\nabla d(\vec{x})$.
- The [[Gradient|gradient]] vector $\nabla f(x_{0},y_{0},z_{0})$ is orthogonal to the [[Vector Fields#Contour Lines|contour lines]] $f(x,y,z)=k$ at the point $(x_{0},y_{0},z_{0})$.
