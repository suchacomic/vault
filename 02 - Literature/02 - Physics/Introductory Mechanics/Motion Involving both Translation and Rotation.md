---
tags:
  - Physics
  - Introductory_Mechanics
---
# Chasles’ Theorem
- Consider a rigid body undergoing arbitrary motion. Pick any point $P$ in the body. Then at any instance, the motion of the body can be written as the sum of the [[Displacement, Velocity and Acceleration|translational motion]] of $P$,plus the [[Rotational Motion|rotational motion]] around some axis (which may change with time) through $P$.

# Angular Momentum of a Moving Body
- Let $z$ be the axis of rotation, the $z$ component of [[Conservation of Angular Momentum#Angular Momentum|angular momentum]] $L_{z}$, is the sum of two terms:
	1. The angular momentum $I_{0}\omega$ due to rotation of the body around its [[Center of Mass|center of mass]].
	2. The angular momentum due to motion of the center of mass with respect to the origin of the [[Reference Frame#Inertial Reference Frame|inertial coordinate system]]
	$$L_{z}=I_{0}\omega + (\mathbf{R}\times M\mathbf{V})_{z}$$Where $\mathbf{R}$ is a vector from the origin to the center of mass, $\mathbf{V}=\dot{\mathbf{R}}$ and $I_{0}$ is the moment of inertia around the center of mass.
- These two terms are referred to as the spin and the orbital angular momentum respectively.  
- The spin angular momentum is independent if the coordinate system, whereas the orbital angular momentum disappears if the origin is chosen to lie along the line of motion. 
# Torque on a Moving Body
- The torque also naturally divides itself into two terms. The torque on a body is $$\boldsymbol{\tau}=\tau_{0}+(\mathbf{R}\times \mathbf{F})_{z}$$where $\tau_{0}$ is the $z$ component of the torque around the center of of mass.
- From equation describing angular momentum $L_{z}$ we have $$\begin{align} \frac{dL_{z}}{dt} &= I_{0} \frac{d\omega}{dt}+\frac{d}{dt}(\mathbf{R}\times M\mathbf{V})_{z} \\ &= I_{0}\alpha + (\mathbf{R}\times M\mathbf{a})_{z}\,; \hspace{0.15in} \mathbf{R} \text{ is constant} \end{align}$$
- Using $\tau_{z}=dL_{z} / dt$ yield $$\begin{align}
\tau_{0}+(\mathbf{R}\times \mathbf{F})_{z} &= I_{0}\alpha+(\mathbf{R}\times M\mathbf{a})_{z} \\
&= I_{0}\alpha
+(\mathbf{R}\times \mathbf{F})_{z}\end{align}$$Hence $$\tau_{0}=I_{0}\alpha$$
# Kinetic Energy
- The same nature of natural separation holds true for the kinetic energy $K$. $$\bbox[15px, border:1px solid white]{K=\frac{1}{2}I_{0}\omega^{2}+\frac{1}{2}MV^{2}}$$
# Work-Energy Theorem 
- The work done similarly is composed of two components, 
- The [[Work Energy Theorem|work done]] when the center of mass is displaced by $d\mathbf{R}=\mathbf{V}\,dt$ is $$\mathbf{F}\cdot d\mathbf{R}= \left( M \frac{d\mathbf{V}}{dt} \right)\cdot \mathbf{V}\,dt=d\left( \frac{1}{2}MV^{2} \right)$$[[Integrals|Integrating]] we obtain $$\int_{\mathbf{R}_{a}}^{\mathbf{R}_{b}} \mathbf{F}\cdot d\mathbf{R} = \frac{1}{2}MV_{b}^{2}-\frac{1}{2}MV_{a}^{2}$$
- The work done by the applied [[Conservation of Angular Momentum#Torque|torque]] when the body is displaced by $d\theta=\omega\, dt$ is,$$\begin{align}
\tau_{0}\,d\theta &= I_{0}\,\alpha \,d\theta=I_{0} \frac{d\omega}{dt}\omega\,dt \\
&= d\left( \frac{1}{2}I_{0} \omega^{2}\right)
\end{align}$$Integrating, we find that $$\int_{\theta_{a}}^{\theta_{b}} \tau_{0}\,d\theta= \frac{1}{2}I_{0}\,\omega_{b}^{2}-\frac{1}{2}I_{0}\,\omega_{a}^{2}$$
- The general work-energy theorem for a rigid body is therefore $$K_{b}-K_{a}=W_{ba}$$where $\displaystyle K=\frac{1}{2}MV^{2}+\frac{1}{2}I_{0}\,\omega^{2}$ and $W_{ba}$ is the total work on the body as it moves from position $a$ to position $b$.
- The work-energy theorem is composed of two independent theorems, one for translation and one for rotation. They can be applied separately too. 