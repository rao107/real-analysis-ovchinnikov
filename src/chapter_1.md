# Chapter 1: Rational Numbers

18/28 problems solved

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

Reflexivity:
\\((f, g) \sim (f, g)\\) since \\(fg = fg\\).

Symmetry:
If \\(fk = hg\\), then \\(hg = fk\\). Therefore, \\((f, g) \sim (h, k)\\) implies \\((h, k) \sim (f, g)\\).

Transitivity:
Suppose \\((f, g) \sim (h, k)\\) and \\((h, k) \sim (m, n)\\). That is, \\(fk = hg\\) and \\(hn = mk\\). Therefore, \\((fk)(hn) = (hg)(mk)\\) which simplifies to \\(fn = gm\\). Therefore, \\((f, g) \sim (m, n)\\).

### Exercise 1.8

Proving **A1**:
\\[ f/g + h/k = (fk + gh)/gk = (hg + kf)/kg = h/k + f/g \\]

Proving **A2**:
\\[
  \begin{align}
    (f/g + h/k) + m/n &= (fk + gh)/gk + m/n \\\\
    &= (fkn + ghn + gkm)/gkn \\\\
    &= f/g + (hn + mk)/kn \\\\
    &= f/g + (h/k + m/n) \\\\
  \end{align}
\\]

Proving **A3**:
The \\(0\\) rational polynomial is the additive identity since the \\(0\\) polynomial is the additive identity for integer polynomials.

Proving **A4**:
The additive identity of a rational polynomial \\(f/g\\) is \\(-f/g\\) since adding these two gives us \\(f/g + (-f/g) = (fg + -gf)/gg = 0/gg = 0\\).

Proving **M1**:
\\[ f/g \cdot h/k = fh/gk = hf/kg = h/k \cdot f/g \\]

Proving **M2**:
\\[ (f/g \cdot h/k) \cdot m/n = fh/gk \cdot m/n = fhm/gkn = f/g \cdot hm/kn = f/g \cdot (h/k \cdot m/n) \\]

Proving **M3**:
The multiplicative identity is the \\(1\\) polynomial since \\(f/g \cdot 1/1 = f/g\\).

Proving **M4**:
The multiplicative inverse of a rational polynomial \\(f/g\\) is \\(g/f\\) since multiplying these two gives us \\(fg/gf = 1\\).

Proving **D**:
\\[
  \begin{align}
    f/g \cdot (h/k + m/n) &= f/g \cdot (hn + mk)/kn \\\\
    &= (fhn + fmk)/gkn \\\\
    &= fhn/gkn + fmk/gkn \\\\
    &= fh/gk + fm/gn \\\\
    &= f/g \cdot h/k + f/g \cdot m/n \\\\
  \end{align}
\\]

### Exercise 1.9

In an ordered field, \\(0 \neq 1\\). If \\(1 < 0\\), then ... [find contradiction]. Therefore, from the trichotomy property, \\(0 < 1\\).



### Exercise 1.10

We prove this via induction. The case \\(n = 0\\) is trivial since \\(\tau(-0) = \tau(0) = 0 = -0 = -\tau(0)\\).

Now, we assume that \\(\tau(-n) = -\tau(n)\\) and must prove \\(\tau(-(n + 1)) = -\tau(n + 1)\\). This can be shown be these series of equalities,

\\(-\tau(n + 1) = -(\tau(n) + 1) = -\tau(n) - 1 = \tau(-n) - \tau(1)\\)



### Exercise 1.11

\\[ a/b < c/d \iff abd/b < bcd/d \iff ad < bc \\]

### Exercise 1.12

We can prove this via induction. For the base case, \\(n = 3\\), we need to show \\(a_1 < a_3\\). Using the order relation's transitivity property with \\(a_1 < a_2\\) and \\(a_2 < a_3\\), we know that \\(a_1 < a_3\\).

Now, we assume that \\(a_1 < a_n\\) and must show that \\(a_1 < a_{n+1}\\). We are given that \\(a_n < a_{n+1}\\). Using the transitivity property again, we can prove that \\(a_1 < a_{n+1}\\) for all \\(n > 2\\).

### Exercise 1.13



### Exercise 1.14

From Example 1.3, we define \\(f/g < h/k\\) if \\(fk < gh\\).

**(a)**
\\(f/g < h/k\\) iff \\(f/g + m/n < h/k + m/n\\)

