---
tags:
  - Physics
  - Introductory_Mechanics
---
# Potential Energy
- The work done by [[Conservative Forces|conservative force]] is independent of the [[Line Integrals|path]] and along any path from $a$ to $b$ is $$\int_{\mathbf{r}_{a}}^{\mathbf{r}_{b}} \mathbf{F}\cdot d\mathbf{r} = -U(\mathbf{r}_{b})+U(\mathbf{r}_{a}) $$Where $U(\mathbf{r})$ is a function, defined by the above expression, known as the [[Conservative Forces#Potential|potential]] energy function.
- Only the difference in potential energy have a physical significance.
- Consider the change in potential energy $\Delta U$ as the particle moves from some point $x$ to $x+\Delta x$:$$\begin{align} U(x+\Delta x)-U(x)&=\Delta U \\ &=-\int_{x}^{x+\Delta x} F(x) \, dx  \end{align}$$for sufficiently small $\Delta x$, $F(x)$ can be considered constant over the range of integration and we have $$\begin{align} \Delta U &\approx-F(x)[(x+\Delta x)-x] \\ &= -F(x)\,\Delta x \end{align}$$or,$$F(x) \approx -\frac{\Delta U}{\Delta x}$$
- In the [[Limits|limit]] $\Delta x\to {0}$ we have $$F(x)=-\frac{dU}{dx}$$
- Extending this relation to three dimensions and from [[Conservative Forces#Potential|potential of a conservative force]],$$\bbox[15px, border:1px solid white]{\mathbf{F}=-\nabla U}$$we say that $\mathbf{F}$ is derivable from a potential energy.
  
# Energy Conservation
- For conservative forces the [[Work Energy Theorem|work energy theorem]] becomes, $$\int_{\mathbf{r}_{a}}^{\mathbf{r}_{b}} \mathbf{F}\cdot d\mathbf{r} = W_{ba}= -U(\mathbf{r}_{b})+U(\mathbf{r}_{a}) $$or, rearranging, $$K_{a}+U_{a}=K_{b}+U_{b}$$because $\mathbf{r}_{a}$ and $\mathbf{r}_{b}$ are arbitrary and nit specially chosen points, this can be true only if each side of the equation equals a constant. Denoted $E$, we have $${K_{a}+U_{a}=K_{b}+U_{b}=E}$$$E$ is called the **total mechanical energy** of the particle which remains constant and for conservative forces are is conserved.
- If we have $n$ conservative forces $\mathbf{F}_{i}, (i=1,\dots,n)$ acting on a particle, each with its corresponding potential energy $U_{i}(\mathbf{r})$ the **total mechanical energy** is defined as, $$\bbox[15px, border:1px solid white]{E\equiv K+U\equiv K+U_{1}(\mathbf{r})+\dots+U_{n}(\mathbf{r})}$$is <u>constant in time</u>.
# Energy Conservation with Non-Conservative Forces
- We divide the net forces on the particle into two parts, the conservative part $\mathbf{F}_{\text{cons}}$ and the non-conservative part $\mathbf{F}_{\text{nc}}$,
- If the potential energy corresponding to $\mathbf{F}_{\text{con}}$ is given by $U$, by [[Work Energy Theorem|work energy theorem]], the change in kinetic energy between any two times is $$\Delta K=W=W_{\text{cons}}+W_{\text{nc}}$$as, $W_{\text{cons}}=-\Delta U$, we have $$\begin{align}
\Delta K &= -\Delta U+W_{\text{nc}} \\
\Delta K+\Delta U &= W_{\text{nc}} \\
\Delta E &\equiv \Delta(K+U)=W_{\text{nc}}\end{align}$$
- The mechanical energy is not conserved but the change in mechanical energy corresponds exactly to the work done by the non-conservative forces on the particle,$$\bbox[15px, border:1px solid white]{\Delta E=W_{\text{nc}}}$$
- Example of non-conservative forces include friction, air resistance and viscosity. 
# Time-Dependent Potential Energy 
- We can define a potential energy $U(\mathbf{r},t)$ with the property that $\mathbf{F}=-\nabla U$, but it is no longer the case that mechanical energy is conserved.
- Consider two neighboring points on a particles path at times $t$ and $t+dt$, then the [[Differentials|change]] in kinetic energy is $$dK=(m\dot{\mathbf{v}}\cdot \mathbf{v})\,dt=\mathbf{F}\cdot d\mathbf{r}$$
- The function $U(\mathbf{r},t)$ is a function of four variables, $(x,y,z,t)$ and by [[Partial Derivatives#Chain Rule|chain rule]], $$dU=\frac{ \partial U }{ \partial x } dx+\frac{ \partial U }{ \partial y } +\frac{ \partial U }{ \partial z } dz+\frac{ \partial U }{ \partial t } dt$$The first three terms on the right is the potential of a force $\mathbf{F}$: $\nabla U=-\mathbf{F}\cdot d\mathbf{r}$. Thus $$dU=-\mathbf{F}\cdot d\mathbf{r}+\frac{ \partial U }{ \partial t } dt$$adding this to the change in $K$ equation, $$\begin{align}
dK &=-dU+\frac{ \partial U }{ \partial t } dt \\
	d(K+U) &= \frac{ \partial U }{ \partial t } dt
\end{align}$$
- It is only when $U$ is independent of $t$ (that is ${ \partial U } / { \partial t }=0$) is the total mechanical energy conserved.

# See also
