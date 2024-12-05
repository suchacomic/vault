---
tags:
  - Calculus
  - derivatives
  - Vector_Analysis
  - Mathematics
---
Suppose we have a vector $\vec{r}(t)=\langle f(t),g(t),h(t) \rangle$.
# Limits 
The [[Limits|limit]] is given by,
$$
\begin{align}
\lim_{ t \to a } \vec{r}(t) &= \lim_{ t \to a } \langle f(t),g(t),h(t) \rangle \\
&= \langle \lim_{ t \to a } f(t),\lim_{ t \to a } g(t),\lim_{ t \to a } g(t) \rangle  \\
&= \lim_{ t \to a } f(t)\hat{x}+\lim_{ t \to a } g(t)\hat{y}+\lim_{ h \to a }h(t)\hat{z}
\end{align}
$$
# Derivative
- The [[Derivatives|derivative]] of $\vec{r}(t)$ is,$$
\vec{r}'(t)=\frac{d}{dt} f(t)\hat{x}+\frac{d}{dt} g(x)\hat{y}+\frac{d}{dt} h(t)\hat{z}
$$
- Most of the basic facts about derivatives hold,
	1. $\displaystyle \frac{d}{dt}(\vec{u} \cdot \vec{v})=\vec{u}'\cdot \vec{v}+\vec{u}+\vec{v}'$
	2. $\displaystyle \frac{d}{dt}(\vec{u}\times \vec{v})=\vec{u}'\times \vec{v}+\vec{u}\times \vec{v}'$
# Integral 
- A **smooth curve** is any curve for which $\vec{r}'(t)$ is continuous and $\vec{r}'(t)\neq 0$ for any $t$ except possibly at endpoints.
- [[Integrals|Integration]] of $\vec{r}(t)$ is given by,$$
\int \vec{r}(t) \, dt =\left\langle  \int f(t) \, dt ,\int g(t) \, dt ,\int h(t) \, dt   \right\rangle + \vec{c}
$$
- [[Definite Integrals| Definite integral]] of $\vec{r}(t)$ is,$$
\int_{a}^{b} \vec{r}(t) \, dt = \left\langle  \int_{a}^{b} f(t) \, dt ,\int_{a}^{b} g(t) \, dt ,\int_{a}^{b} h(t) \, dt  \right\rangle 
$$or, it is sometimes written as,$$
	\int_{a}^{b} \vec{r}(t) \, dt = \left( \left\langle  \int f(t) \, dt,\int g(t) \, dt,\int h(t)\,dt   \right\rangle  \right)\Bigg|_{a}^b
$$
