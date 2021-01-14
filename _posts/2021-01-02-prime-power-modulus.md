---
layout: page
title: Prime Power Modulus
---

# Hensel's Lifting Lemma

**Theorem.** *Let $ f(x) $ be a polynomial with integral coefficients. If*

$$
\begin{aligned}
f(a) &\equiv 0 \mod p^j \\
f'(a) &\not\equiv 0 \mod p,
\end{aligned}
$$

*then there is a unique $ t \mod p $ s.t.*

$$
f(a + tp^j) \equiv 0 \mod p^{j+1}.
$$

*Moreover, $ t $ satisfies*

$$
t f'(a) \equiv - \frac{f(a)}{p^j} \mod p.
$$

If $ f'(a) \not\equiv 0 \mod p, $ we call $ a $ a nonsingular root; OTW it is singular.

Hensel's Lemma allows us to use a known solution of $ f(x) \equiv 0 \mod p^j $ to find new solutions of $ f(x) \equiv 0 \mod p^{j+1}. $ In particular, e.g. if we know a solution of $ f(x) \equiv 0 \mod p, $ we can find all solutions of $ f(x) \equiv 0 $ modulo $ p^2, p^3,..., $ provided the nonsingularity condition holds.

# Lifting a nonsingular solution

**Theorem.**
*Let $ f(x) $ be a polynomial with integral coefficients. Suppose that $ f(a) \equiv 0 \mod p^j, p^\t || f'(a), $ and $ j \geq 2\t + 1. $ If*

$$
b \equiv a \mod p^{j-\t},
$$

*then*

$$
f(b) \equiv f(a) \mod p^j
$$

*and
$ p^\t || f'(b). $ Moreover, there is a unique $ t \mod p $ s.t.*

$$
f(a + tp^{j-\t}) \equiv 0 \mod p^{j+1},
$$

*where $ t $ satisfies*

$$
\frac{f(a+tp^{j-\t})}{p^j} \equiv \frac{f(a)}{p^j} + t \frac{f'(a)}{p^\t} \mod p.
$$

The condition
$ p^\t || f'(a) $ replaces the nonsingularity condition in Hensel's Lemma. This theorem says that if we know a solution modulo a high enough power $ p^j, $ namely $ j \geq 2\t + 1, $ then we can lift it to arbitrarily higher powers of $ p. $