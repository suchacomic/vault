---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Bound System
- A bounded system has negative total energy.
- The kinetic energy required to overcome the potential energy is greater than that of the particle in the system. 
- The particle is thus restricted to some finite space due to the potential barrier.
# Small Oscillations in a Bound System

![[99 - Meta/02 - Excalidraw/Drawings/ED-bounded_system.excalidraw]]

- Suppose we have a particle at the [[Extremum in Multi-Variables|local minima]] near $r_{0}$ of a potential function $U(r)$, then for small [[Oscillations|oscillation]] near $r_{0}$ the potential function can be expanded using [[Taylor’s series]].$$U(r)=U(r_{0})+(r-r_{0}) \frac{dU}{dr}\Bigg|_{r_{0}}+\frac{1}{2} (r-r_{0})^{2} \frac{d^{2}U}{dt^{2}}\Bigg|_{r_{0}}+\dots$$
- As $U$ has a minima at $r_{0}$, it is [[Extremum in one Variable#Stationary Points|stationary point]], $dU/dr=0$ at $r_{0}$.
- Furthermore for sufficiently small displacements, we can neglect terms beyond the third in the power series. In this case $$U(r)\approx U(r_{0})+\frac{1}{2} (r-r_{0})^{2}\, \frac{d^{2}U}{dt^{2}}\Bigg|_{r_{0}}$$
- This is the potential energy of a [[Simple Harmonic Oscillators|harmonic oscillator]], $$U(x)=\text{constant}+\frac{1}{2}k(x-x_{o})^{2}$$Comparing the two equation, we identify the effective spring constant in the bound system as $$k=\frac{d^{2}U}{dt^{2}}\Bigg|_{r_{o}}$$