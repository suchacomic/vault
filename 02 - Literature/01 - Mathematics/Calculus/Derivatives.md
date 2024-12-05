---
tags:
  - Calculus
  - Mathematics
  - derivatives
aliases:
  - diffrentiation
  - "#derivatives"
  - derivative
  - differentiate
cssclasses:
---
# Definition

- The derivative of $f(x)$ with respect to $x$ is the function $f'(x)$ and is defined as,$$
f'(x)=\lim_{ h \to 0 } f'(x)=\frac{f(x+h) -f(x)}{h}$$
- A [[Function|function]] $f(x)$ is **differentiable** at $x=a$, then f(x) is [[Continuity|continuous]] at $f=a$. 
- Differentiable functions are always continuous but not vice-versa for example, $f(x)=|x|$. For a continuous function to be differentiable the graph should not shave sharp edges.
# Properties
## General Properties

- $(f(x)\pm g(x))'=f'(x)\pm g'(x)$
- $(cf(x))'=cf'(x)$
- if $f(x)=c$ then $f'(x)=0$ 
- $f(x)=x^n$ then $f'(x)=nx^{n-1}$, $n$ is any number

## Product and Quotient Rule

- If the two functions $f(x)$ and $g(x)$ are differentiable then the product is differentiable and, 
$$(fg)^\prime=f'g+fg'$$
- If the two functions $f(x)$ and $g(x)$ are differentiable then the quotient is differentiable and, 
$$\left( \frac{f}{g} \right)'=\frac{f'g-fg'}{g^{2}}$$
# Chain Rule

- suppose that we have two functions $f(x)$ and $g(x)$ and they are both differentiable.
	
	1. if  we define $F(x)=(f \circ g)(x)$ then the derivative of $F(x)$ is,$$
F'(x)=f'(g(x))g'(x)
$$
	2. If we have $y=f(u)$ and $u=g(x)$ then the derivative of $y$ is,$$
\frac{dy}{dx}=\frac{dy}{du} \frac{du}{dx}

$$


## See also

- [[Limits]]
- [[Rate of Change and Tangent Line]]
- [[Common Derivatives]]
- [[Extremum in one Variable]]
- [[Monotonicity and Concavity]]