---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Hooke’s Law

![[99 - Meta/02 - Excalidraw/Drawings/ED-block_and_spring.excalidraw]]
- The restoring force exerted by the spring on the mass $m$ when displaced from the equilibrium by $x$ is given by,$$F_{x}(x)=-kx \tag{1}$$This is called **Hooke’s Law**.
- An exact equivalent way to state Hooke’s law id that the potential energy is $$U(x)=\frac{1}{2}kx^{2} \tag{2}$$
- The constant $k$ is a positive constant called the force constant. 
# Simple Harmonic Motion 
- If the only force on the spring-block system is the restoring force provided by the spring, then by the [[Newton's Laws of Motion#Newton’s Second law|Newton’s second law]], $$\begin{align}
m\ddot{x}&=F_{x}(x)=-kx \\
\ddot{x} &= -\frac{k}{m}x
\end{align}$$
- Introducing a new constant $\omega$ called the angular frequency with which the block will oscillate, $$\omega=\sqrt{ \frac{k}{m} }$$The time period of oscillation is, $$T=\frac{2\pi}{\omega}=2\pi \sqrt{ \frac{m}{k} }$$
- Substituting $\omega$  into the [[differential equation]] we get, $$\ddot{x} =- w^{2}x$$$$\bbox[15px, border:1px solid white]{\ddot{x}+w^{2}x=0 }$$This is the differential equation describing the motion of a simple harmonic oscillator. 
# Solution to the Spring-Block System
- From the equation of the oscillator,$$\begin{align} \frac{dv}{dt} &=- \Omega^{2}x \\ \\  \frac{dv}{dt}\cdot \frac{dx}{dt}&= -\omega^{2}x \frac{\,dx}{dt} \\ \\  v\,dv &= -\omega^{2}x\,dx \end{align}$$If the block at $x_{0}=x$ with velocity $v_{0}=v$ and the maximum displacement called **the amplitude** is $x_{\text{max}}=A$, the velocity at $A$ is $0$ is . [[Integrals|Integrating]] with those limits, $$\begin{align} \int_{v}^{0}v\, dv &= \int_{0}^{A} -\omega^{2}x \, dx \\ \frac{v^{2}}{2}\Bigg|_{v}^{0} &= -\omega^{2} \frac{x^{2}}{2}\Bigg|_{x}^{A} \\ \\ v^{2} &= \omega^{2}(A^{2}-x^{2}) \\v &= \omega\sqrt{ A^{2}-x^{2} } \end{align}$$
- Thus the velocity as a function of time is given by $$\bbox[15px, border:1px solid white]{v=\omega \sqrt{ A^{2}-x^{2} }}$$
- Using the equation above to find $x$, $$\begin{align}
\frac{dx}{dt} &= \omega^{2}\sqrt{ A^{2}-x^{2} } \\ \\
\frac{dx}{\sqrt{ A^{2}-x^{2} }}&=\omega\, dt
\end{align}$$
- Integrating this, $$\begin{align}
\int \frac{dx}{\sqrt{ A^{2}-x^{2} }} \, dx &= \int\omega  \, dt  \\
\sin^{-1}\left( \frac{x}{A} \right) &= \omega\,t + \phi\\
\end{align}$$where $\phi$ is the constant of integration called the **phase**,
 $$\bbox[15px, border:1px solid white]{x=A\sin(\omega\,t + \phi)}$$
 - [[Derivatives|Differentiating]] the above equation to obtain the velocity and the acceleration as a function of time, $$\bbox[15px, border:1px solid white]{\begin{align}
v &=A\,\omega\,\cos(\omega\,t+\phi)\ \\
a &= -A\,\omega^{2}\sin(\omega\,t+\phi) = -\omega^{2}x
\end{align}}$$
