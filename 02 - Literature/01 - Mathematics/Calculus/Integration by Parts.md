---
tags:
  - integration
  - Mathematics
  - Calculus
  - integration_techniques
cssclasses:
  - center-images
---
# Integration By Parts

$$\int f\,g' \, dx = fg-\int f'\,g \, dx $$Or,$$
	\int u \, dv=uv-\int v \, du$$
# Example

$Q$. Evaluate the following integral.$$
\int xe^{6x} \, dx$$$$
\begin{align}
u &= x & \hspace{1in} dv&=e^{6x}dx \\
du &= dx & \hspace{1.0in} v&=\int e^{6x} \, dx=\frac{1}{6}e^{6x} 
\end{align}$$The integral is then,$$
\begin{align}
\int xe^{6x} \, dx &= \frac{x}{6}e^{6x}-\int \frac{1}{6}e^{} \, dx \\
& = \frac{x}{6}e^{6x}-\frac{1}{36}e^{6x}+c
\end{align}$$
# Integration By Parts, [[Definite Integrals]]
$$\int_{a}^{b} u \, dv = uv|_{a}^b-\int_{a}^{b} v \, du $$
# Cascading “By Parts”
$Q$. Evaluate the following integral.$$\int x^{4}e^{x/2} \, dx$$
- We start by choosing $u$ and $dv$.
- Instead of computing $dv$ and $v$ we put these into a column
- We then [[Derivatives|differentiate]] down the column corresponding to $u$ until we hit zero.
- In the column corresponding to $dv$ we [[Integrals]] once for each entry in the first column.
- In the third column we start it with a + and then alternate signs as shown.

![[Cascading by parts.png]]

$$\begin{multline*}
\int x^{4}e^{x/2} \, dx = (x^{4})(2e^{x/2})-(4x^{3})(e^{x/2})+(12x^{2})(8e^{x/2})\\
-(24x)(16e^{x/2})+(24)(32e^{x/2})
\end{multline*}$$## See also

- [[Integration Techniques]]
- [[Integrals]]