---
tags:
  - derivatives
  - Calculus
  - Mathematics
aliases:
  - rate
  - slope
---
# Rate of Change
- A **rate** is the quotient of two quantities, the dividend of the rate expresses the corresponding **rate of change** in the other variable.

![[rate of change.png]]

- Here the average rate of change of given by,$$\langle rate\ of\ change \rangle=\frac{f(a+h)-f(a)}{h}$$
- The instantaneous rate of change if equivalent to a [[Derivatives|derivative]], and is obtained when the [[Limits|limit]] of the difference between two successive measurements $h$ approaches zero, that is $h\to 0$ .$$\text{Instantaneous rate of change} = \lim_{ h \to 0 } \frac{f(a+h)-f(a)}{h}=\frac{df}{dx}$$

# Tangent
- As $h\to 0$ the line passing joining $(a,f(a))\text{ and } (a+h,f(a+h))$ is called the tangent at $x=a$.
- The slope of tangent at $x=a$ is given by,$$\begin{align}
m &= \frac{{y_{2}-y_{1}}}{x_{2}-x_{1}}= \frac{{f(a+h) -f(a)}}{(a+h)-h} \\
&=\lim_{ h \to 0 } \frac{f(a+h)-f(a)}{h} \\
m &= \frac{df}{dx}
\end{align}$$
- The slope of the tangent at $x=a$ gives us the rate of change of the function $f(x)$ at $x=a$.
# Normal 
- The line perpendicular to the tangent is called the normal.
- The slope of normal is, $$
m=-\frac{1}{m_{tangent}}$$
## See also

- [[Directional Derivatives]]
- [[Newton's Method]]
- [[Linear Approximations]]
- [[Tangent and Normal Vectors]]