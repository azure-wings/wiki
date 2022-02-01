---
title: "Vector space"
math: true
---
## Intuition
WIP
## Definition

A vector space $V$ over a [field](notes/Field.md) $F$ consists of a set on which two operations $+$ (_addition_) and $\cdot$ (_scalar multiplication_) are defined so that the followings hold.

For any $\mathbf{x}, \mathbf{y}, \mathbf{z} \in V$ and $c, d \in F$:
> **(A1)** $\mathbf{x}, \mathbf{y} \in V \Rightarrow \mathbf{x} + \mathbf{y} \in V$
>
> **(A2)** $\mathbf{x} + \mathbf{y} = \mathbf{y} + \mathbf{x}$ (Commutativity of addition)
>
> **(A3)** $(\mathbf{x} + \mathbf{y}) + \mathbf{z} = \mathbf{x} + (\mathbf{y} + \mathbf{z})$ (Associativity of addition)
>
> **(A4)** $\forall \mathbf{x} \in V: \exists \mathbf{0} \in V$ such that $\mathbf{x} + \mathbf{0} = \mathbf{x}$ (Existence of additive identity)
>
> **(A5)** $\forall \mathbf{x} \in V: \exists (-\mathbf{x}) \in V$ such that $\mathbf{x} + (-\mathbf{x}) = \mathbf{0}$ (Existence of additive inverse)
>
> **(M1)** $\mathbf{x} \in V \Rightarrow c\mathbf{x} \in V$
>
> **(M2)** $c(d\mathbf{x}) = (cd)\mathbf{x}$
>
> **(M3)** $c(\mathbf{x} + \mathbf{y}) = c\mathbf{x} + c\mathbf{y}$
>
> **(M4)** $(c + d)\mathbf{x} = c\mathbf{x} + d\mathbf{x}$
>
> **(M5)** $\forall \mathbf{x} \in V: 1\mathbf{x} = \mathbf{x}$


## Related Concepts
- [Norm](notes/Norm.md): Defines a distance-like property in vector spaces
- [Inner product](notes/Inner%20product.md): Allows the concept of 'direction' to be considered in cevtor spcaes
 