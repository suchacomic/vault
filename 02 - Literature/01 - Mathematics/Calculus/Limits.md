---
tags:
  - Mathematics
  - Calculus
aliases:
  - limit
---
# Definitions

- We say that the limit of [[Function|function]] $f(x)$ is $L$ as $x$ approaches $a$, $$\lim _{ a \to 0 }f(x) = L$$
provided we can make $f(x)$ as close to $L$ as we want for all $x$ sufficiently close to $a$, from <u>both sides</u>, without actually letting $x$ be $a$.

- Given a function $f(x)$ if, $$\lim_{ x \to a^+} f(x) = \lim_{ x \to a^- } f(x) = L$$then the normal limit will exist and $$\lim_{ x \to a } f(x) =L$$

# Properties

# Theorems

1. If $f(x)\leq g(x)$ for all $x$ on $[a,b]$ (except possibly at $x=c$ ) and $a\leq v\leq b$ then,$$\lim_{ x \to c } f(x)\leq \lim_{ x \to c } g(x)
$$
2. **Squeeze Theorem** supposes that for $x$ on $[a,b]$ (except possibly at $x=c$ ) we have,$$f(x)\leq h(x)\leq g(x))$$Also suppose that,$$\lim_{ x \to c } f(x)=\lim_{ x \to c } g(x)=L$$for some $a\leq c\leq b$. Then,$$\lim_{ x \to c } h(x) = L$$

![[squeeze_thm.png]]

## See also

- [[Function|function]]
- [[sets]]
- [[Limits, Infinities and Asymptotes]]
- [[L'Hospital's Rule and Indeterminate Forms]]