If \\(f/g < h/k\\), then we know \\(fk < gh\\) and must prove \\((fn + mg)/gn < (hn + mk)/kn\\) or equivalently \\((fn + mg)kn < (hn + mk)gn\\). We can remove the \\(n\\) on both sides and distribute to get \\(fnk + mgk < hng + mkg\\). This can be further simplified into \\(fk < hg\\) which is what we know from \\(f/g < h/k\\).

If \\(f/g + m/n < h/k + m/n\\), then we know \\((fn + mg)/gn < (hn + mk)/kn\\), and must prove \\(f/g < h/k\\) or equivalently \\(fk < gh\\). We can multiply \\(n\\) and add \\(mgk\\) on both sides to get \\(fkn + mgk < ghn + mgk\\). This can be rewritten as \\((fn + mg)k < (hn + mk)g\\). Multiply \\(n\\) on both sides to get \\((fn + mg)kn < (hn + mk)gn\\). This is what we know from \\((fn + mg)/gn < (hn + mk)/kn\\).

**(b)**
\\(f/g < h/k\\) iff \\(f/g \cdot m/n < h/k \cdot m/n\\) where \\(m/n > 0\\)

If \\(f/g < h/k\\), then we know \\(fk < gh\\) and must prove \\(fm/gn < hm/kn\\) or equivalently \\(fmkn < hmgn\\). We can remove \\(mn\\) from both sides of the inequality to get \\(fk < hg\\), which is true from \\(f/g < h/k\\).

If \\(f/g \cdot m/n < h/k \cdot m/n\\), then we know \\(fmkn < hmgn\\) and must prove \\(f/g < h/k\\) or equivalently \\(fk < gh\\). We can multiply each side of the inequality by \\(mn\\) to get \\(fkmn < ghmn\\), which is true from \\(f/g \cdot m/n < h/k \cdot m/n\\).

### Exercise 1.15



### Exercise 1.16

If \\(x = y\\), then \\(|x - y| = |x - x| = |0| = 0\\). If \\(|x - y| = 0\\), then, from the definition of absolute value, \\(|x - y| = x - y\\). Substituting this into the above equality, we see that \\(x - y = 0\\). From here, it's simple to see \\(x = y\\).

If \\(x - y\\) is positive, \\(|y - x| = |-(x - y)| = x - y = |x - y|\\). If \\(x - y\\) is negative, \\(|x - y| = |-(y - x)| = y - x = |y - x|\\). If \\(x - y = 0\\), this is trivially true.

We know that \\(|x - z| = |x - y + y - z|\\).



### Exercise 1.17

**(a)**
\\(|a| \geq 0\\)

If \\(a \geq 0\\), then \\(|a| \geq 0\\) by the definition of absolute value. If \\(a < 0\\), then \\(0 < -a\\). We can do \\(|a| = |a - 0| = |0 - a| = |-a| = -a > 0\\) by symmetry to show that \\(|a| > 0\\).

**(b)**
\\(|a| = 0\\) iff \\(a = 0\\)

If \\(a = 0\\), then \\(|a| = 0\\). If \\(|a| = 0\\), then we show through the trichotomy property that \\(a = 0\\). If \\(a > 0\\), then \\(|a| > 0\\). If \\(a < 0\\), then \\(0 < -a\\) so \\(|a| = |-a| > 0\\). Therefore, \\(a = 0\\).

**(c)**
\\(|-a| = |a|\\)

\\[|a| = |a - 0| = |0 - a| = |-a|\\]

**(d)**
\\(|a \cdot b| = |a| \cdot |b|\\)

If \\(a \geq 0\\) and \\(b \geq 0\\), \\(|a \cdot b| = a \cdot b = |a| \cdot |b|\\).

If \\(a < 0\\) and \\(b < 0\\), \\(|a \cdot b| = |-a \cdot -b| = -a \cdot -b = a \cdot b = |a| \cdot |b|\\).

If \\(a \geq 0\\) and \\(b < 0\\), \\(|a \cdot b| = |a \cdot -b \cdot -1| = |-(a \cdot -b)| = |a \cdot -b| = a \cdot -b = |a| \cdot |-b| = |a| \cdot |b|\\). The same can be done for \\(a < 0\\) and \\(b \geq 0\\).

**(e)**
\\(-|a| \leq a \leq |a|\\)

If \\(a \geq 0\\), then \\(|a| = a\\). Therefore, \\(a \leq |a|\\) and \\(-|a| = -a \leq a\\) since \\(0 \leq a + a\\).

If \\(a < 0\\), then \\(|a| = |-a| = -a\\). Therefore, \\(-|a| \leq a\\) and \\(a \leq -a = |a|\\) since \\(a + a \leq 0\\).

