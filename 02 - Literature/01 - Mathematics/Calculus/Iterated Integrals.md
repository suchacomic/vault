---
tags:
  - Calculus
  - integration
  - Mathematics
---
# Fubini’s Theorem

If $f(x,y)$ is [[Continuity|continuous]] on $R=[a,b]\times[c,d]$ then,$$\iint\limits_{R}f(x,y)\, dA=\int_{a}^{b} \int_{c}^{d} f(x,y) \, dy \, dx=\int_{c}^{d} \int_{a}^{b} f(x,y) \, dx \, dy  $$ These [[Integrals|integrals]] are called **iterated integrals**

# Double Integration for Separable Function

Assume a function $f(x,y)=g(x)h(y)$ and we are [[Double Integrals|integrating]] over a rectangle given by $R=[a,b]\times[c,d]$. Then the integral becomes,$$\iint\limits_{R}f(x,y)\, dA=\iint\limits_{R}g(x)h(y)\,\mathrm{d}A=\left( \int_{a}^{b} g(x) \, dx  \right)\left( \int_{c}^{d} h(y) \, dy  \right)$$
