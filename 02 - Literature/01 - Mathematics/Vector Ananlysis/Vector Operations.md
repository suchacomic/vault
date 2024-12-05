---
tags:
  - Mathematics
  - Vector_Analysis
---

# Addition of Vectors
- Suppose that $\mathbf{v}$ and $\mathbf{w}$ are two [[Vector|vectors]] then to find the sum of the two vectors, denoted $\mathbf{v}+\mathbf{w}$, we position $\mathbf{w}$ so that its initial point coincides with the terminal point of $\mathbf{v}$. The new vector whose initial point is the initial point of $\mathbf{v}$ and whose terminal point is the terminal point of $\mathbf{w}$ will be the sum of the two vectors, or $\mathbf{v}+\mathbf{w}$.
	![[Vector addition.png]]
- From the sketch we can see that,$$\mathbf{v}+\mathbf{w}=\mathbf{w}+\mathbf{v}$$
- If $\mathbf{u},\mathbf{v},\mathbf{w}$ are vector in 2-space or 3-space and $c$ and $k$ are scalars then, 
	1. $\mathbf{u}+\mathbf{v}=\mathbf{v}+\mathbf{u}$
	2. $\mathbf{u}+(\mathbf{v}+\mathbf{w})=(\mathbf{u}+\mathbf{v})+\mathbf{w}$
	3. $\mathbf{u+0}=\mathbf{0+u}=\mathbf{u}$
	4. $\mathbf{u}-\mathbf{u}=\mathbf{u}+(-\mathbf{u}=\mathbf{0})$
	5. $1\mathbf{u}=\mathbf{u}$
	6. $(ck)\mathbf{u}=c(k\mathbf{u})=k(c\mathbf{u})$
	7. $(c+k)\mathbf{u}=c\mathbf{u}+k\mathbf{u}$
	8. $c(\mathbf{u}+\mathbf{v})=c\mathbf{u}+c\mathbf{v}$

# Dot Product 
- if $\mathbf{u}$ and $\mathbf{v}$ are two vectors in 2-space or 3-space and $\theta$ is the angle between then then the **dot product**, denoted by $\mathbf{u}\cdot \mathbf{v}$ is defined as, $$\mathbf{u}\cdot \mathbf{v}=\lvert \mathbf{u} \rvert \lvert \mathbf{v}\rvert \cos\theta$$
- Dot product is sometimes called the **scalar product** or the **Euclidean inner product**.
- Suppose the $\mathbf{u}=(u_{1},u_{2},u_{3})$ and $\mathbf{v}=(v_{1},v_{2},v_{3})$ are two vectors in 3-space then,$$\mathbf{u}\cdot \mathbf{v}=u_{1}v_{1}+u_{2}v_{2}+u_{3}v_{3}$$
- Two non-zero vectors, $\mathbf{u}$ and $\mathbf{v}$ are orthogonal if and only if $\mathbf{u}\cdot \mathbf{v}=0$ as for $\theta=\frac{\pi}{2},\ \cos\theta=0$
- Suppose that $\mathbf{u}$, $\mathbf{v}$ and $\mathbf{w}$ are three vectors that are all in 2-space or all in 3-space and that $c$ is a scalar. Then,
	1. $\mathbf{v}\cdot \mathbf{v}=\lvert \mathbf{v} \rvert^{2}$
	2. $\mathbf{u}\cdot \mathbf{v}=\mathbf{v}\cdot \mathbf{u}$
	3. $\mathbf{u}\cdot(\mathbf{v}+\mathbf{w})=\mathbf{u}\cdot \mathbf{v}+\mathbf{u\cdot \mathbf{w}}$
	4. $c(\mathbf{u}\cdot \mathbf{v})=(c\mathbf{u})\cdot \mathbf{v}$=$\mathbf{u}\cdot(c\mathbf{v})$
	5. $\mathbf{v}\cdot \mathbf{v}>0$ if $\mathbf{v}\neq 0$
	6. $\mathbf{v}\cdot \mathbf{v}=0$ if and only id $\mathbf{v=0}$

# Cross Product
- if $\mathbf{u}=\langle u_{1},u_{2},u_{3} \rangle$ and $\mathbf{v}=\langle v_{1},v_{2},v_{3} \rangle$ are the vectors in 3-space then the **cross product**, denoted by $\mathbf{u}\times \mathbf{v}$ and is defined in one of three ways.
	1. $\mathbf{u}\times \mathbf{v}=(u_{2}v_{3}-u_{3}v_{2},u_{3}v_{1}-u_{1}v_{3},u_{1}v_{2}-u_{2}v_{1})$ - Vector notation
	2. $\displaystyle \mathbf{u}\times \mathbf{v}=\left (\begin{vmatrix} u_{2} & u_{3} \\ v_{2} & v_{3}\end{vmatrix}, \begin{vmatrix} u_{1} & u_{3} \\ v_{1} & v_{3} \end{vmatrix},\begin{vmatrix} u_{1} & u_{2} \\ v_{1} & v_{2} \end{vmatrix} \right)$ - Using 2x2 [[determinants]]
	3. $\displaystyle \mathbf{u}\times \mathbf{v}=\begin{vmatrix} \mathbf{x} & \mathbf{y} & \mathbf{z} \\ u_{1} & u_{2} & u_{3} \\ v_{1} & v_{2} & v_{3} \end{vmatrix}$ - Using 3x3 determinants
- Suppose that $\mathbf{u}$ and $\mathbf{v}$ are vectors in 3-space and let $\theta$ be the angle between them then,$$
\lvert \mathbf{u}\times \mathbf{v} \rvert =|\mathbf{u}|\ |\mathbf{v}|\ \sin\theta$$
- Suppose $\mathbf{u},\mathbf{v}$ and $\mathbf{w}$ are vectors in 3-space and $c$ is any scalar then
	1. $\mathbf{u}\times \mathbf{v}=-(\mathbf{v}\times \mathbf{u})$
	2. $\mathbf{u}\times(\mathbf{v}+\mathbf{w})=(\mathbf{u}\times \mathbf{v})+(\mathbf{u}\times \mathbf{w})$
	3. $(\mathbf{u}+\mathbf{v})\times \mathbf{w}=(\mathbf{u}\times \mathbf{w})+(\mathbf{v}\times \mathbf{w})$
	4. $c(\mathbf{u}\times \mathbf{v})=(c \mathbf{u})\times \mathbf{v}=\mathbf{u}\times(c \mathbf{v})$
	5. $\mathbf{u}\times \mathbf{0}=\mathbf{0}\times \mathbf{u}=\mathbf{0}$
	6. $\mathbf{u}\times \mathbf{u}=\mathbf{0}$
## See also

- [[Vector Products]]