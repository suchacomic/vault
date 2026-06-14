---
tags:
  - Mathematics
  - Physics
  - Differential_Geometry
---
- Let a particle traveling along a trajectory at time $t$ has the velocity $${\mathbf{v}}=\mathbf{\dot{x}}(t) \equiv \frac{d\mathbf{x}}{dt} $$
- It is convenient to write $\mathbf{v}$ in terms of the distance $l$ along the trajectory. Let $s$ be any [[Parametric Equations and Curves|parameter]] that increases [[Derivatives|smoothly]] and [[Monotonicity and Concavity|monotonic]] along the trajectory, and let $\mathbf{x}(s_{0})$ and $\mathbf{x}({s_{1})}$ be any two points in the trajectory. Then the [[Position and Distance#distance|distance]] along the trajectory between the two points is $$l(s_{0},s_{1})=\int_{s_{0}}^{s_{1}} \left( \frac{dx_{i}}{dt} \frac{dx_{i}}{dt} \right)^{1/2} \, ds $$
- Note the use of summation convention here: there is a sum over $i$.
- $l$ does not depend on the parameter $s$. The trajectory can be parameterized by the time $t$ or even $l$ itself. the result would be the same.  
- If $l$ is taken as the parameter, $\mathbf{v}$ can be written in terms of $l$:$$\mathbf{v}=\frac{d\mathbf{x}}{dt} \frac{dl}{dt}$$
- But ${d\mathbf{x}}/{dl}$ is just the unit vector ${} \hat{\tau} {}$ [[Tangent and Normal Vectors#Tangent Vector|tangent]] to the trajectory at time $t$ ![[tangent_normal_binormal.png]]
- Then $\mathbf{v}$ becomes $$\mathbf{v}=\hat{\tau} \frac{dl}{dt}={\hat{\tau}}v$$ where $v$ is the speed along the trajectory $v=\dot{l}$
- The acceleration $\mathbf{a}$ is given by $$\mathbf{a}=\mathbf{\dot{v}}\equiv \ddot{\mathbf{x}}\equiv \frac{d\mathbf{v}}{dt}$$ $$\mathbf{a}=\frac{d\hat{\tau}}{dt} v + \hat{\tau} \frac{dv}{dt }$$
- $\hat{\dot{\tau}}$ is perpendicular to the $\hat{\tau}$ and hence to the curve thus $$\frac{d}{dt} (\hat{\tau} \cdot \hat{\tau}) = 0 = 2\hat{\tau} \cdot \frac{d\hat{\tau}}{dt}$$
- Let ${} \hat{n} {}$ be the unit vector in the direction of $d\hat{\tau} / dt$, called the *principle [[Tangent and Normal Vectors#Normal Vector|normal]] vector*. $$\mathbf{n}= \frac{\hat{\dot{\tau}}}{|\hat{\dot{\tau}}|}$$
- The *[[Curvature, Velocity and Acceleration#Curvature|curvature]]* $\kappa$ of the trajectory, the inverse of *radius of curvature* $\rho$ is defined by $$\frac{1}{\rho}=\kappa=\left\lvert \frac{d\hat{\tau}}{dl}\right\rvert$$
- Thus ${} \kappa v = |\hat{\dot{\tau}}| {}$, or ${} \hat{\dot{\tau}}= \kappa v\hat{n} {}$. Inserting these expressions for $\dot{l}$ and $\boldsymbol{\tau}$ into $\mathbf{a}$, one obtains $$\mathbf{a}=\kappa v^{2} \hat{n} + \ddot{l} \hat{\tau}$$
- The acceleration lies in the plane formed by $\boldsymbol{\tau}$ and $\mathbf{n}$, called the *osculating plane*.
- The unit vector $\hat{B}$ normal to the osculating plane is called the *[[Tangent and Normal Vectors#Binormal Vector|binormal vector]]*, is given by $$\hat{B} = \hat{\tau} \wedge \hat{n}$$
- Where the *[[Wedge Product|wedge]]* $\wedge$  stands for the cross product, often denoted by $\times$. The *wedge* is used extensively in [[Differential Geometry|differential geometry]].
- The [[Torsion|torsion]] $\theta(t)$ of the curve is defined by writing $\hat{\dot{B}}$ in the form $$\frac{d\hat{B}}{dl} = -\theta \hat{n}$$
- By [[Derivatives|differentiating]] $\hat{n}$ it can be shown that $$\bbox[15px, border:1px solid white]{\begin{array}
\dot{\tau}=\kappa \dot{l} \hat{n} \\ \dot{n}=-\kappa \dot{l} \hat{\tau} + \theta \dot{l} \hat{B}
\end{array}}$$These are known as the <u>Frenet-Serret Formuals</u>