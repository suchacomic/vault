---
tags:
  - 3D_Space
  - Vector_Analysis
  - Mathematics
cssclasses:
  - center-images
aliases:
  - plane
---
- Assuming that we know a point that is in the plane $P_{0}=(x_{0},y_{0},z_{0})$. Let’s also suppose that we have a vector that is [[Tangent and Normal Vectors#Normal Vector|orthogonal]] to the plane , $\vec{n}=\langle a,b,c \rangle$ called [[Rate of Change and Tangent Line#Normal|normal]] vector.
- If $P=(x,y,z)$ is any point in the plane, let $\vec{r}_{0}$ and $\vec{r}$ be the position vectors for $P_{0}$ and $P$ respectively.
	![[Equation of Plane.png]]
- By [[Vector Operations#Addition of Vectors| vector law of addition]],$$
\begin{align}
\vec{r}&=\vec{r}_{0}+\overrightarrow{P_{0}P} \\
\overrightarrow{P_{0}P}&=\vec{r}-\vec{r}_{0}
\end{align}$$
- The [[Vector|vector]] $\vec{r}-\vec{r}_{0}$ lies completely in the plane and the vector $\vec{n}$ is orthogonal to the plane, and we know that [[Vector Operations#Dot Product|dot product ]] of orthogonal vectors is $0$,$$
\vec{n}\cdot(\vec{r}-\vec{r}_{0})=0 \hspace{0.25in}  \implies \hspace{0.25in}  \vec{n}\cdot \vec{r}=\vec{n}\cdot \vec{r}_{0}$$This is know as the **vector equation of the plane**.
- A slightly useful equation is as follows,$$\begin{align}
\langle a,b,c \rangle\cdot (\langle x,y,z \rangle -\langle x_{0},y_{0},z_{0} \rangle )&=0 \\
\langle a,b,c \rangle \cdot \langle x-x_{0},y-y_{0},z-z_{0} \rangle &= 0
\end{align}$$computing the dot product we get,$$

a(x-x_{0})+b(y-y_{0})+c(z-z_{0})=0$$This is called the **scalar equation of the plane.** Often this will be written as, $$
ax+by+cz=d$$where, $d=ax_{0}+by_{0}+cz_{0}$.
## See also

- [[Equation of Line]]
