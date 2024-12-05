---
tags:
  - 3D_Space
  - Mathematics
  - Vector_Analysis
cssclasses:
  - center-images
---
# Equation of Line in 2-dimensions
- The standard form of line in $\mathbb{R}^{2}$ are,$$
Ax+B=C
$$here $A$ and $B$ can be zero but not simultaneously.
- The equation of line described by two points $P_{1}=(x_{1},y_{1})$ and $P_{2}=(x_{2},y_{2})$ is,$$y-y_{1}=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}\, x-x_{1}$$
- The [[Rate of Change and Tangent Line#Tangent|slope]] of the line $m$ , that is the measure of the *steepness* is,$$m=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}$$
- The slope-intercept form of the line is,$$
y-y_{1}=m(x-x_{2})
$$where, $m$ is the slope of the line and the line passes through the point $(x_{1},y_{1})$
- If the line has slope $m$ and $y$-intercept $(0,c)$ then the slope-intercept form of the line is,$$y=mx+c$$
# Equation of Line in 3-Dimensions
- The equation $y=mx+c$ in $\mathbb{R}^{3}$ <u>does not</u> describe a line but a [[Equation of Plane|plane]].
- In two dimension we need the slope ($m$) and a point that was on the line in order to write down the equation, in $\mathbb{R}^{3}$ we still need all that except in this case “slope” won’t be a simple number as it was in $\mathbb{R}^{2}$ but a [[Vector|vector]] that represent the three dimensional slope.
- Suppose that we know a point that is on the line, $P_{0}=(x_{0},y_{0},z_{0})$, and that $\vec{v}=\langle a,b,c \rangle$ is some vector that is parallel to the line. The slope is represented by the vector $\vec{v}$.
- Let $P=(x,y,z)$ be any point on the line and $\vec{r}_{0}$ and $\vec{r}$ be the position vector for $P_{0}$ and $P$ respectively.
- Let $\vec{a}$ be the vector with representation $\overrightarrow{P_{0}P}$.
	![[Eqn of line.png]]
- By the vector law of [[Vector Operations#Addition of Vectors|addition]], $$
\vec{r}=\vec{r}_{0}+\vec{a}$$
- $\vec{a}$ and $\vec{t}$ are parallel, therefore there is a number $t$, such that $$
\vec{a}=t\, \vec{v}$$
- We now have,$$
\vec{r}=\vec{r}_{0}+t\,\vec{v}=\langle x_{0},y_{0},z_{0} \rangle +t\, \langle a,b,c \rangle $$This is called the **vector form of the equation of a line**. As $t$ varies over all possible values we will completely cover the line.
- The only way two vectors are equal is for the components to be equal,$$\begin{align}
x&=x_{0}+ta \\
y&=y_{0}+tb \\
z&=z_{0}+tc
\end{align}$$This set of equation is called the **[[Parametric Equations and Curves|parametric]] form of the equation of a line**.
- Assuming $a,b$ and $c$ are all non-zero numbers, $$
\frac{x-x_{0}}{a}=\frac{y-y_{0}}{b}=\frac{z-z_{0}}{c}$$This is called the **symmetric equation of the line**.
 
- [[Tangent and Normal Vectors]]
- [[Rate of Change and Tangent Line]]