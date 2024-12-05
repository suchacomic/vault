---
tags:
  - Introductory_Mechanics
  - Physics
---
# Time of Flight
- Solving the equation of kinematics for [[Equations of Kinematics#Displacement and Acceleration|displacement of acceleration]] for a object thrown with a initial [[Displacement, Velocity and Acceleration#Velocity Vector|velocity]] $v_{0}$ at an angle $\theta$ from the horizon, $$y-y_{0}=v_{0,y}t-\frac{1}{2}gt^{2}=(v_{0}\sin\theta)t-\frac{1}{2}gt^{2}=0$$
- Factoring, we have,$$t\left( v_{0}\sin \theta-\frac{gt}{2} \right)=0$$
- Solving for $t$ gives us,$$
\bbox[15px, border:1px solid white]{T_{tof}=\frac{2v_{0}\sin\theta}{g}}
$$
# Range 
- Range can be calculated by,$$\begin{align}
R&=v_{0,x}\cdot T_{tof} \\
&=v_{0}\cos\theta \cdot \frac{2v_{0}\sin\theta}{g} \\
&=\frac{2v_{0}^{2}\sin\theta \cos\theta}{g}\end{align}$$using the double angle trigonometric property of $\sin\theta$, $$\bbox[15px, border:1px solid white]{\text{Range}=R=\frac{v_{0}^{2}\sin_{2}\theta}{g}}$$
# Maximum Height Reached $$\bbox[15px, border:1px solid white]{H_{max}=\frac{(v_{0}\sin\theta)^{2}}{2g}}$$
# Trajectory 
- The trajectory of a projectile can be found by eliminating the time variable $t$ from the [[Equations of Kinematics|kinematic equations]] for arbitrary $t$ and solving for $y(x)$.
- We take $y_{0}=x_{0}=0$ so the projectile is launched from the origin. The kinematic equation for $x$ gives $$x=v_{0,x}t\implies t=\frac{x}{v_{0,x}}=\frac{x}{v_{0}\cos\theta}$$
- Substituting the expression for $t$ into the [[Equations of Kinematics#Displacement and Acceleration|equation for the position]] $y=(v_{0}\sin\theta)t-\frac{1}{2}gt^{2}$ gives $$y=(v_{0}\sin\theta)\left( \frac{x}{v_{0}\cos\theta} \right)-\frac{1}{2}g\left( \frac{x}{v_{0}\cos\theta} \right)^{2}$$
- Rearranging the terms, we have $$\bbox[15px, border:1px solid white]{y=x\tan\theta-\left[ \frac{g}{2(v_{0}\cos\theta)^{2}} \right]x^{2}}$$
- This trajectory equation is of the form $y=ax+bx^{2}$,  which is an equation of a parabola with coefficients,$$a=\tan\theta,\hspace{0.25in}b=-\frac{g}{2(v_{0}\cos\theta)^{2}} $$