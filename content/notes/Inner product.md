---
title: "Inner product"
---
# Inner product
## Intuition
WIP
## Definition
An inner product on a [vector space](Vector%20space.md) $V$ over a [field](Field.md) is a function $\langle \cdot,\cdot\rangle:V^2 \to F$ that satisfies the followings:
For arbitrary $\mathbf{x}, \mathbf{y}, \mathbf{z} \in V$ and $c \in \mathbb{R}$,
$$
\begin{align*}
&(1) \quad \text{Linearity for the first argument:}\; &&\langle a\mathbf{x}+\mathbf{y},\mathbf{z}\rangle = a\langle \mathbf{x},\mathbf{z}\rangle + \langle \mathbf{y},\mathbf{z}\rangle\\[1pt]
&(2) \quad \text{Conjugate symmetry}: \; &&\langle \mathbf{x},\mathbf{y}\rangle = \overline{\langle \mathbf{y},\mathbf{x}\rangle}\\[4pt]
&(3) \quad \text{Positive semidefiniteness:} \; &&\langle \mathbf{x},\mathbf{x}\rangle \geq 0, \langle\mathbf{x},\mathbf{x}\rangle = 0\;\text{if and only if}\;\mathbf{x}=\mathbf{0}
\end{align*}
$$

## Standard inner product
### Definition
A standard inner space in $\mathbb{R}^n$ is defined for $\mathbf{x} = (x_1, \cdots, x_n)$ and $\mathbf{y} = (y_1, \cdots, y_n)$ as
$$
\langle\mathbf{x},\mathbf{y}\rangle = \mathbf{x}^\top\mathbf{y} = \sum\limits_{i=1}^n x_iy_i.
$$
Note that for the Euclidean [norm](Norm.md),
$$
\|\mathbf{x}\|_2 = \sqrt{\langle\mathbf{x},\mathbf{x}\rangle}.
$$

## Angle between vectors
The standard inner product on $\mathbb{R}^n$ is related to the angle between two vectors $\vx, \vy$. Let $\theta$ be the angle between the two vectors and let $\vz=\vx-\vy$.
Then, applying the second law of cosine gives
$$
\|\vz\|_2^2 = \|\vx\|_2^2 + \|\vy\|_2^2 -2\|\vx\|_2\|\vy\|_2\cos\theta.
$$
Now substitute $\vz=\vx-\vy$.
$$
\begin{align*}
\|\vx-\vy\|_2^2 &= (\vx-\vy)^\top(\vx-\vy)\\[1pt]
&= \vx^\top \vx + \vy^\top\vy -2\vx^\top\vy\\[1pt]
&= \|\vx\|_2^2 + \|\vy\|_2^2 -2\vx^\top\vy\\[1pt]
&= \|\vx\|_2^2 + \|\vy\|_2^2 -2\|\vx\|_2\|\vy\|_2\cos\theta
\end{align*}
$$
Hence,
$$
\cos\theta = \dfrac{\vx^\top\vy}{\|\vx\|_2\|\vy\|_2}.
$$