---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - Vector_Analysis
---
# Tangent Vector 
- Given a [[Vector|vector]] function $\vec{r}(t)$, we call $\vec{r}'(t)$ the [[Rate of Change and Tangent Line#Tangent|tangent]] vector, provided it [[Continuity|exists]] and provided $\vec{r}'(t)\neq 0$.
- The tangent line to $\vec{r}(t)$ at $P$ is then the line that passes through the point $P$ and is parallel to the tangent vector $\vec{r}'(t)$.
- The [[Vector#Unit Vector|unit]] tangent vector to the curve is given by,$$
\overrightarrow{T}(t)=\frac{\vec{r}'(t)}{\lvert \vec{r}'(t) \rvert }$$
# Normal Vector 
	- Suppose that $\vec{r}'(t)$ is a vector such that $|\vec{r}'(t)|=c$ for all $t$. Then $\vec{r}(t)$ is orthogonal to $\vec{r}(t)$.
- The unit [[Rate of Change and Tangent Line#Normal|normal]] vector is defined to be,$$
\overrightarrow{N}(t)=\frac{\overrightarrow{T'}(t)}{|\overrightarrow{T'}(t)|}
$$
- The unit normal vector is orthogonal to the unit tangent vector and hence the curve as well.
- Normal vector to a curve to a curve in a scalar form at a point can also be obtained by taking the [[Gradient|gradient]] at that point. 
# Binormal Vector 
- The Binormal vector is defined to be,$$
\overrightarrow{B}(t)=\overrightarrow{T}(t)\times \overrightarrow{N}(t)
$$
- Binormal Vector is orthogonal to both tangent vector and the normal vector.
