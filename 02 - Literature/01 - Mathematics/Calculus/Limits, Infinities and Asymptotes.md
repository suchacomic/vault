---
tags:
  - Calculus
  - Mathematics
---
# Infinite [[Limits]]

- We say $$ \lim_{ a \to a } f(x)=\infty$$
if we can make $f(x)$ arbitrarily large for all $x$ sufficiently close to $x=a$, from both sides, without actually letting $x=a$.

- We say $$\lim_{ x \to a } f(x)=-\infty $$
if we can make $f(x)$ arbitrarily large and negative for all $x$ sufficiently close to $x=a$, from both sides, without actually letting $x=a$.   
## Properties of Infinite Limits
Given the functions $f(x)$ and $g(x)$ suppose we have,

$$\lim_{ x \to c } f(x) = \infty \hspace{1.0in} \lim_{ x \to c } g(x)=L$$
for some real numbers $c$ and $L$. Then,
1. $\displaystyle \lim_{ x \to c }[f(x)\pm g(x)=\infty]$
2. if $L>0$ then $\displaystyle \lim_{ x \to c }[f(x)\ (g)x]=\infty$
3. if $L<0$ then $\displaystyle \lim_{ x \to c }[f(x)\ g(x)]=-\infty$
4. $\displaystyle \lim_{ x \to c }{\frac{g(x)}{f(x)}}=0$
# Limits at Infinity

1. If $r$ is a positive rational number and $c$ is any real number then,$$
\lim_{ x \to \infty } \frac{c}{x^{r}}=0$$

2. If $r$ is a positive rational number, $c$ is any real number and $x^{r}$ is defined for $x<0$ then,$$
\lim_{ x \to -\infty } \frac{c}{x^{r}}=0$$

3. if $p(x)=a_{n}x^n+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$ is a polynomial of degree $n$ then,$$\lim_{ x \to \infty } p(x) = \lim_{ x \to \infty }a_{n}x^n \hspace{1.0in} \lim_{ n \to -\infty } p(x)=\lim_{ n \to -\infty } a_{n}x^n$$
This is simply saying that when we take a limit at infinity for a polynomial all we need to really do is look at the term with the largest power.

# Asymptotes
- The function $f(x)$ will have a vertical asymptote at $x=a$, if we have any of the following limits at $x=a$.$$\lim_{ x \to a^- } f(x)=\pm \infty \hspace{0.5in} \lim_{ x \to a^+ } f(x)=\pm \infty \hspace{0.25in} \lim_{ x \to a } f(x)=\pm\infty$$
- The function $f(x)$ will have a horizontal asymptote at $y=L$ if either of the following are true$$\lim_{ x \to -\infty }f(x)=L \hspace{0.5in} \text{or} \hspace{0.5in} \lim_{ x \to \infty } f(x) = L$$

![[Asymptotes.png]]
- Here for the function $y=\dfrac{1}{x}$ has x-axis and y-axis are the asymptotes.
## See also

- [[Limits]]
- [[Improper Integrals]]