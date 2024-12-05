---
tags:
  - Calculus
  - derivatives
  - Vector_Analysis
  - Mathematics
---
# Lagrange Multiplier 
- We want to optimize (i.e. find the minimum or maximum value of) a function, $f(x,y,z)$, subject to the constrain $g(x,y,z,)=k$.
- The constraint may be equation that describes the boundary of a region or it may not be.
- **Method of Lagrange Multiplier:**
	1. Solve the following system of equations.$$\begin{align}\nabla f(x,y,z) &= \lambda\ \nabla g(x,y,z) \\ g(x,y,z) &= k\end{align}$$
	2. Plug in the solutions, $(x,y,z)$, from the first step into $f(x,y,z)$ and identify the minimum and maximum values, provided they exist and $\nabla g\neq 0$ at that point.
	The constant $\lambda$ is called the **Lagrange Multiplier**.
- The constant $\lambda$ gives the rate of change of $f_{max}$ with respect to the constraint constant.$$\lambda = \frac{df_{max}}{dk}$$
- For multiple constraints $g(x,y,z)=k$ and $h(x,y,z)=l$,$$\begin{align}
\nabla f(x,y,z) &= \lambda \nabla g(x,y,z)+\mu \nabla h(x,y,z) \\
g(z,y,z) &= k \\
h(x,y,z) &= l
\end{align}$$
# Lagrangian 
$$
\mathcal{L}(x,y,\lambda)=f(x,y)-\lambda(g(x,y)-k)
$$
- This is a compact way to represent the constraint problem,$$
\nabla\mathcal{L}=0\implies \begin{cases} \displaystyle 
\frac{ \partial h }{ \partial x } &= f_{x}-\lambda g_{x}=0 \\ \displaystyle 
\frac{ \partial h }{ \partial y } &=f_{y}-\lambda g_{y}=0 \\ \displaystyle \frac{ \partial \mathcal{L} }{ \partial\lambda } &=0 -\lambda(g(x,y)-k)=0 \\ \displaystyle 
&=g(x,y)=k
\end{cases}
$$
