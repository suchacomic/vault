---
tags:
  - Calculus
  - integration
  - Mathematics
aliases:
  - volume integral
cssclasses:
  - center-images
---
# Volume Integrals
- To [[Integrals|integrate]] over three dimensional region, the notation for the general triple integrals is, $$\iiint\limits_{\mathcal{V}}f\,(x,y,z)\, sd\tau$$where $f(x,y,z)$ is a scalar function and $d\tau$ is an infinitesimal [[Orthogonal Curvilinear Coordinates#Volume Element|volume element]].
- Integrating over a volume $\mathcal{V}=[a,b]\times[c,d]\times[r,s]$, the triple integration in this case is,$$\iiint\limits_{\mathcal{V}}f(x,y,z)\,d\tau= \int_{r}^{s} \int_{c}^{d} \int_{a}^{b} f\,(x,y,z)\,dx\,dy\,dz$$
- The volume of the three-dimensional region $\mathcal{V}$ is given by the integral,$$V=\iiint\limits_{\mathcal{V}}d\tau$$
- For general three-dimensional volume we define the region as follows,$$\mathcal{V}=\{ (x,y,z)\,| (x,y) \in D,u_{1}(x,y)\leq z\leq u_{2}(x,t) \}$$![[Triple Integrals volume.png]]where $(x,y) \in D$ is the notation that means that the point $(x,y)$ lies in the region $D$ from the $xy$-plane,$$\iiint\limits_{\mathcal{V}}f(x,y,z)=\iint\limits_{D}\left[ \int_{u_{1}(x,y)}^{u_{2}(x,y)}f(x,y,z)  \, dz \right]\,dA$$similarly, we can extrapolate the volume of regions bound by functions $v(y,z)$ and $w(x,z)$.
# Triple Integration in Cylindrical Coordinates
- For [[Cylindrical Coordinate System|cylindrical]] [[Orthogonal Curvilinear Coordinates|curvilinear coordinates]], the relation to Cartesian coordinates are$$x=s\cos\theta\hspace{0.5in}y=s\sin\theta \hspace{0.5in} z=z$$
- The [[Cylindrical Coordinate System#Volume Element|volume element]] is,$$d\tau=s\,ds\,d\theta \,dz$$where,$$
\alpha\leq\theta\leq\beta,\hspace{0.15in} h_{1}(\theta)\leq s\leq h_{2}(\theta),\hspace{0.15in} u_{1}(s\cos\theta,s\sin\theta)\leq z\leq u_{2}(s\cos\theta,s\sin\theta)$$
- The triple integration after substitution becomes,$$\iiint\limits_{\mathcal{V}}f\,(x,y,z)\,d\tau=\int_{\alpha}^{\beta} \int_{h_{1}(\theta)}^{h_{2}(\theta)} \int_{u_{1}(s\cos\theta,s\sin\theta)}^{u_{2}(s\cos\theta,s\sin\theta)} f(s\cos\theta,s\sin\theta,z)\,s \, dz  \, ds  \, d\theta  $$
- This can be derived from [[Change of Variable]] too.
## See also

- [[Double Integrals]]
- [[]]