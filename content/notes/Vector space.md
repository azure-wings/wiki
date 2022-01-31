---
title: "Vector space"
---
# Vector space
## Intuition
WIP
## Definition
A nonempty set $V$, associated with a [field](notes/Field.md) $F$, is called a vector space if it satisfies the followings:
For arbitrary $\mathbf{x}, \mathbf{y}, \mathbf{z}\in V$ and $a,b\in F$ [^-1]
$$\begin{align*}
&(1) \quad \text{Commutativity:}   \; &&\mathbf{x}+\mathbf{y}=\mathbf{y}+\mathbf{x}\\[1pt]
&(2) \quad \text{Associativity:}   \; &&\begin{cases}(\mathbf{x}+\mathbf{y})+\mathbf{z}=\mathbf{x}+(\mathbf{y}+\mathbf{z})\\[1pt] a(b\mathbf{x})=(ab)\mathbf{x}\end{cases}\\[1pt]
&(3) \quad \text{Additive Identity:}   \; &&\exists \;\mathbf{0}\in V\; \text{s.t.:} \quad \mathbf{0}+\mathbf{x}=\mathbf{x}\\[1pt]
&(4) \quad \text{Additive Inverse:}   \; &&\exists \;\mathbf{-x}\in V\; \text{s.t.:} \quad \mathbf{-x}+\mathbf{x}=\mathbf{0}\\[1pt]
&(5) \quad \text{Scalar Multiplication Identity:}   \; &&\exists\;1\in F\; \text{s.t.:} \quad 1\mathbf{x}=\mathbf{x}\\[1pt]
&(6) \quad \text{Distributivity:}   \;&&\begin{cases}\;(a+b)\mathbf{x} = a\mathbf{x} + b\mathbf{x}\\[1pt] \;a(\mathbf{x}+\mathbf{y}) = a\mathbf{x}+a\mathbf{y}\end{cases}\\
\end{align*}
$$


## Related Concepts
- [Norm](notes/Norm.md): Defines a distance-like property in vector spaces
- [Inner product](notes/Inner%20product.md): Allows the concept of 'direction' to be considered in cevtor spcaes

[^-1]: Actually, in $(2)$ associativity, the scalar one is not a property of associativity because $b\mathbf{x}$ is a scalar-vector multiplication while $ab$ is a scalar-scalar multiplication. It should be called the 'compatibility for scalar multiplication to field multiplication' instead. 