---
layout: page
title: Alternating Group $ A_n $
---

**Definition.** *A 2-cycle is called a **transposition.***

**Corollary.** *Every permutation of $ \\{ 1,...,n \\} $ can be written as a
product of transpositions:*

$$
  S_n = \< (ij): 1 \leq i < j \leq n \>.
$$

A lot like bubble sort and its parallelized sibling even-odd sort.

![](/poij/assets/Bubble-sort-example-300px.gif)
![](/poij/assets/Odd_even_sort_animation.gif)

**Definition.** *Let $ \s \in S_n $ act on the polynomial*

$$
  \D = \prod_{1\leq i < j \leq n} (x_i - x_j)
$$

*by permuting its indices $ i, j $:*

$$
  \s\D = \prod_{1\leq i < j \leq n} (x_{\s i} - x_{\s j}).
$$

*Define the **sign** of $ \s $ as*

$$
  \e\s = \pm 1 \text{ if } \s\D = \pm\D, \text{ i.e. } \s\D = (\e\s)\D,
$$

*and call $ \s $ even if $ \e = 1$ and odd otherwise.*

**Proposition.** *The map $ \e: S_n \longrightarrow \\{ \pm 1 \\} $ is a
homomorphism.*

**Proposition.** *Transpositions are odd permutations:*

$$
\e(ij) = -1,
$$

*and thus $ \e $ is a surjective homomorphism.*

**Definition.** *The kernel of $ \e $, i.e. the set of even permutations, is
called the **alternating group of degreen** $ n, $ and is denoted $ A_n. $*