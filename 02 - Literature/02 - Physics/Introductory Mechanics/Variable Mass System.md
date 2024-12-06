---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Variable Mass System 

![[ED-variable_mass_system.excalidraw]]
- Suppose the system of mass $m$ moving with [[Displacement, Velocity and Acceleration#Velocity Vector|velocity]] $v$ and is its mass is changing at the rate $\Omega=\dfrac{dm}{dt}$.
- From [[Newton's Laws of Motion#Newton’s Second law|Newton’s second law]],  $$ \begin{align}
\sum \mathbf{F}^e &= \frac{d\mathbf{P}}{dt} \\
&= \frac{d}{dt}(m\mathbf{v})
\end{align} $$
- By [[Derivatives#Chain Rule|chain rule]], $$\bbox[15px, border:1px solid white]{\sum \mathbf{F}^e = m\frac{d\mathbf{v}}{dt}+\mathbf{v} \frac{dm}{dt}}$$If there are no external [[Fundamental Forces|force]] acting on the system is zero,$$\begin{align} 0&=\frac{dm}{dt} \mathbf{v}+m \frac{d\mathbf{v}}{dt} \\ m \frac{d\mathbf{v}}{dt} &= -\frac{dm}{dt} \mathbf{v} \\ m\mathbf{a} &= -\Omega \mathbf{v}  \\
\end{align}$$Where $\Omega$ is the [[Rate of Change and Tangent Line|rate of change]] of the mass of the system, and the force on the left hand sided is called the **thrust force**.$$\bbox[15px, border:1px solid white]{\mathbf{F}_{\text{thrust}}=m\mathbf{a}=-\Omega \mathbf{v}=-\frac{dm}{dt}\mathbf{v}}$$
# Rocket Motion 

![[ED-rocket_motion.excalidraw]]
- Consider the rocket shown, with mass $m$, travelling in the positive $x$ direction and ejecting mass.
- At time $t$, the momentum is $\mathbf{P}(t)=mv$, a short time later at $t+dt$, the rocket’s mass is $m+dm$, where $dm$ is negative, and its momentum is $(m+dm)(v+dv)$.
- By the [[Conservation of Momentum|conservation of momentum]], $$\begin{align}
\mathbf{P}(t+dt)&=(m+dm)(v+dv)-dm(v-v_{ex}) \\ &=mv+m\,dv+dm\,v_{ex} \end{align}$$neglecting the small product $dm\,dv$.
- The change in total momentum is $$dP=P(t+dt)-P(t)=m\,dv+dm\,v_{ex}$$
- If net external force $\mathbf{F}^e$ (gravity, for instance), is zero, $P$ is constant and thus $dP=0$. Therefore,$$m\,dv=-dm\,v_{ex}$$Dividing both sides by $dt$,$$F_{\text{thrust}}=m\dot{v}=-\dot{m}v_{ex}$$where $-\dot{m}$ is the [[Rate of Change and Tangent Line|rate]] at which rocket is ejecting mass.
- Dividing both sides by $m$ gives,$$dv=-v_{ex}\frac{dm}{m}$$If the exhaust speed is constant, this equation can be [[Integrals|integrated]] to give $$v-v_{0}=v_{ex}\ln\left( \frac{m_{0}}{m} \right)$$where $v_{0}$ is the initial velocity and $m_{0}$ is the initial mass of the rocket.
 