---
tags:
  - Calculus
  - derivatives
  - Mathematics
  - approximation
cssclasses:
---
- Given a function, $f(x)$, we can find its [[Rate of Change and Tangent Line#Tangent|tangent]] at $x=a$. The equation of the tangent line $L(x)$ is given by,$$L(x) = f(a)+f'(a)(x-a)$$
- for example,

```desmos-graph
left=-0.1; right=4;
bottom=-0.1; top=4;
---
f(x) = 0.5x^{2}+1
y = f(1)+(x-1)
(1, 1.5)|label:(a,f(a))
```

- From the above graph we can see that near $x=a$ the [[Rate of Change and Tangent Line#Tangent|tangent]] line and the function have nearly the same value. In these cases we call the tangent line the **linear approximation** to the function at x=a.

## See also

- [[Rate of Change and Tangent Line]]
- [[Newton's Method]]