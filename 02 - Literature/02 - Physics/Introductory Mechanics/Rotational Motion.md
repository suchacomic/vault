---
tags:
  - Physics
  - Introductory_Mechanics
---
# Angular Position 
- The angle $\theta$ is called the **angular position** of the particle. As the particle moves in its circular path, it also traces an arc length $s$. The angle is related to the radius of the circle and the arc length by $$\theta=\frac{s}{r}$$or,$$\bbox[15px, border:1px solid white]{\vec{\mathbf{s}}=\vec{\boldsymbol{\theta}}\times \vec{\mathbf{r}}}$$
# Angular Velocity 
- The magnitude of **angular velocity**, denoted by, $\omega$, is the time [[Rate of Change and Tangent Line|rate of change]] of the angle $\theta$ as the particle moves in its circular path.
- The instantaneous angular velocity is defined as the [[Limits|limit]] in which $\Delta t\to 0$ in the average angular velocity $\boldsymbol{\omega}=\frac{\Delta\theta}{\Delta t}$:$$\omega=\lim_{ \Delta t \to 0 } \frac{\Delta\theta}{\Delta t}=\frac{d\theta}{dt} $$
- The relation between angular velocity and the tangential speed of the particle can be obtained by [[Derivatives|differentiating]] the arc length and angle relation $s=r\theta$,$$\frac{ds}{dt}=\frac{d}{dt}(r\,\theta)=\theta \frac{dr}{dt} +r \frac{d\theta}{dt}=r\frac{d\theta}{dt}$$here the radius is constant thus we get the tangential [[Displacement, Velocity and Acceleration#Velocity Vector|velocity]], $$v_{t}=r\omega$$or in vector form,$$\bbox[15px, border:1px solid white]{\mathbf{\vec{v}}=\boldsymbol{\vec{\omega}}\times \mathbf{\vec{r}}}$$
# Angular Acceleration 
- We define instantaneous **angular acceleration** $\alpha$ as the derivative of angular velocity with respect to time:$$\alpha=\lim_{ \Delta t \to 0 } \frac{\Delta\omega}{\Delta t}=\frac{d\omega}{dt}=\frac{d^{2}\theta}{dt^{2}}$$
- Taking the derivative of tangential velocity, we get tangential acceleration $$\bbox[15px, border:1px solid white]{\mathbf{\vec{a}}=\boldsymbol{\vec{\alpha}}\times \mathbf{\vec{r}}}$$or $$a_{t}=r\alpha$$
# Rotational Kinematics 
- Analogous to [[Equations of Kinematics|kinematics]] in linear motion we have three equations describing the motion in rotational paradigm
	1. $\displaystyle \theta_{f}=\theta_{0}+\omega t$
	2. $\displaystyle\omega_{f}=\omega_{0}+\alpha t$
	3. $\displaystyle \theta_{f}=\theta_{0}+\omega_{0}t+\frac{1}{2}\alpha t^{2}$
