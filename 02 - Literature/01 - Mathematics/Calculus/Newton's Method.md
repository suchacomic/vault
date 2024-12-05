---
tags:
  - approximation
  - Calculus
  - derivatives
  - Mathematics
---
- Suppose we want to approximate the solution to $f(x)=0$ and we found a initial approximation to this solution say, $x_{0}$/
- The equation of [[Rate of Change and Tangent Line#Tangent|tangent]] line to $f(x)$ at $x_{0}$ is given by,$$y=f(x_{0})+f'(x_{0})(x-x_{0})$$
![[Newton's Method.png]]

- The blue line is the tangent at $x_{0}$, we can see that this line will cross the $x$-axis much closer to the actual solution to the equation than $x_{0}$.
- Plugging $(x_{1},0)$ into the tangent equation as follows,$$
\begin{align*}
0 &= f(x_{0})+f'(x_{0})(x_{1}-x_{0})\ \\
x_{1}-x_{0} &= -\frac{f(x_{0})}{f'(x_{0})}\\
x_{1} &= x_{0}-\frac{f(x_{0})}{f('(x_{0}))}
\end{align*}$$

- Now we repeat the whole process to find an even better approximation.
- More generally, if $x_{n}$ is an approximation of a solution of $f(x)=0$ and if $f'(x_{n})\ne 0$ then the next approximation is given by,$$x_{n+1}=x_{n}-\frac{{f(x_{n})}}{f'(x_{n})}$$
## See also

- [[Linear Approximations]]
- [[Derivatives]]