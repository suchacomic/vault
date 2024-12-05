---
tags:
  - Mathematics
  - Vector_Analysis
aliases:
  - vector
cssclasses:
  - center-images
---
# Definition of Vector
- A vector can be represented geometrically by a directed line segment that starts at a point $A$, called the **initial point**, and ends at a point $B$, called the **terminal point**.
- Vectors are typically denoted with a boldface letter or when we’ve explicitly given the initial and terminal points we will often represent vectors with an arrow above the line segment,$$\mathbf{v}=\vec{v}=\overrightarrow{AB}$$![[Vector AB.png]]

- Vectors with the same direction and same magnitude (that is they are parallel and of the same length) are called **equivalent** even if their initial and terminal points are different.$$\mathbf{v}=\mathbf{u}$$
- Vectors can be in $\mathbb{R}^{2}$ or $\mathbb{R}^{3}$. Whereas in $\mathbb{R}$ we have scalars.

# Magnitude of A Vector
- The length of the arrow representing a vector $\vec{v}=\langle v_{1},v_{2},v_{3} \rangle$ is called the _length_ or **the magnitude** or the **norm** of $\vec{v}$, and is given by,$$v = \lvert \vec{v} \rvert = \sqrt{v_{1}^{2}+v_{2}^{2}+v_{3}^{2}}$$

![[Vector in 3d.png]]
- Given a vector $\mathbf{v}$ in 2-space or 3-space then $\lvert v \rvert\geq0$. Also, $\lvert v \rvert=0$ if and only if $\mathbf{v}=\mathbf{0}$.
# Scalar Multiple
- Suppose that $\mathbf{v}$ is a vector and $c$ is a non-zero scalar then the **scalar multiple**, $^{3}fv$ is a vector whole length is $|c|$ times the length of $\mathbf{v}$ and is in the direction of $\mathbf{v}$ if $c$ is positive and in the opposite direction of $\mathbf{v}$ is $c$ is negative.
# Unit Vector
- Any vector with magnitude of $1$, _i.e._ $\lvert \vec{u} \rvert=1$ is called a **unit vector**.
- Given a non-zero vector $\mathbf{v}$ in 2-space or 3-space define a new vector $\displaystyle \mathbf{u}=\frac{1}{\lvert \mathbf{v} \rvert}\mathbf{v}$, then $\mathbf{u}$ is a unit vector.
# Orthogonality 
- Unit vectors that obey the relationship $x_{i}y_{i}\delta_{ij}$ where $\delta$ is the [[Kronecker delta]]. 
- In other words, the [[Vector Operations#Dot Product|dot product]] of  any two unit vectors is $0$ unless they are the same vector. This is the **orthogonality** property of vectors, and [[Orthogonal Curvilinear Coordinates#Orthogonal Coordinate Systems|orthogonal coordinate systems]] are those in which all the unit vectors obey this properties.
## See also

- [[Vector Operations]]
- [[Vector Products]]