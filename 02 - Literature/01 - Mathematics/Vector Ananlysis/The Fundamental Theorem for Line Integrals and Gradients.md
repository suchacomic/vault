---
tags:
  - derivatives
  - Calculus
  - Mathematics
  - Vector_Analysis
  - integration
---
# # The Fundamental Theorem for Line Integrals and Gradients
- Suppose we have a scalar function of three variables $f(x,y,z)$ and that $\mathcal{P}$ is a smooth curve given by $\vec{r}(t), a\leq t\leq b$. Starting at point $a$, we move a small distance $d\vec{r}_{1}$, the function will change; following the [[Partial Derivatives#Chain Rule|chain rule]] and [[Gradient#Gradient in Cartesian Coordinates|gradient]], by an amount $$df=(\nabla f)\cdot d\vec{r_{1}}$$
- In this manner, proceeding by infinitesimal steps, we make the journey to point $b$, at each step compute the gradient and [[Vector Operations#Dot Product|dot]] it into the displacement $d\vec{r}$, $$\int_{\vec{r}(a)}^{\vec{r}(b)} (\nabla f)\cdot d\vec{l} =f(\vec{r}(b))-f(\vec{r}(b))$$
- This is called the **fundamental theorem for gradients**. 
- The line integrals ordinarily depend on the path taken form $a$ to $b$, the right side makes no reference to path taken only end points. Evidently, gradients have a special properties that their [[Line Integrals|line integrals]] are <u>path independent</u>.
## Geometric Interpretation
- If we want to measure the height of a tower we could climb the stairs, using a ruler to measure the rise at each step as is done by the integral, or we could place altimeters at the top and the bottom, and subtract the two reading as done on the right side.
# Corollaries
1. $\displaystyle \int\limits_{\mathcal{P}} (\nabla f)\cdot d\vec{r}$ is independent of the path taken from $\vec{a}$ to $\vec{b}$.
2. $\displaystyle \oint(\nabla f)\cdot d\vec{r}=0$, since the beginning and end points are identical for [[Line Integrals#Closed Loop Integrals|closed loop integrals]], and hence $f({\vec{r}(b)})-f(\vec{r}(a))=0$