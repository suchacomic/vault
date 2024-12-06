---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Collision 
- Assuming the external forces are negligible, the total [[Conservation of Momentum|momentum]] in a collision even is conserved.$$\mathbf{P}_{i}=\mathbf{P}_{f}$$
- For two body collision, ![[99 - Meta/02 - Excalidraw/Drawings/ED-collision.excalidraw]]$$m_{1}\mathbf{u}_{1}+m_{2}\mathbf{u}_{2} = m_{1}\mathbf{v}_{1}+m_{2}\mathbf{v}_{2}$$
# Coefficient of Restitution  
- Coefficient of restitution, denoted by $e$ is $$\begin{align}
e = \frac{\text{Relative Velocity of Sepereation}}{\text{Relative Velocity of Approch}}
\end{align}$$
$$\bbox[15px, border:1px solid white]{e=\frac{{\mathbf{v}_{2}-\mathbf{v}_{1}}}{\mathbf{u}_{1}-\mathbf{u}_{2}}}$$
# Elastic Collision 
- A collision in which the total kinetic energy is unchanged is called an elastic collision.
- The coefficient of restitution is equal to $1$ for a perfectly elastic collision. $$\mathbf{v}_{2}-\mathbf{v}_{1}= \mathbf{u}_{1}-\mathbf{u}_{2}$$
# Inelastic Collision 
- A collision in which the total kinetic energy is not conserved is called an inelastic collision.
- The coefficient of restitution is between 0 and 1. $$0<e<1, \hspace{.25in}V_{\text{seperation}}<V_{\text{approach}}$$
- The loss in kinetic energy is given by, $$\Delta K=(K_{i})_{\text{com}}(1-e^{2})$$
# Perfectly Inelastic Collision 
- The coefficient of restitution is exactly zero. 
- Both bodies stick together and travel at the same velocity after the collision.$$\mathbf{v}_{2}=\mathbf{v}_{1}$$
# Collision and Center of Mass Coordinates 
- Consider two particles of masses $m_{1}$ and $m_{2}$ with positions $\mathbf{r}_{1}$ and $\mathbf{r}_{2}$ moving with velocities $\mathbf{v}_{1}$ and $\mathbf{v}_{2}$. The [[Center of Mass|center of mass]] is given by, $$\mathbf{R}=\frac{{m_{1}\mathbf{r}_{1}+m_{2}\mathbf{r}_{2}}}{m_{1}+m_{2}}$$[[Derivatives|Differentiating]] with respect to time, we get the center of mass velocity $$\mathbf{V}=\frac{{m_{1}\mathbf{v}_{1}+m_{2}\mathbf{v}_{2}}}{m_{1}+m_{2}}$$
- The velocities in the $C$ system are$$\begin{align}\mathbf{v}_{1c} &= \mathbf{v}_{1}-V \\ &= \frac{m_{2}}{m_{1}+m_{2}}(\mathbf{v}_{1}-\mathbf{v}_{2}) \end{align}$$and $$\begin{align} \mathbf{v}_{2c} &= \mathbf{v}_{2}-\mathbf{V}  \\
&= \frac{m_{1}}{m_{1}+m_{2}} (\mathbf{v}_{2}-\mathbf{v}_{1}) \end{align}$$
- The momenta in the $C$ system are $$\begin{align} \mathbf{p}_{1c}=m_{1}\mathbf{v}_{1c} &= \frac{m_{1}m_{2}}{m_{1}+m_{2}}(\mathbf{v}_{1}-\mathbf{v}_{2})  \\ &= \mu \mathbf{v} \\\mathbf{p}_{2c} =m_{1}\mathbf{v}_{2c} &= \frac{m_{1}m_{2}}{m_{1}+m_{2}} (\mathbf{v}_{2}-\mathbf{v}_{1}) \\ &=-\mu \mathbf{v} \end{align}$$where $\mathbf{v}$ is the relative velocity [[Vector|vector]] $\mathbf{v}=\mathbf{v}_{1}-\mathbf{v}_{2}$ and $\mu=\dfrac{m_{1}m_{1}}{m_{1}+m_{2}}$ is the **reduced mass of the system**, the natural unit of mass in a two-particle system.
- As the total momentum is conserved in any collision, $\mathbf{V}$ is constant.$$\bbox[15px, border:1px solid white]{\mathbf{V}_{\text{com}}=\text{Constant}}$$  