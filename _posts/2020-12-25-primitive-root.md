---
layout: page
title: Primitive Root Modulo $ n $
---

**Definition.** *Let n be a positive integer. A primitive root mod n is an
integer g such that every integer relatively prime to n is congruent to a power
of g mod n, i.e. for every number a relatively prime to n there is an integer z
such that*

$$
  a \equiv g^z \mod n.
$$

**Example.** 2 is a primitive root mod 5 because for every $ a $ coprime with 5,
there is a power $ 2^z $ s.t. $ a \equiv 2^z \mod 5. $

**Definition.** *Define the order $ |a| $ of $ a $ to be the smallest
integer z s.t. $ a $ is a $ z $-th root of $ 1 \mod n $, i.e.*

$$
    a^z \equiv 1 \mod n.
$$

**Corollary.** *A number $ a $ is a primitive root of $ n $ iff $ |a| =
\f(n). $*

