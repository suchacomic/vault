---
tags:
  - Calculus
  - Mathematics
  - integration
---
# Definite Integral
Given a function $f(x)$ that is [[Continuity|continuous]] on the interval $[a,b]$ we divide the interval into $n$ sub-intervals of equal width, $\Delta x$, and from each interval choose a point, $x_{i}^*$. Then the **definite integral** of $f(x)$ from $a$ to $b$ is 

$$\int_{{\,a}}^{{\,b}}{{f\left( x \right)\,dx}} = \mathop {\lim }\limits_{n \to \infty } \sum\limits_{i = 1}^n {f\left( {x_i^*} \right)\Delta x}$$

# Properties

1. $\displaystyle \int_{a}^{b} f(x) \, dx=-\int_{b}^{a} f(x) \, dx$
2. $\displaystyle \int_{a}^{a} f(x) \, dx=0$
3. $\displaystyle \int_{a}^{b} cf(x) \, dx =c\int_{a}^{b} f(x) \, dx$
4. $\displaystyle \int_{a}^{b} f(x)\pm g(x) \, dx=\int_{a}^{n} f(x) \, dx+\int_{a}^{b} g(x) \, dx$
5. $\displaystyle\int_{a}^{b} f(x) \, dx=\int_{a}^{c} f(x) \, dx+\int_{c}^{b} f(x) \, dx$
6. $\displaystyle \int_{a}^{b} f(x) \, dx=\int_{a}^{b} f(t) \, dt$ - Change of Variables 
7. $\displaystyle \int_{a}^{c} c \, dx=c(b-a)$
8. if $f(x)\geq 0$ for $a\leq x\leq b$ then $\displaystyle \int_{a}^{b} f(x) \, dx \geq \int_{a}^{b} g(x) \, dx$.
9. if $f(x)\geq g(x)$ for $a\leq x\leq b$ then $\displaystyle \int_{a}^{b} f(x) \, dx\geq \int_{a}^{b} g(x) \, dx$.
10. If $m\leq f(x)\leq M$ for $a\leq x\leq b$ then $m(b-a)\leq \int_{a}^{b} f(x) \, dx\leq M(b-a)$
11. if $|\int_{a}^{b} f(x)| \, dx\leq \int_{a}^{b}|f(x)|  \, dx$
## See also

- [[Fundamental Theorem of Calculus in one Variable]]
- [[Integrals]]
- [[Integration Techniques]]