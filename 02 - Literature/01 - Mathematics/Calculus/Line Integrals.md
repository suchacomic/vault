---
tags:
  - Calculus
  - integration
  - Mathematics
---
# Line Integrals for Scalar Functions
- In line [[Integrals|integrals]] we integrate a function $f(x,y,z)$, a function in three variables, and the values of $x$.$y$,$z$ lies on the curve $\mathcal{P}$. 
- The curve $\mathcal{P}$ is a smooth [[Parametric Equations and Curves|parametric]] curve given by,$$x=x(t),\hspace{0.25in}y=y(t), \hspace{0.25in}z=z(t) ;\hspace{0.25in} a\leq t \leq b$$or, $$\vec{r}(t)=x(t)\,\hat{x}+y(t)\,\hat{y}+z(t)\,\hat{z}$$The curve is called “smooth” if $\vec{r}'(t)$ is [[Continuity|continuous]] and $\vec{r}'(t) \neq 0$ for all $t$.
- The **line integral** of $f(x,y,z)$ along $\mathcal{P}$ is denoted by,$$\int\limits_{\mathcal{P}} f(x,y,z) \, dl $$We us a $dl$ here to acknowledge the fact the we are <u>moving along</u> the curve, $\mathcal{P}$, instead of $x$-axis (demoted by $dx$) or the $y$-axis (denoted by $dy$).
- Because of $dl$ this is sometimes called the line integral of $f$ with respect to [[Arc Length|arc length]] (or [[Orthogonal Curvilinear Coordinates#Arc Length| arc length]]).
- Arc length $L$ is given by,$$L=\int_{a}^{b}dl,\hspace{0.25in} \text{where,}\, dl=\sqrt{ \left( \dfrac{dx}{dt} \right)^{2}+\left(\dfrac{dy}{dt}\right)^{2}+\left(\dfrac{dz}{dt}\right)^{2}}\,dt  $$thus,$$\int\limits_{\mathcal{P}}f(x,y)\,dl=\int_{a}^{b} f(h(t),g(t))\,\sqrt{ \left( \dfrac{dx}{dt} \right)^{2}+\left(\dfrac{dy}{dt}\right)^{2}+\left(\dfrac{dz}{dt}\right)^{2}} \, dt $$but,$$\lvert \vec{r}'(t) \rvert =\sqrt{\left( \dfrac{dx}{dt} \right)^{2}+\left(\dfrac{dy}{dt}\right)^{2}+\left(\dfrac{dz}{dt}\right)^{2}}$$$$\int\limits_{\mathcal{P}}f(x,y,z\,)\,dl=\int_{a}^{b} f(x(t),y(t),g(t))\ \lvert \vec{r}'(t) \rvert \,dt$$
# Line Integrals of Vector Function
- For a [[Vector Functions|vector function]] $\vec{F}$, $d\vec{r}$ is the infinitesimal displacement vector along the curve given by $\vec{r}(t)$ and the integral is carried out along a prescribed path $\mathcal{P}$ from point $\vec{a}$ to $\vec{b}$.$$\int_{a}^{b} \vec{F}\cdot d\vec{r}$$![[line integral.png]]If $\vec{r}=x(t)\,\hat{x}+y(t)\,\hat{y}+z(t)\,\hat{z}$, then by [[Derivatives#Chain Rule|chain rule]] $d\vec{r}=\vec{r}'(t)\,dt$ and the line integral becomes,$$\int\limits_{\mathcal{P}}\vec{F}\cdot d\vec{r}=\int_{a}^{b} \vec{F}(\vec{r}(t))\cdot\vec{r}'(t) \, dt  $$
- The line integral with respect to arc length as follows,$$\int\limits_{\mathcal{P}}\vec{F}\cdot d\vec{r}=\int\limits_{\mathcal{P}} \vec{F}\cdot \vec{T}\,ds$$where $\vec{T}$ is the [[Tangent and Normal Vectors|tangent]] vector and is given by,$$\overrightarrow{T}(t)=\dfrac{{\vec{r}'(t)}}{\lvert \vec{r}'(t) \rvert }$$
# Line Integral Independent of Arc Length
- The line integral of $f$ with respect to $x$ is,$$\int\limits_{\mathcal{P}}f(x,y)\,dx=\int_{a}^{b} f(x(t),y(t))\,x'(t) \, dt $$
- The line integral of $f$ with respect to $y$ is,$$\int\limits_{\mathcal{P}}f(x,y)\,dy=\int_{a}^{b} f(x(t),y(t))\,y'(t) \, dt $$
- These two integrals often appear together,$$\int\limits_{\mathcal{P}} P\,dx+ Q \, dy =\int\limits_{\mathcal{P}}P(x,y)\,dx+\int\limits_{\mathcal{P}}Q(x,y)\,dy $$
- We can see see that,$$\int\limits_{\mathcal{P}}\vec{F}\cdot d\vec{r}=\int\limits_{\mathcal{P}}P\,dx+Q\,dx+R\,dz$$where, $\vec{F}= P\,\hat{x}+Q\,\hat{y}+R\,\hat{z}$
# Closed Loop Integrals 
- If the path taken by the integral is a closed loop, that is $\vec{a}=\vec{b}$, the closed loop integral is used, denoted by $$\oint \vec{F}\cdot d\vec{r} $$