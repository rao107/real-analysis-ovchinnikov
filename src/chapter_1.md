# Chapter 1: Rational Numbers

### Exercise 1.1

From Theorem 1.1, \\((mp, np) \sim (m, n)\\) is true if and only if \\(mpn = mnp\\) which is easily true.

### Exercise 1.2

Suppose \\(\phi\\) is not one-to-one and there exists \\(\phi(m) = \phi(n)\\). This implies that \\(m/1 = n/1\\). This equality is only true if \\(m \cdot 1 = n \cdot 1\\), so \\(m = n\\) and \\(\phi\\) is one-to-one.

\\[
  \begin{align}
    \phi(m + n) &= (m + n)/1 \\\\
    &= m/1 + n/1 \\\\
    &= \phi(m) + \phi(n) \\\\
  \end{align}
\\]

\\[
  \begin{align}
    \phi(m \cdot n) &= (m \cdot n)/1 \\\\
    &= m/1 \cdot n/1 \\\\
    &= \phi(m) \cdot \phi(n) \\\\
  \end{align}
\\]

### Exercise 1.3

Proving **A1**:

When \\(a = b\\), this is proven by reflexivity. For \\(0 + 1 = 1 + 0\\), both sides evaluate to \\(1\\).

Proving **A2**:

When \\(a = 0\\), both sides simplify to \\(b + c = b + c\\) which is true by reflexivity. Looking at the case where \\(a = 1\\), when \\(b = 0\\) both sides simplify to \\(1 + c = 1 + c\\) which is true by reflexivity. Now when \\(a = b = 1\\), we can look at both cases where \\(c = 0\\) and \\(c = 1\\) and see the equality holds and is equal to \\(0\\) and \\(1\\) respectively.

Proving **A3**:

We can see that \\(0 + 0 = 0\\) and \\(1 + 0 = 1\\) so \\(0\\) is the additive identity on \\(\mathbb{Z}_2\\).

Proving **A4**:

For \\(0\\), the additive inverse is \\(0\\) since \\(0 + 0 = 0\\). For \\(1\\), the additive inverse is \\(1\\) since \\(1 + 1 = 0\\).

Proving **M1**:

When \\(a = b\\), the equality is true by reflexivity. For \\(0 \cdot 1 = 1 \cdot 0\\), both sides of the equation evaluate to 0.

Proving **M2**:

When \\(a = 0\\) or \\(b = 0\\) or \\(c = 0\\), the product is \\(0\\) on both sides. When \\(a = b = c = 1\\), then both sides evaluate to \\(1\\).

Proving **M3**:

We can see that \\(0 \cdot 1 = 0\\) and \\(1 \cdot 1 = 1\\) so \\(1\\) is the multiplicative identity on \\(\mathbb{Z}_2\\).

Proving **M4**:

For \\(a = 1\\), the multiplicative inverse is \\(1\\) since \\(1 \cdot 1 = 1\\).

Proving **D**:

For \\(a \cdot (b + c)\\), when \\(a = 0\\) this is true since \\(0\\) or \\(1\\) times \\(0\\) is \\(0\\). When \\(a = 1\\), then the equality evaluates to \\(b + c = b + c\\) which is trivially true by reflexivity.

### Exercise 1.4

Suppose the additive inverse is not unique, that there are two elements \\(-a\\) and \\(-a'\\) for which \\(a + (-a) = 0\\) and \\(a + (-a') = 0\\). From **A2**, \\((-a + a) + -a' = -a + (a + -a')\\). Since both \\(-a\\) and \\(-a'\\) are additive inverses, this simplifies to \\(-a' = -a\\). Therefore, the additive inverse must be unique.

Suppose the multiplicative inverse is not unique, that there are two elements \\(a^{-1}\\) and \\(a^{-1}\{'\}\\) for which \\(a \cdot a^{-1} = 1\\) and \\(a \cdot a^{-1}\{'\} = 1\\). From **M2**, \\((a^{-1} \cdot a) \cdot a^{-1}\{'\} = a^{-1} \cdot (a \cdot a^{-1}\{'\})\\). Since both \\(a^{-1}\\) and \\(a^{-1}\{'\}\\) are multiplicative inverses, this simplifies to \\(a^{-1}\{'\} = a^{-1}\\). Therefore, the multiplicative inverse must be unique.

### Exercise 1.5

Since \\(0 + 0 = 0\\), we can use this to find that:

\\[
  \begin{align}
    a \cdot 0 &= a \cdot (0 + 0) \\\\
    &= a \cdot 0 + a \cdot 0
  \end{align}
\\]

Therefore, \\(a \cdot 0 = 0\\).

### Exercise 1.6

