---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses: []
aliases:
  - angular momentum
---
# Angular Momentum 
- The angular momentum $\mathbf{L}$ of a particle that has [[Conservation of Momentum#Momentum|momentum]] $\mathbf{p}$ and is at position $\mathbf{r}$ with respect to a given coordinate system:$$\mathbf{L}=\mathbf{r}\times \mathbf{p}$$
- $\mathbf{L}$ explicitly depends upon $\mathbf{r}$, thus contrary to linear momentum $\mathbf{p}$, the value of $\mathbf{L}$ depends not only on the motion of the particle, but also on its location with respect to the origin of a particular coordinate system.
- The [[Vector|vectors]] $\mathbf{r}$ and $\mathbf{p}$ determines a [[Equation of Plane|plane]] called the plane of motion, and by the properties of the [[Vector Operations#Cross Product|cross product]], $\mathbf{L}$ is perpendicular to the plane.
- The direction of $\mathbf{L}$ is dictated by the [[Right-Hand Rule|right-hand rule]]. 
- The angular momentum can also be [[Fixed Axis Rotation#Dynamics of Fixed axis rotation|obtained by]] $$\mathbf{L}=I\boldsymbol{\omega}$$
# Torque 
- We introduce a new quantity, torque $\tau$, which plays a role in [[Rotational Motion|rotational motion]] analogous to the role of force in linear motion.
- The torque due to the force $\mathbf{F}$ that acts in a particle at position $\mathbf{r}$ is defined to be $$\boldsymbol{\tau}=\mathbf{r}\times \mathbf{F}$$
- The magnitude of $\boldsymbol{\tau}$ is given by $$\lvert \boldsymbol{\tau} \rvert = \lvert \mathbf{r}_{\perp} \rvert \lvert \mathbf{F} \rvert = \lvert \mathbf{r} \rvert\lvert \mathbf{F}_{\perp} \rvert  $$
- The direction of the torque vector is given by the [[Right-Hand Rule|right-hand rule]]
- The torque can also be obtained from the [[Fixed Axis Rotation#Dynamics of Fixed axis rotation|rotational equivalent]] of [[Newton's Laws of Motion#Newton’s Second law|Newton’s second law ]], $$\boldsymbol{\tau}=I\boldsymbol{\alpha}$$
# Relation between Torque and Angular Momentum 
- The [[Rate of Change and Tangent Line|rate of change]] of angular momentum is determined by torque, $$\frac{d\mathbf{L}}{dt}=\frac{d}{dt}(\mathbf{r}\times \mathbf{p})$$by [[Derivatives#Chain Rule|chain rule]], $$\frac{d\mathbf{L}}{dt}=\left( \frac{d\mathbf{r}}{dt}\times \mathbf{p} \right)+\left( \mathbf{r}\times \frac{d\mathbf{p}}{dt} \right)$$
- The first bracketed term [[Vector Operations#Cross Product|vanishes]] as $$\mathbf{v}\times m\mathbf{v}=0$$also by [[Newton's Laws of Motion#Newton’s Second law|newtons second law]] $d\mathbf{p} / dt=\mathbf{F}$ and hence the second bracketed term is $\mathbf{r}\times \mathbf{F}=\boldsymbol{\tau}$,  $$\boldsymbol{\tau}=\frac{d\mathbf{L}}{dt}$$
# Conservation of Angular Momentum 
- The above formulation shows that if the torque is zero, $\mathbf{L}$ is constant and the angular momentum is conserved. 
- The angular momentum of a system of particles around a point in a fixed [[Reference Frame#Inertial Reference Frame|inertial frame]] is conserved if there is no net external torque around that point: $$\frac{d\mathbf{L}}{dt}=\mathbf{0}$$or, $$\mathbf{L}=\text{constant}$$