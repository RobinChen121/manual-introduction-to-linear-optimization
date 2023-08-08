### Excersie 2.1

For each one of the following sets, determine whether it is a polyhedron.

(a) The set of all $(x, y)\in \mathcal{R}^2$ satisfying the constraints:
$$
\begin{aligned}
x\cos\theta+y\sin\theta&\leq 1,\quad \forall~\theta \in[0, \pi/2],\\
x&\geq 0,\\
y&\geq 0.
\end{aligned}
$$

(b) The set of all $x\in\mathcal{R}$ satisfying the constraint $x^2 - 8x + 15 \leq 0$.

(c) The empty set.

**Solution**

(a) The set equals $\{ (x,y) | x \geq 0, y \geq 0, x^2 + y^2 \leq 1 \}$, which has the following image:

![image.png](attachment:image.png)

It is a set represented by infinite linear constraints, while a polyhedron is formed by **finite** linear constraints.

(b) The set is $\{x\geq 3, x\leq 5\}$ and is a polyhedron.

(c) The empty set can be represented as $\{x\geq 0, x< 0\}$ and is a polyhedron.

### Excersie 2.2

Let $f:\mathcal{R}^n\rightarrow\mathcal{R}$ be a convex function and let $c$ be some constant. Show that the set $S = \{\bf{x} \in \mathcal{R}^n\mid f(\bf{x}) \leq c\}$ is convex.


**Solution**

Assume two random element $x_1$ and $x_2$ in the set $S$,  therefore
 $$
 \begin{aligned}
 f(x_1)\leq c\\
 f(x_2)\leq c
 \end{aligned}
 $$
For a parameter $\theta\in [0, 1]$, 
 $$
 \begin{aligned}
 \theta f(x_1)&\leq  \theta c\\
 (1-\theta)f(x_2)&\leq  (1-\theta) c
 \end{aligned}
 $$
 Thus, 
$$
 \theta f(x_1)+ (1-\theta)f(x_2)\leq c
$$

Since $f$ is a convex function, 
$$
f(\theta x_1+(1-\theta)x_2)\leq \theta f(x_1)+ (1-\theta)f(x_2)
$$
And this leads to
$$
f(\theta x_1+(1-\theta)x_2)\leq c
$$
Therefore, the set $S$ is convex. $\Box$



```python

```
