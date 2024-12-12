---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Moment of Inertia
- In [[Fixed Axis Rotation|fixed axis rotation]] the [[Conservation of Angular Momentum#Angular Momentum|angular momentum]] $L_{z}=\sum m_{j}\rho^{2}_{j}\omega$ can be written as, $$L_{z}=I\omega$$where $I\equiv \sum_{j}m_{j}\rho_{j}^{2}$
- $I$ is a geometric quantity called the **moment of inertia**. $I$ depends on the distribution of mass in the body with respect to the axis of rotation.
- This reveals a close analogy between [[Conservation of Angular Momentum|angular momentum]] and [[Conservation of Momentum#Momentum|linear momentum]] along an axis $P=Mv$. The moment of inertia plays the same role in rotational motion that mass plays in linear momentum.
- For continuously distributed matter, the [[Limits|limit]] of number of particles tends to infinity, and we get a [[Area Under the Curve#Riemann Sum|Riemann sum]] $$\lim_{ n \to \infty } \sum_{j}^{n} m_{j}\rho_{j}^{2}=\int \rho^{2}\,dm,$$and $$\bbox[15px, border:1px solid white]{I=\int \rho^{2}\,dm}$$ $$I=\int (x^{2}+y^{2})\,dm$$
# Axis Theorems

![[99 - Meta/02 - Excalidraw/Drawings/ED-moi_theorems.excalidraw]]

## Parallel Axis Theorem
- $I$, the moment of inertia around any axis, provided that we know $I_{0}$, the moment of inertia around an axis through the [[Center of Mass|center of mass]] parallel to the first is given by $$I=I_{0}+Ml^{2}$$where the mass of the body is $M$ and the distance between the axes is $l$
## Perpendicular Axis Theorem 
- Suppose a 2 dimensional pancake object is located in the $x$-$y$ plane then, $$I_{z}=I_{x}+I_{y}$$
# See also
- [[Moment of Inertia]]
- [[Motion in Polar Coordinates]]