---
tags:
  - 3D_Space
  - Vector_Analysis
  - Mathematics
  - Calculus
  - integration
cssclasses:
  - center-images
---
# Arc Length
- Given a [[Continuity|continuous]] function $t=f(x)$ on the interval $[a,b]$ with its [[Derivatives|derivative]] continuous on $[a,b]$.
- We divide the interval into $n$ equal sub-intervals each of width $\Delta x$ and denote the point of the curve at each point by $P_{i}$.![[Arc Length in 1D.png]]
- The length of each segments are $|P_{i-1}Pi|$ and the length of the curve can be approximated by,$$
L \approx \sum_{i=1}^{n} |P_{i-1}Pi|$$
- We can get the exact length of the curve taking $n$ larger and larger, eventually taking the limit of $n$ at infinity,$$
L = \lim_{ n \to \infty } \sum_{i=1}^{n} |P_{i-1}Pi|$$
- Length of each segment is,$$\begin{array}{c}
|P_{i-1}P_{i}|=\sqrt{ \Delta x_{i}^{2}-\Delta y_{i}^{2} } \\ \\
\Delta x_{i}=x_{i}-x_{i-1} \hspace{0.5in} \Delta y_{i}=y_{i}-y_{i-1}=f(x_{i})-f(x_{i-1}) \\ \\
|P_{i-1}P_{i}|=\sqrt{ (x_{i}-x_{i-1})^{2}-(f(x_{i})-f(x_{i-1}))^{2} }
\end{array}$$
- By [[Mean Value Theorem#Lagrange's Mean Value Theorem|mean value theorem]] we know that on the interval $[x_{i-1},x_{i}]$ there is point $x_{i}^*$ so that,,$$\begin{align}
f(x_{i})-f(x_{x-1}) &= f'(x_{i}^*)(x_{i}-x_{i-1}) \\
\Delta y_{i} &=f'(x_{i}^*)\Delta x
\end{align}$$
- The length can be written as,$$\begin{align}
|P_{i-1}P_{i}| &= \sqrt{ \Delta x^{2}+[f'(x_{i}^*)]^{2}\Delta x^{2} } \\
&= \sqrt{ 1+[f'(x_{i}^*)]^{2} }\ \, \Delta x
\end{align}$$
- The length of the curve by the [[Area Under the Curve#Riemann Sum|Riemann sum]] is exactly,$$\begin{align}
L &= \lim_{ n \to \infty } \sum_{i=1}^{n} \sqrt{ 1+[f'(x_{i}^*)]^{2} }\ \, \Delta x \\
L &= \int_{a}^{b} \sqrt{ 1+\left( \frac{\mathrm{d}y}{\mathrm{d}x} \right)^{2} } \, dx 
\end{align}$$
- Arc length is thus,$$
L=\int dl$$where,$$
\begin{align}
dl &= \sqrt{ 1+\left( \frac{dy}{dx} \right)^{2} }\ dx \hspace{0.25in} \text{if } y=f(x),\ a\leq x\leq b \\
dl &= \sqrt{1+\left( \frac{dx}{dy} \right)^{2}}\ dy \hspace{0.25in} \text{if } x=h(y),\ c\leq y\leq d
\end{align}$$

# Arc Length with Parametric Equations  in 2-Dimensions
- Given a [[Parametric Equations and Curves|parametric]] curve,$$
x=f(t)\hspace{0.75in}y=g(t)\hspace{0.75in} \alpha\leq t\leq\beta$$
- We have the arc length as,$$
L=\int_{\alpha}^{\beta} \sqrt{ \left( \frac{dx}{dt} \right)^{2}+\left( \frac{dy}{dt} \right)^{2} } \, dt $$
# Arc Length with Vector Functions
- We have a [[Vector Functions|vector function]],$$
\vec{r}(t)=\langle f(t),g(t),h(t) \rangle $$on the interval $a\leq t\leq b$.
-  Extrapolating from 2-dimensional parametric curves’ arc length,$$
L =\int_{a}^{b} \sqrt{ [f'(t)]^{2}+[g'(t)]^{2}+[h'(t)]^{2} } \, dx $$
- This is nothing more than the [[Tangent and Normal Vectors|tangent vector]],$$
|\vec{r}'|=\sqrt{ [f'(t)]^{2}+[g'(t)]^{2}+[h'(t)]^{2} }$$
- Therefore, the arc length can be written as,$$
L=\int_{a}^{b} \lvert \vec{r}'(t) \rvert  \, dt $$
## See also

- [[Orthogonal Curvilinear Coordinates#Arc Length| Arc length for a general orthogonal curvilinear coordinates]]