**(f)**
\\(|a| \leq b\\) iff \\(-b \leq a \leq b\\)

If \\(a \geq 0\\), then \\(|a| = a\\). Therefore, if \\(|a| \leq b\\), then it's trivial to see \\(a \leq b\\). Moreover, \\(0 \leq b - a\\) which means \\(a - b \leq 0\\) and so \\(-b \leq -a\\). Since \\(a \geq 0\\), \\(-b \leq -a \leq a \leq b\\). If \\(-b \leq a \leq b\\), then \\(-b \leq |a| \leq b\\) and so \\(|a| \leq b\\).

If \\(a < 0\\), then \\(|a| = -a\\). Therefore, if \\(|a| \leq b\\), then \\(-b \leq a\\). Moreover, \\(0 \leq a + b\\) which means \\(-a - b \leq 0\\) and so \\(-a \leq b\\). Since \\(a < 0\\), \\(-b \leq a \leq -a \leq b\\). If \\(-b \leq a \leq b\\), then \\(-b \leq a\\) so \\(-a \leq b\\) which means \\(|a| \leq b\\).

**(g)**
\\(|a|^2 = a^2\\)

If \\(a \geq 0\\), then \\(|a|^2 = a^2\\). If \\(a < 0\\), then \\(|a|^2 = |-a|^2 = (-a)^2 = -1 \cdot -1 \cdot a \cdot a = a^2\\)

**(h)**
\\(|a - b| \geq ||a| - |b||\\)

If \\(a - b \geq 0\\), then \\(a \geq b\\) and we only need to prove \\(a - b \geq ||a| - |b||\\). If \\(b \geq 0\\), then \\(a \geq 0\\) and so we only need to show \\(a - b \geq |a - b| = a - b\\) which is trivially true. If \\(b < 0\\), then we need to show \\(a - b \geq ||a| + b|\\). In this scenario, if \\(a \geq 0\\) or \\(a < 0\\), then this simplifies to \\(a - b \geq a + b\\) or \\(a - b \geq |-(a - b)| = a - b\\). The latter is trivially true and the former is true since \\(b < 0\\).

If \\(a - b > 0\\), then \\(a < b\\) and we need to show that \\(b - a \geq ||a| - |b||\\). If \\(a \geq 0\\), then \\(b \geq 0\\) as well and so \\(b - a \geq |a - b| = |-(b - a)| = b - a\\). If \\(a < 0\\), then we need to show \\(b - a \geq |-a -|b||\\). In this scenario, if \\(b < 0\\), then \\(b - a \geq |-a + b| = b - a\\) which is trivially true. Moreover, if \\(b \geq 0\\), then \\(b - a \geq |-a - b| = a + b\\) which is true since \\(a < 0\\).

**(i)**
\\(|a + b| = |a| + |b|\\) iff \\(ab \geq 0\\)

Assume \\(|a + b| = |a| + |b|\\). If \\(a + b \geq 0\\), then \\(a + b = |a| + |b|\\) which means \\(|a| = a\\) and \\(|b| = b\\) so \\(ab \geq 0\\). If \\(a + b < 0\\), then \\(-(a + b) = -a + -b = |a| + |b|\\) which means \\(|a| = -a\\) and \\(|b| = -b\\) so \\(ab = -a \cdot -b \geq 0\\).


If \\(ab \geq 0\\), then either \\(a \geq 0\\) and \\(b \geq 0\\) or \\(a \leq 0\\) and \\(b \leq 0\\). If \\(a \geq 0\\) and \\(b \geq 0\\), then \\(|a + b| = a + b = |a| + |b|\\). If \\(a \leq 0\\) and \\(b \leq 0\\), then \\(|a + b| = |-(a + b)| = -(a + b) = -a + -b = |a| + |b|\\).

### Exercise 1.18

If \\(a \leq b \leq c\\), then \\(a - b \geq 0\\) and \\(b - c \geq 0\\). Therefore, from Exercise 1.17(i), \\(|(a - b) + (b - c)| = |a - b| + |b - c|\\). Simplifying this gives us \\(|a - b| + |b - c| = |a - c|\\).

If \\(|a - b| + |b - c| = |a - c|\\), then by Exercise 1.17(i), \\((a - b)(b - c) \geq 0\\). This means \\((a - b)\\) and \\((b - c)\\) must both be positive or negative. However, if they are both positive, then \\(a - b \geq 0 \implies a \geq b\\) and \\(b - c \geq 0 \implies b \geq c\\) so \\(a \geq c\\) violating our assumption that \\(a \leq c\\). When they are both negative, the same reasoning shows that \\(a \leq b \leq c\\).

