---
tags:
  - Physics
  - Introductory_Mechanics
---
# Polar Coordinates 
- Polar coordinates are [[Spherical Coordinate System|spherical coordinates]] in two dimensions ($xy$-plane), with the value of $\theta=\frac{\pi}{2}$, thus the $z$ component, $r\cos\theta=0$. $$\begin{align}
x &= r\cos\phi \\
y &= r\sin \phi \\ \\
r &=\sqrt{ x^{2}+y^{2} } \\
\phi &=\tan^{-1}\left( \frac{y}{x} \right)
\end{align}$$and,$$\mathbf{r}=r\cos \phi\,\hat{x}+r\sin \phi \, \hat{y}$$
- with unit basis vectors are $\hat{e}_{r}=\hat{r}$ and $\hat{e}_{\phi}=\hat{\phi}$, and [[Orthogonal Curvilinear Coordinates#Unit Vectors and Scale Factor|scale factor]] $h_{r}=1$ and $h_{\phi}=r$,$$\begin{align}
\hat{r} &= \cos \phi \, \hat{x}+\sin \phi \,\hat{y} \\
\hat{\phi}&= -\sin \phi\, \hat{x} +\cos \phi\,\hat{y}
\end{align}$$
- By the chain rule, $$\begin{align}
d\mathbf{\hat{r}}&= -\sin \phi\,\hat{x}\, d\phi+\cos \phi\, \hat{y} \, d\phi \\ &= \,d\phi\,(-\sin \phi\,\hat{x}+\cos \phi\,\hat{y}) = \,d\phi\, \hat{\phi} \\
\frac{d\hat{\mathbf{r}}}{dt}&=\frac{d\phi}{dt}\,\hat{\phi} \\ \\
\frac{d\hat{\mathbf{r}}}{dt} &= \dot{\phi}\,\hat{\phi} \tag 1
\end{align}$$similarly,$$\begin{align}
d\hat{\phi} &= -\cos \phi\,d\phi\,\hat{x}-\sin \phi\,d\phi\,\hat{y} \\
d\hat{\phi} &=-d\phi\,(\cos\phi \,\hat{x}+\sin \phi \,\hat{y}) \\ \\
\frac{d\hat{\phi}}{dt} &= - \dot{\phi}\,\hat{r} \tag 2
\end{align}$$
# Motion in Polar Coordinate 
 - For the position vector $\mathbf{r}$, using [[Derivatives#Product and Quotient Rule|product rule]] we get two terms,$$\dot{\mathbf{r}}=\dot{r}\,\hat{r}+r\, \frac{d\hat{r}}{dt}$$substituting, from the equation $(1)$ , we find for the [[Displacement, Velocity and Acceleration#Velocity Vector|velocity]] $\dot{\mathbf{r}}$, or $\mathbf{v}$,$$\mathbf{v}\equiv \dot{\mathbf{r}}=\dot{r}\,\hat{r}+r\,\dot{\phi}\,\hat{\phi}$$
 - From this we can read off the polar components of the velocity:$$v_{r}=\dot{r} \hspace{0.5in} \text{and} \hspace{0.5in} v_{\phi}=r\dot{\phi}=r\omega$$where $\omega$ is called the angular velocity.$$\bbox[15px, border:1px solid white]{\mathbf{v}=\dot{r}\,\hat{r}+r\,\omega\,\hat{\phi}}$$
 - [[Derivatives|Differentiating]] twice to obtain acceleration,$$a\equiv \ddot{\mathbf{r}}=\frac{d}{dt}(\dot{\mathbf{r}})=\frac{d}{dt}(\dot{r}\,\hat{r}+r\,\dot{\phi}\,\hat{\phi})$$
 - Applying product rule to both terms, $$a=\left( \ddot{r}\,\hat{r}+\dot{r}\, \frac{d\hat{r}}{dt}\right)+\left( ( \dot{r}\,\dot{\phi} +r\,\ddot{\phi})\,\hat{\phi} +r\,\dot{\phi}\,\frac{d\hat{\phi}}{dt}  \right)$$substituting the derivatives from equation $(1)$ and $(2)$, $$\begin{align}
a &= (\ddot{r}\,\hat{r}+\dot{r}\,\dot{\phi}\,\hat{\phi})+((\dot{r}\,\dot{\phi}+r\, \ddot{\phi})\,\hat{\phi}-r\,\dot{\phi}^{2}\,\hat{r}) \\ \\

&\bbox[15px, border:1px solid white]{a=(\ddot{r}-r\,\dot{\phi}^{2})\,\hat{r}+(r\,\ddot{\phi}+2\,\dot{r}\,\dot{\phi})}
\end{align}$$
- The radial acceleration $a_{r}$ is composed of the acceleration due to the change in radial velocity, $\ddot{r}$ and the centripetal force, $r\,\omega^{2}$.
- The tangential acceleration $a_{t}$ is composed of the acceleration due to change in the angular velocity, $r\,\ddot{\phi}=r\alpha$, where $\alpha$ is called the angular acceleration and the Coriolis acceleration, $2\,\dot{r}\,\dot{\phi}$. 