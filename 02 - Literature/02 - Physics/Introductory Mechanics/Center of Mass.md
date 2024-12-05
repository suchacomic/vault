---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Center of Mass for Discrete Systems
- From [[Conservation of Momentum|conservation of momentum]], $$\begin{align}
\mathbf{F}&=\frac{d\mathbf{P}}{dt} \\
\mathbf{F} &= M\ddot{\mathbf{R}}
\end{align}$$where $M$ is the total mass of the system and $\mathbf{R}$ is a [[Vector|vector]] yet to be defined.
- Because $\mathbf{p}=\sum_{j=1}^{N}m_{j}\ddot{\mathbf{r}}_{j}$,$$M\ddot{R}=\frac{d\mathbf{P}}{dt}=\sum_{j=1}^{N} m_{j}\ddot{\mathbf{r}}_{j}$$which is true if$$\bbox[15px, border:1px solid white]{\mathbf{R}=\frac{1}{M}\sum_{j=1}^{N} m_{j}\mathbf{r}_{j}}$$$\mathbf{R}$ is a vector from origin to a point called the **center of mass**.
- For a two particle system with masses $m_{1}$ and $m_{2}$ at positions $\mathbf{r}_{1}$and $\mathbf{r}_{2}$ respectively the center of mass is given by, $$\mathbf{R}=\frac{m_{1}r_{1}+m_{2}r_{2}}{m_{1}+m_{2}}$$![[99 - Meta/02 - Excalidraw/Drawings/Center of mass .excalidraw]]  
# Center of Mass
- As the number of particles approach infinity, we take the [[Limits|limit]] $N\to \infty$,$$\mathbf{R}= \frac{1}{M} \lim_{ N \to \infty } \sum_{j=1}^{N} m_{j}\mathbf{r}_{j}$$and by [[Area Under the Curve#Riemann Sum|Riemann sum]], the limiting process defines an integral. Formally $$\lim_{ N \to \infty } \sum_{j=1}^{N} m_{j}r_{j}=\int \mathbf{r\,}dm,$$where $dm$ is a [[Differentials|differential]] mass element at position $\mathbf{r}$. Then $$\bbox[15px, border:1px solid white]{\mathbf{R}=\frac{1}{M}\int \mathbf{r}\,dm}$$
- If we assume that $dm$ is the mass of an element of volume $dV$ located at position $\mathbf{r}$ ans the mass density of the element is $\rho$, then $dm=\rho\,dV$ and $$\bbox[15px, border:1px solid white]{R=\frac{1}{M}\iiint \limits_{V}\mathbf{r}\,\rho\,dV}$$