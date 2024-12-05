---
tags:
  - Calculus
  - integration
  - Mathematics
---
# Infinite Interval
- In this kind of integral one or both of the [[limits]] of [[Integrals|integration]] are infinity.
- To deal with these kind of integrals in general we replace the infinity with a variable(usually $t$), do the integral and then take the limit if the result as $t\to \infty$.
- There are three essential cases,

	1. if $\displaystyle \int_{a}^{t} f(x) \, dx$ exists for every $t>a$ then,$$\int_{a}^{\infty} f(x) \, dx = \lim_{ n \to \infty } \int_{a}^{t} f(x) \, dx$$provided the limit exists and is finite.
	2. if $\displaystyle \int_{t}^{b} f(x) \, dx$ exists for every $t<b$ then,$$\int_{-\infty}^{b} f(x) \, dx = \lim_{ n \to -\infty }\int_{t}^{b}  \, dx$$provided the limit exists and is finite.
	3. if $\displaystyle \int_{-\infty}^{c} f(x) \, dx$ and $\displaystyle \int_{c}^{\infty} f(x) \, dx$ are both convergent then,$$\int_{-\infty}^{\infty} f(x) \, dx =\int_{-\infty}^{c} f(x) \, dx + \int_{c}^{\infty} f(x) \, dx $$where $c$ is any number. 
- If $a>0$ then $$
\int_{a}^{\infty} \frac{1}{x^{p}} \, dx$$is [[Convergence and Divergence|convergent]] if $p>1$ and [[Convergence and Divergence|divergent]] if $p\leq 1$.

# Discontinuous Integrand

- If $f(x)$ is [[Continuity|continuous]] on the interval $[a,b)$ and not continuous at $x=b$ then,$$\int_{a}^{b} f(x) \, dx =\lim_{ t \to b^- } \int_{a}^{t} f(x) \, dx $$provided the limit exists and is finite.

- If $f(x)$ is continuous on the interval $(a,b]$ and not continuous at $x=a$ then,$$\int_{a}^{b} f(x) \, dx =\lim_{ t \to a^+ } \int_{t}^{b} f(x) \, dx $$provided the limit exists and is finite.

- if $f(x)$ is not continuous at $x=c$ where $a<c<b$ and $\displaystyle \int_{a}^{c} f(x) \, dx$ and $\displaystyle \int_{c}^{b} f(x) \, dx$ are both convergent then,$$\int_{a}^{b} f(x) \, dx =\int_{c}^{a} f(x) \, dx +{ \int_{c}^{b} f(x) \, dx }$$

# Comparison Test
if $f(x) \geq g(x) \geq 0$ on the interval $[a,\infty)]$ then,
1. if $\displaystyle \int_{a}^{\infty} f(x) \, dx$ converges then so does $\displaystyle\int_{a}^{\infty} g(x) \, dx$
2. if $\displaystyle \int_{a}^{\infty} gx \, dx$ diverges then so does $\displaystyle \int_{a}^{\infty} f(x) \, dx$
## See also

- [[Limits, Infinities and Asymptotes]]
- [[Definite Integrals]]
- [[Integrals]]
- [[Convergence and Divergence]]