**(a)**
By **M3**, \\(1 \cdot 1 = 1\\). This equation also satisfies **M4**, showing that \\(1^{-1} = 1\\).

**(b)**

\\[
  \begin{align}
    (a \cdot b)^{-1} &= a^{-1} \cdot b^{-1} \\\\
    (a \cdot b)^{-1} \cdot (a \cdot b) &= a^{-1} \cdot b^{-1} \cdot (a \cdot b) \\\\
    1 &= aa^{-1} \cdot bb^{-1} \\\\
    1 &= 1 \cdot 1 \\\\
    1 &= 1 \\\\
  \end{align}
\\]

**(c)**

\\[
  c \cdot b = a \iff c \cdot b \cdot b^{-1} = a \cdot b^{-1} \iff c = a/b
\\]

**(d)**

\\[
  \frac{a}{b} \cdot \frac{c}{d} = a \cdot c \cdot \frac{1}{b} \cdot \frac{1}{d} = \frac{a \cdot c}{b \cdot d}
\\]

**(e)**

\\[
  ab^{-1} = ab^{-1}cc^{-1} = (a \cdot c)(b^{-1} \cdot c^{-1}) = (a \cdot c)(b \cdot c)^{-1}
\\]

**(f)**

\\[
  ab^{-1} + cd^{-1} = ab^{-1}dd^{-1} + cd^{-1}bb^{-1} = (ad)(bd)^{-1} + (cb)(bd)^{-1} = (ad + cb)(bd)^{-1}
\\]

**(g)**

\\[
  ab^{-1} = cd^{-1} \iff ab^{-1}bd = cd^{-1}db \iff ad = cb
\\]

**(h)**

\\[
  (ab^{-1})^{-1} = a^{-1}(b^{-1})^{-1} = ba^{-1}
\\]

**(i)**

\\[
  ab^{-1} \div cd^{-1} = ab^{-1} \cdot (cd^{-1})^{-1} = ab^{-1}c^{-1}d = ad(bd)^{-1}
\\]

### Exercise 1.7

TODO

TODO

TODO

### Exercise 1.8

TODO

TODO

TODO

### Exercise 1.9

TODO

TODO

TODO

### Exercise 1.10

We prove this via induction. The case \\(n = 0\\) is trivial since \\(\tau(-0) = \tau(0) = 0 = -0 = -\tau(0)\\).

Now, we assume that \\(\tau(-n) = -\tau(n)\\) and must prove \\(\tau(-(n + 1)) = -\tau(n + 1)\\). This can be shown be these series of equalities,

\\(-\tau(n + 1) = -(\tau(n) + 1) = -\tau(n) - 1 = \tau(-n) - \tau(1)\\)

TODO

TODO

TODO

### Exercise 1.11



### Exercise 1.12

We can prove this via induction. For the base case, \\(n = 3\\), we need to show \\(a_1 < a_3\\). Using the order relation's transitivity property with \\(a_1 < a_2\\) and \\(a_2 < a_3\\), we know that \\(a_1 < a_3\\).

Now, we assume that \\(a_1 < a_n\\) and must show that \\(a_1 < a_{n+1}\\). We are given that \\(a_n < a_{n+1}\\). Using the transitivity property again, we can prove that \\(a_1 < a_{n+1}\\) for all \\(n > 2\\).

### Exercise 1.13



### Exercise 1.14



### Exercise 1.15



### Exercise 1.16

If \\(x = y\\), then \\(|x - y| = |x - x| = |0| = 0\\). If \\(|x - y| = 0\\), then, from the definition of absolute value, \\(|x - y| = x - y\\). Substituting this into the above equality, we see that \\(x - y = 0\\). From here, it's simple to see \\(x = y\\).

If \\(x - y\\) is positive, \\(|y - x| = |-(x - y)| = x - y = |x - y|\\). If \\(x - y\\) is negative, \\(|x - y| = |-(y - x)| = y - x = |y - x|\\). If \\(x - y = 0\\), this is trivially true.

We know that \\(|x - z| = |x - y + y - z|\\).

TODO

TODO

TODO

### Exercise 1.17

**(a)**



**(b)**



**(c)**



**(d)**



**(e)**



**(f)**



**(g)**



**(h)**



**(i)**



### Exercise 1.18



### Exercise 1.19

\\(a \leq x \leq b\\), \\(a \leq y \leq b\\)

\\(|x - y| \leq b - a\\)

### Exercise 1.20



### Exercise 1.21



### Exercise 1.22



### Exercise 1.23



### Exercise 1.24



### Exercise 1.25



### Exercise 1.26



### Exercise 1.27



### Exercise 1.28


