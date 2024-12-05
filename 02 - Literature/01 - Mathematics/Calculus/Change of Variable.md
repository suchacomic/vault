---
tags:
  - derivatives
  - Mathematics
  - Calculus
---
# Jacobian
- The [[Jacobian]] transformation of $x=g(u,v),y=h(u,v)$ is, $$\frac{ \partial (x,y) }{ \partial (u,v) }= \begin{vmatrix}
	\dfrac{ \partial r }{ \partial u } & \dfrac{ \partial x }{ \partial v }  \\
	\dfrac{ \partial y }{ \partial u }  & \dfrac{ \partial u }{ \partial v } \end{vmatrix}$$
# Change of Variables for a Double Integral
- Suppose that we want to [[Integrals|integrate]] $f(x,y)$ over the region $R$. Under the transformation $x=g(u,v),y=h(u,v)$ the region becomes $S$ and the [[Double Integrals|double integral]] becomes,$$\iint\limits_{R}f(x,y)\,=\iint\limits_{S}f(g(u,v),h(u,v))\left\lvert  \frac{ \partial (x,y) }{ \partial (u,v) }  \right\rvert \,\overline{dA}$$
# Change of Variable for a Triple Integral
- For a [[Triple Integrals|triple integral]],$$\iiint\limits_{R}f(x,y,z)\,dV=\iiint\limits_{S}f(g(u,v,w),h(u,v,w),k(u,v,w))\,\left\lvert  \frac{ \partial (x,y,z) }{ \partial (u,v,w) }\right\rvert  \, \overline{dV}$$