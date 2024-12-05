---
tags:
  - Physics
  - Introductory_Mechanics
cssclasses:
  - center-images
---
# Law of Conservation of Momentum on a Simple Two Particle System
- The law of conservation of momentum is intimately related to the [[Newton's Laws of Motion#Newton’s Third Law of Motion|third law of motion]]. 
- Assume there are two objects as shown,![[99 - Meta/02 - Excalidraw/Drawings/conservation of momentum]]Where the net external forces on the two objects are $\mathbf{F}_{1}^{\text{ext}}$ and $\mathbf{F}_{2}^{\text{ext}}$.
- The total force on object 1 and 2 is then,$$\begin{align}
\text{net force on 1} &\equiv \mathbf{F}_{1}=\mathbf{F}_{12}+\mathbf{F}_{1}^\text{ext} \\
\text{net force on 2} &\equiv \mathbf{F}_{2}=\mathbf{F}_{21}+\mathbf{F}_{2}^{\text{ext}}
\end{align}$$
- Using [[Newton's Laws of Motion#Newton’s Second law|Newton’s second law]]:$$\dot{\mathbf{p}}_{1}=\mathbf{F}_{1}=\mathbf{F}_{12}+\mathbf{F}_{1}^{\text{ext}}$$and,$$\dot{\mathbf{p}}_{2}=\mathbf{F}_{2}=\mathbf{F}_{21}+\mathbf{F}_{2}^{\text{ext}}$$If we define the total momentum is just $$\dot{\mathbf{P}}=\dot{\mathbf{p}}_{1}+\dot{\mathbf{p}}_{2}$$
- From the third law, $\mathbf{F}_{12}=-\mathbf{F}_{21}$, thus the above equation resolves to just,$$\dot{\mathbf{P}}=\dot{\mathbf{F}}_{1}^{\text{ext}}+\dot{\mathbf{F}}_{2}^{\text{ext}}\equiv \mathbf{F}^{\text{ext}}$$where $\mathbf{F}^{\text{ext}}$ denotes the total external force on the two-particle system.
- This asserts that as far a total momentum is concerned, the internal forces have no effect.
- If there are no external force,$$\bbox[15px, border:1px solid white]{\text{If} \hspace{0.25in} \mathbf{F}^{\text{ext}}=0,\hspace{0.25in} \text{then} \hspace{0.25in}\mathbf{P}=\text{const.} }$$
- In absence of external forces, the total momentum of is constant. This result is called the principle of conservation of momentum.
# Law of Conservation of Momentum
![[99 - Meta/02 - Excalidraw/Drawings/conservation of momentum 2.excalidraw]]
- Here $F_{\alpha\beta}$ is the force on $\alpha$ by $\beta$.
- The net force on the particle $\alpha$ is,$$\mathbf{F}_{\alpha}=\sum_{\beta \neq \alpha}\mathbf{F}_{\alpha\beta}+\mathbf{F}_{\alpha}^{\text{ext}}$$
- According to newtons second law, $\mathbf{F}_{\alpha}$ is the same as the rate of change of $\mathbf{p}_{\alpha}$:$$\mathbf{\dot{p}}_{\alpha}=\sum_{\beta \neq \alpha}\mathbf{F}_{\alpha\beta}+\mathbf{F}_{\alpha}^{\text{ext}}$$
- The total momentum of the $N$-particle system,$$\mathbf{P}=\sum_{\alpha}\mathbf{p}_{\alpha} $$
- [[Derivatives|Differentiating]] the equation with respect to time, we find $$\dot{\mathbf{P}}=\sum_{\alpha}\dot{\mathbf{p}}_{\alpha}$$substituting for $\dot{\mathbf{p}}_{\alpha}$,$$\dot{\mathbf{P}}=\sum_{\alpha}\sum_{\beta \neq \alpha}\mathbf{F}_{\alpha\beta}+\sum_{\alpha}\mathbf{F}_{\alpha}^{\text{ext}}$$
- Each term $\mathbf{F}_{\alpha\beta}$ in the double sum can be paired with a second term $\mathbf{F}_{\beta\alpha}$, and by the third law, $\mathbf{F}_{\alpha \beta}=-\mathbf{F}_{\beta\alpha}$, each pair cancels out and thus the whole double sum is zero, $$\sum_{\alpha}\sum_{\beta \neq \alpha}\mathbf{F}_{\alpha\beta}=0$$and,$$\dot{\mathbf{P}}=\sum_{\alpha}\mathbf{F}_{\alpha}^{\text{ext}}=\mathbf{F}^{\text{ext}}$$
- The result corresponds exactly to the two particle system. 
- If the net external force $\mathbf{F}^{\text{ext}}$ on an $N$-particle system is zero, the system’s total momentum $\mathbf{P}$ is constant.
- If the mass of the particle $\alpha$ is $m_{\alpha}$ and the velocity of the particle is $\mathbf{v}_{\alpha}$ then,$$\mathbf{P}=\sum m_{\alpha}\mathbf{v}_{\alpha}=\text{constant}$$