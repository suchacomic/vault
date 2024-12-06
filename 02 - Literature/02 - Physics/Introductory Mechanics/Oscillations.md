---
tags:
  - Introductory_Mechanics
  - Physics
cssclasses:
  - center-images
---
# Oscillations
- The energies in some regimes of motion often have quadratic forms $$\begin{align} U &= \frac{1}{2}Aq^{2}+\text{constant} \\ K &= \frac{1}{2}B\dot{q}^{2}, \end{align} \tag{1}$$where $q$ represents a variable appropriate to the problem.
- For the elementary case of a [[Simple Harmonic Oscillators|mass on a spring]] we have $$\begin{align} U &= \frac{1}{2}kx^{2} \\ K &= \frac{1}{2}m\dot{x}^{2}\end{align}$$and $$\omega=\sqrt{ \frac{k}{m} }$$
- By this analogy, the angular frequency of the system described by equations in $(1)$ is $$\omega=\sqrt{ \frac{A}{B} }$$
- To explicitly prove that any system whose energy has the form of equations $(1)$ oscillates harmonically with frequency $\sqrt{ A/B }$, we take the total energy, $$\begin{align} E &= K+U  \\ &= \frac{1}{2}B\dot{q}^{2}+\frac{1}{2}Aq^{2} +\text{constant}\end{align}$$Because the system is conservative, $E$ is constant. Differentiating the energy equation with respect to time gives $$ \begin{align} \frac{dE}{dt} &= B\dot{q}\ddot{q}+Aq\dot{q}  \\ &= 0 \end{align} $$or $$\ddot{q}+\frac{A}{B}q=0$$Which is the equation of a [[Simple Harmonic Oscillators|harmonic oscillator]], hence $q$ undergoes harmonic oscillation with angular frequency $\sqrt{ A / B }$.
# Example 

 ![[99 - Meta/02 - Excalidraw/Drawings/ED-simple_pendulum.excalidraw]]
 - The velocity of the bob is given by, $$\begin{align} v &= (\text{arc lenght})' \\ &= (l\theta)'=l\dot{\theta} \end{align}$$

 - The [[Taylor’s series|Taylor expansion]] for $\cos\theta$ is,$$\cos\theta=1-\frac{\theta^{2}}{2!}+\frac{\theta^{4}}{4!}-\frac{\theta^6}{6!}+\dots=\sum_{i=0}^{\infty} \frac{(-1)^{n}}{(2n)!} \theta^{2n}$$and $$1-\cos\theta \approx \frac{\theta^{2}}{2}$$
- The energies of the pendulum are, $$\begin{align} U &= mgh=mgl(1-\cos\theta) \approx \frac{1}{2} mgl\theta^{2} \\ K &= \frac{1}{2}ml^{2}\dot{\theta}^{2} \end{align}$$
- The angular frequency $\omega$ is $$\omega=\sqrt{ \frac{A}{B} }=\sqrt{ \frac{gl}{l^{2}}}=\sqrt{ \frac{g}{l}}$$
