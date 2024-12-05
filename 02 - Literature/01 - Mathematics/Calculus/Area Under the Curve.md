---
tags:
  - Calculus
  - approximation
  - integration
  - Mathematics
---
# Riemann Sum
- To determine the area under a function $y=f(x)\geq{0}$ on $[a,b]$ we divide the interval into $n$ sub-interval each of length,$$\Delta x=\frac{{b-a}}{n}$$
- The endpoints if each sub-intervals are,$$
\begin{align}
x_{0}&=a \\
x_{1}&=a+\Delta x \\
x_{2}&=a+2\Delta \\
 \vdots \\
x_{i}&=a+i\Delta x \\
\vdots \\
x_{n-1}&=a+(n-1)\Delta x \\
x_{n}&=a+n\Delta x
\end{align}
$$
- We choose a point $x_{i}^*$ at midpoints on each sub-intervals to determine the height of the function at that point.
- The area under the curve on the given interval is then approximately,$$
\begin{align}
A &\approx f(x_{1}^*)\Delta x+f(x_{2}^*)\Delta x+\dots+f(x_{i}^*)\Delta x+\dots+f(x_{n}^*)\Delta x \\ \\
A &\approx \sum_{i=1}^{n} f(x_{i}^*)\Delta x
\end{align}
$$
- This summation is called a **Riemann Sum**.

![[Area Under the Curve.png]]

- If we let $n$ got to infinity we will get exact area, $$\begin{align}
A &=\lim_{ n \to \infty } \sum_{i=1}^{n}f(x_{i}^*) \Delta x \\
&=\int_{a}^{b} f(x) \, dx 
\end{align}$$

# Area Between Two Curves

- To determine the area between $y=f(x)$ and $y=g(x)$ on the interval $[a,b]$, assuming $f(x)>g(x)$,$$A=\int_{a}^{b} f(x)-g(x) \, dx,\hspace{1.0in} a\leq x\leq b $$
- [[Integrals|Integration]] represent subsequent additions of [[Limits|infinitesimally]] small rectangles to approximate the are under the curve.
## See also

- [[Rate of Change and Tangent Line]]