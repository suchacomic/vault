---
tags:
  - Calculus
  - derivatives
  - integration
  - Vector_Analysis
  - Mathematics
aliases:
  - Gauss's theorem
  - Green's theorem
  - divergence theorem
---
# Fundamental Theorem for Volume Integrals and Divergence
- This Theorem has at least three special names: **Gauss’s theorem**,**Green’s theorem** or simply the **divergence theorem**.
- Suppose we have [[Vector Fields|vector field]] $\vec{F}$ whose components have [[Continuity|continuous]] [[Partial Derivatives|first order partial derivatives]] and that $\mathcal{V}$ is a [[Curves and Regions|simple]] solid region and $\mathcal{S}$ is the boundary surface of $\mathcal{V}$ with positive orientation. Then,$$\iiint\limits_{\mathcal{V}}(\nabla\cdot \vec{F})\,d\tau= \oint\limits_{\mathcal{S}}\vec{F}\cdot d\vec{a}$$
- The [[Triple Integrals|volume integral]] of the [[Divergence|divergence]] over a volume $\mathcal{V}$ is equal to the value of the function at the boundary, that is a surface enclosing the volume $\mathcal{S}$.
# Geometric Interpretation 
- If $\vec{F}$ represents the flow of an in-compressible fluid, then the flux of $\vec{F}$ given by the closed [[Double Integrals|surface integral]] is the total amount fluid passing through the boundary, whereas the divergence measures the “spreading out” of vectors or the amount of sources in the volume $\mathcal{V}$.
- There are thus two ways we could determine how much fluid is being produced:
	- Count up all the sources, and record how much is being produced in the volume as is done by the volume integral.
	- We could go around the boundary, measuring the flow at point and add it up as is done by the surface integral. $$\int \text{(Sources within the volume)}=\oint \text{(flow out through the surface})$$
# See also

- [[The Fundamental Theorem for Surface Integrals and Curls]]
- [[The Fundamental Theorem for Line Integrals and Gradients]]