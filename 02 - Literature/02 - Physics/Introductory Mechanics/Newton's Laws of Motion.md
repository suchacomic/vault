---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Inertia
- The mass of an object characterizes the object’s inertia —its resistance to being [[Displacement, Velocity and Acceleration#Acceleration|accelerated]]: A large mass is harder to accelerate, whereas a smaller mass is easier. 
- **Inertia** is the natural tendency of objects in motion to stay in motion and objects at rest to stay at rest, unless a [[Fundamental Forces|force]] causes the [[Displacement, Velocity and Acceleration#Velocity Vector|velocity]] to change.
# Newton’s First Law
- In absence of forces, a particle moves with constant velocity.
- This is also called as **The Law of Inertia**.
- It is also the assertion that [[Reference Frame#Inertial Reference Frame|inertial systems]] exist.
# Newton’s Second law
- For any particle of mass $m$, the net force $\mathbf{F}$ on the particle is always equal to the mass $m$ times the particle’s acceleration:$$\bbox[15px, border:1px solid white]{\mathbf{F}=m\mathbf{a}}$$Where $\mathbf{F}$ denotes the [[Vector|vector]] sum of all the forces on the particle and $\mathbf{a}$ is the particle’s acceleration,$$\begin{align}
\sum \mathbf{F}&=m\mathbf{a}=m\dot{\mathbf{v}}=m\ddot{\mathbf{r}} \\
\end{align}$$
- The second law can be rephrased in terms of the particle’s **momentum**, defined as $$\mathbf{p}=m\mathbf{v}$$Assuming mass $m$ of a particle never changes, so that $$\dot{\mathbf{p}}=m\dot{\mathbf{v}}=m\mathbf{a}$$Thus the second law can be rephrased to say that $$\bbox[15px, border:1px solid white]{\mathbf{F}=\dot{\mathbf{p}}}$$
# Differential Form of the Second law
- When written in the form $m\mathbf{\ddot{r}}=\mathbf{F}$, Newton’s second law is a  [[differential equation]] for the particle’s position $\mathbf{r}(t)$. 
- Consider Newton’s second law for a particle confined to move along the $x$ axis and subject to a constant force $F_{0}$, $$\ddot{x}(t)=\frac{F_{0}}{m}$$This is a [[second-order differential equation]] for $x(t)$ as a function of $t$. Integrating it twice. The first integration gives the [[Displacement, Velocity and Acceleration#Velocity Vector|velocity]]$$
\dot{x}(t)=\int \ddot{x} \, dt=v_{0}+\frac{F_{0}}{m}t $$where the constant of integration is the particle’s initial velocity, and a second integration gives the position $$x(t)=\int \dot{x}(t) \, dt =x_{0}+v_{0}t+\frac{F_{0}}{2m}t^{2}$$where the constant of integration is the particle’s initial position.
# Newton’s Third Law of Motion 
![[ED-newtons_third_law.excalidraw]]
- If object 1 exerts a force $\mathbf{F}_{21}$ on object 2, then object 2 <u>always</u> exerts a reaction force $\mathbf{F}_{12}$ on object 1 given by $$\mathbf{F}_{12}=-\mathbf{F}_{21}$$
- Also stated as “Every action has an equal and opposite reaction”. Though the definition of action is vague.