### Exercise 1.19

From Exercise 1.17(e), to show that \\(|x - y| \leq b - a\\) we can show that \\(-(b - a) \leq x - y \leq b - a\\). We also know that since \\(a \leq x \leq b\\), \\(0 \leq x - a \leq b - a\\) and \\(-(b - a) \leq x - b \leq 0\\). Since \\(a \leq y \leq b\\), this means that \\(-(b - a) \leq x - y \leq b - a\\).

### Exercise 1.20



### Exercise 1.21

**(a)**
\\(\lim(1/n) = 0\\)

To prove this, we must show that \\(| 1/n - 0 | < \varepsilon\\) for all \\(n > N\\) or \\(1/n < \varepsilon\\) since \\(n > 0\\). First, we can see that \\(1/n\\) is strictly decreasing since \\(1/n > 1/(n+1)\\). This is true since \\(n+1 > n\\) is obviously true. Therefore, if \\(N = 1/\varepsilon\\), then for all \\(n > N\\), \\(1/n < \varepsilon\\) since if \\(n = 1/\varepsilon\\) then \\(1/n = \varepsilon\\) and \\(1/n\\) is strictly decreasing.

**(b)**
\\(\lim(1/n^3) = 0\\)

We can use the Squeeze Theorem to show this limit is true. We know that \\(1/n^3 < 1/n\\) for \\(n > 0\\) since \\(n < n^3\\). We also know that \\(0/1 < 1/n^3\\) for \\(n > 0\\) since \\(0 < 1\\). Since \\(0 < 1/n^3 < 1/n\\) and \\(\lim(0) = 0\\) and \\(\lim(1/n) = 0\\), by the Squeeze Theorem, \\(\lim(1/n^3) = 0\\).

**(c)**
\\(\lim\frac{2 + n - n^2}{4 + 5n + 3n^2} = -\frac{1}{3}\\)



### Exercise 1.22

We want to show that \\((|a_n|)\\) is a Cauchy sequence given that \\((a_n)\\) is a Cauchy sequence. From the definition of a Cauchy sequence, we know that for every \\(\varepsilon > 0\\), there is \\(N\\) such that \\(|a_m - a_n| < \varepsilon\\) for all \\(m, n > N\\). From Exercise 1.17(h), we know that \\(||a_n| - |a_m|| \leq |a_n - a_m|\\) for \\(m > n\\). Therefore, for every \\(\varepsilon > 0\\), there is \\(N\\) such that \\(||a_n| - |a_m|| < \varepsilon\\) for all \\(m, n > N\\) so \\((|a_n|)\\) is a Cauchy sequence.

### Exercise 1.23

Let \\(b_n\\) be a constant sequence that equals \\(k\\) for all \\(n\\). This implies \\(k a_n = b_n a_n\\). Using Theorem 1.20, \\(\lim (k a_n) = \lim (b_n a_n) = (\lim b_n)(\lim a_n) = k \lim (a_n)\\).

### Exercise 1.24



### Exercise 1.25

We can prove there is a minimum and a maximum via induction over the size of the finite set of elements of the ordered field, denoted \\(n\\). For the base case where \\(n = 1\\), the only element in the set is the minimum and maximum. Now, we assume that there is a minimum and maximum in a finite set of size \\(n\\) and must prove they exist for a finite set of size \\(n + 1\\). We can take \\(n\\) elements of the set with \\(n + 1\\) and see that it has a minimum and maximum value. Then with the leftover element, we can compare it against the minimum and maximum. If it is less than the minimum, then the element is the minimum of the set. Otherwise the minimum stays the same. If it is more than the maximum, then the element is the maximum of the set. Otherwise the maximum stays the same. Therefore, there is a minimum and maximum of a finite set of elements of an ordered field.

### Exercise 1.26

Let \\(\varepsilon > 0\\). There is \\(N \in \mathbb{N}\\) such that \\(|a_n - a| < \varepsilon\\) for all \\(n > N\\) where \\(a_n \to a\\). Since \\(m, m + 1, \cdots\\) is a strictly increasing sequence of natural numbers, there is \\(N' \in \mathbb{N}\\) such that \\(m + n > N\\) for all \\(n > N'\\). It follows that \\(|a_{m + n} - a| < \varepsilon\\) for all \\(n > N'\\). Therefore, \\(a_{m + n} \to a\\).

### Exercise 1.27



### Exercise 1.28


