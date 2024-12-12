---
tags:
  - Physics
  - Introductory_Mechanics
---
# Fixed Axis Rotation
![[99 - Meta/02 - Excalidraw/Drawings/ED-angular_momentum.excalidraw]]
- Consider a body rotating around the $z$ axis, so that $$\begin{align}
\lvert \mathbf{v}_{j} \rvert &= \lvert \dot{\mathbf{r}}_{j} \rvert  \\
&= \omega \rho_{j}
\end{align}$$where $\rho_{j}=\sqrt{ x^{2}+y^{2} }$ is the perpendicular distance from the axis of rotation to the particle $m_{j}$ of the rigid body and $\omega$ is the rate of rotation ([[Rotational Motion#Angular Velocity|angular velocity]]) .
- The [[Conservation of Angular Momentum#Angular Momentum|angular momentum]] of the $j^{\text{th}}$ particle, ml$\mathbf{L}_{j}$, is $$\mathbf{L}_{j}=\mathbf{r}_{j}\times m_{j}\mathbf{v}_{j}$$Since we are concerned only with $L_{z}$, the component of angular momentum along the axis of rotation and $\mathbf{v}_{j}$ lies in the $x$-$y$ plane, $$\begin{align} L_{j,z} &= m_{j}v_{j}\times \rho_{j} = m_{j}v_{j}\rho_{j} \\ &=m_{j}\rho^{2}_{j}\omega \end{align}$$
- The $z$ component of the total angular momentum of the body $L_{z}$ is the sum of individual $z$ components: $$L_{z} = \sum_{j} L_{j,z}=\sum_{j}m_{j}\rho^{2}_{j}\omega$$where the sum is over all the particles of the body.

# Dynamics of Fixed axis rotation 
- Consider a body rotating with the [[Rotational Motion#Angular Velocity|angular speed]] $\omega$ around the $z$ axis, the $z$ component of [[Conservation of Angular Momentum#Angular Momentum|angular momentum]] is $$L_{z}=I \omega$$where $I$ is the [[Moment of Inertia|moment of inertia]]. 
- Since $\tau=d\mathbf{L} / dt$, where $\tau$ is the [[Conservation of Angular Momentum#Torque|external torque]], we have $$\begin{align} \tau_{z} &= \frac{d}{dt}(I\omega) \\ &= I \frac{d\omega}{dt}  \\ &= I\alpha\end{align}$$where $\alpha$ is called the [[Rotational Motion#Angular Acceleration|angular acceleration]]
- The kinetic energy of a body undergoing pure rotation is $$\begin{align} K &= \sum_{j} \frac{1}{2}m_{j}v_{j}^{2}  \\ &= \sum_{j} \frac{1}{2}m_{j} \rho_{j}^{2} \omega^{2}  \\ &= \frac{1}{2} I \omega^{2}\end{align}$$