---
tags:
  - Physics
  - Introductory_Mechanics
  - integration
---
# Integrating Equations of Motion in One Dimension
- From [[Newton's Laws of Motion#Newton’s Second law|Newton’s second law of motion]] we have, $$m\frac{d\mathbf{v}(t)}{dt}=\mathbf{F}(\mathbf{r})$$where $\mathbf{F}$ is a know function of position.
- In one dimension the position vector resolves into a just $x$ variable,$$m\frac{d^{2}x}{dt^{2}}=F(x)$$or,$$m \frac{dv}{dt}=F(x)$$
- [[Integrals|Integrating]] this to solve the equation for $v$,$$m \int_{x_{a}}^{x_{b}} \frac{dv}{dt} \, dx =\int_{x_{a}}^{x+b} F(x) \, dx \tag{1}$$
- To integrate the right side with respect to time rather than position we use [[Differentials|differentials]] to change the variables from $x$ to $t$,$$dx=\left( \frac{dx}{dt} \right)\,dt=v\,dt$$Then $$\begin{align}
m \int_{x_{a}}^{x_{b}} \frac{dv}{dt}  \, dx &= m\int_{t_{a}}^{t_{b}} \frac{dv}{dt} v \, dt \\
&=m\int_{t_{a}}^{t_{b} }  \frac{d}{dt} \left( \frac{1}{2} v^{2} \right) \, dt  \\
&= m \int_{t_{a}}^{t_{b}}\, d\left( \frac{1}{2} v^{2} \right)  \\
&=\frac{1}{2}mv^{2}\bigg|_{t_{a}}^{t_{b}} \\
&=\frac{1}{2}mv_{b}^{2}-\frac{1}{2}mv_{a}^{2}
\end{align}$$where $x_{a}\equiv x(t_{a})\\,v_{a}\equiv v_{a}(t)$, etc.
- Putting this result in equation $(1)$ yield,$$\frac{1}{2}mv_{b}^{2}-\frac{1}{2}mv_{b}^{2}=\int_{x_{a}}^{x_{b}} F(x) \, dx, \tag{2}$$where $v$ is speed of the particle when it is at position $x$.
# The Work–Energy Theorem 
- The quantity $\dfrac{1}{2}mv^{2}$ is called the **kinetic energy** $K$, and the left-hand side can be written $K_{b}-K_{a}$. 
- The integral $\int_{x_{a}}^{x_{b}} F(x) \, dx$ is called the **work** $W_{ba}$ by the force $F$ on the particle as the particle moves from $a$ to $b$. The relation from equation $(2)$ now takes the form $$\bbox[15px, border:1px solid white]{W_{ba}=K_{b}-K_{a}}$$
- This result is known as the **work energy theorem**, or more precisely, the work energy theorem in one dimension. 
- In three dimensions the work integral becomes a [[Line Integrals|path integral]] ,$$W_{ba}= \int_{\mathbf{r}_{a}}^{\mathbf{r}_{b}} \mathbf{F} \cdot d\mathbf{r} $$