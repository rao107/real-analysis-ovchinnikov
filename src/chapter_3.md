# Chapter 3: Continuous Functions

### Exercise 3.1

If for every \\(x \in G\\), there is an \\(\varepsilon\\)-neighborhood of \\(x\\) such that \\((x - \varepsilon, x + \varepsilon) \subseteq G\\), then \\(G\\) satisfies the definition of an open subset.

If \\(G\\) is an open subset, then for all \\(x \in G\\), there is a neighborhood \\((a, b)\\) such that \\(a < x < b\\). Let \\(\varepsilon = \min\\{x - a, b - x\\}\\). If \\(\varepsilon = x - a\\), then \\(a < x < b\\) implies \\(x - \varepsilon < x < b\\) and since \\(x - a \leq b - x\\), this means \\(x - \varepsilon < x < x + \varepsilon\\). If \\(\varepsilon = b - x\\), then this also implies \\(a < x < x + \varepsilon\\) and since \\(b - x \leq x - a\\), this means \\(x - \varepsilon < x < x + \varepsilon\\).

### Exercise 3.2

If \\(f(x) = f(y)\\), then \\(px + q = py + q \implies px = py \implies x = y\\). Therefore, \\(f\\) is injective. For all \\(y \in \mathbb{F}\\), there exists \\(x = (y - q)/p \in \mathbb{F}\\) such that \\(f(x) = y\\). Therefore, \\(f\\) is surjective. To show \\(f\\) preserves order on \\(\mathbb{F}\\), assume \\(x < y\\). We can see that \\(x < y \implies px < py \implies px + q < py + q \implies f(x) < f(y)\\). Putting these together, \\(f\\) is a bijection preserving order on \\(\mathbb{F}\\).

Since \\(G\\) is an open set, any point \\(x \in G\\) has an \\(\varepsilon\\)-neighborhood, \\((x - \varepsilon, x + \varepsilon) \subseteq G\\). This subset corresponds to the inequality \\(x - \varepsilon < x < x + \varepsilon\\). Since \\(f\\) is a bijection preserving order on \\(\mathbb{F}\\), this means \\(f(x - \varepsilon) < f(x) < f(x + \varepsilon)\\). With some algebra, we can see this is equivalent to \\(f(x) - p\varepsilon < f(x) < f(x) + p\varepsilon\\). Setting \\(\varepsilon' = p\varepsilon\\), we can see every element \\(f(x) \in f(G)\\) has an \\(\varepsilon\\)-neighborhood so \\(f(G)\\) is open.

### Exercise 3.3

We can assume \\(I\\) is an open interval \\((a, b)\\) and our result holds for all other intervals. For any \\(x \in I\\), we know by definition that \\(a < x < b\\). Any neighborhood of \\(x\\), denoted \\((a', b')\\), would need to satisfy \\(a' < x < b'\\). If \\(a' < a\\) or \\(b < b'\\), then it is trivial to see that \\((a', b')\\) contains a point in \\((a, b)\\). If \\(a < a'\\) and \\(b' < b\\), then we can see that the element \\((x + a') / 2\\) is also in both open intervals. Therefore, any point in \\(I\\) is a limit point.

### Exercise 3.4

what if closed set \\(F\\) is only rational numbers but sequence converges to irrational number?

### Exercise 3.5

Suppose \\(x - y > 0\\). This means \\(x - y < \varepsilon\\) so \\(x - \varepsilon < y\\). For any \\(a \in (y - \varepsilon, y + \varepsilon)\\), by definition \\(y - \varepsilon < a < y + \varepsilon\\). In terms of \\(x\\), we can see \\(x - 2\varepsilon < a < x\\).

Suppose \\(-(x - y) > 0\\). This means \\(y - x < \varepsilon\\) so \\(y < x + \varepsilon\\). For any \\(a \in (y - \varepsilon, y + \varepsilon)\\), by definition \\(y - \varepsilon < a < y + \varepsilon\\). In terms of \\(x\\), we can see \\(x < a < x + 2\varepsilon\\).

In either case, any element in \\((y - \varepsilon, y + \varepsilon)\\) will also be in \\((x - 2\varepsilon, x + 2\varepsilon)\\).

### Exercise 3.6

Consider the sequence of points \\(a_n = 1/n\\) which is in \\(\\{1/n : n \in \mathbb{N}\\}\\). We have already shown that the sequence converges to \\(0\\) previously. Since \\(0 \notin \\{1/n : n \in \mathbb{N}\\}\\), the set is not compact.

### Exercise 3.7



### Exercise 3.8

Since \\(\\{x_n : n \in \mathbb{N}\\}\\) is finite, then there must be an element in the set that \\((x_n)\\) repeats infinitely. If there wasn't, then \\((x_n)\\) would need to be finite, a contradiction to the size of \\(\mathbb{N}\\). Let the subsequence \\((x'_n)\\) be a constant sequence for the element that repeats infinitely. This subsequence is obviously convergent.

### Exercise 3.9



### Exercise 3.10

Assume \\(\lim (x_n) \to x\\). For the sake of contradiction, also assume that there exists a neighborhood of \\(x\\) that does not contain infinitely many terms of \\((x_n)\\). That is, there are only finitely many \\(n\\) such that \\(x_n \in (x - \varepsilon, x + \varepsilon)\\). Since convergent sequences are Cauchy, there exists \\(N\\) such that for all \\(m > N\\), \\(|x_m - x| < \varepsilon\\). Since there are an infinite number of such \\(m\\), there cannot be finitely many terms of \\((x_n)\\) in any neighborhood of \\(x\\).

Assume every neighborhood of \\(x\\) contains infinitely many terms of \\((x_n)\\). For the sake of contradiction, also assume that \\(\lim (x_n) \nrightarrow x\\). However, from our assumption, for any \\(\varepsilon > 0\\) the neighborhood \\((x - \varepsilon, x + \varepsilon)\\) will contain infinitely many terms of \\((x_n)\\). Therefore, for any \\(N\\) there will always exist \\(n > N\\) such that \\(x - \varepsilon < x_n < x + \varepsilon\\). Therefore, \\(\lim (x_n) \to x\\).

### Exercise 3.11

For any sequence of points in the union of two compact sets, there are two subsequences divided by the original sets. At least one of the subsequences must have an infinite number of terms or the original sequence is finite. Since each set is compact, a subsequence of the subsequence must converge to a point in the set. The union of the two compact sets will also contain this point. Therefore, the union is compact.

### Exercise 3.12

The intersection of two compact sets must be compact. For the sake of counterargument, assume it is not true. That is, there exists there is a sequence in the intersection of compact sets where every subsequence converges to a point outside of the intersection. Since this sequence was in both compact sets, that means its limit must also be in both compact sets as well. In other words, every subsequence must converge inside the intersection of compact sets.

Any family of compact sets must also be compact in the same way. Assume the intersection of \\(k\\) compact sets is compact. The same argument can be made to show that the intersection of \\(k + 1\\) compact sets is also compact.

### Exercise 3.13

Since \\(E\\) and its superset are both compact, the intersection of these two sets must also be compact as shown in Exercise 3.12. The intersection of a set and its subset is the subset so \\(E\\) is the compact intersection.

### Exercise 3.14



### Exercise 3.15



### Exercise 3.16

**(a)** \\(f + g\\)



**(b)** \\(k \cdot f, k \in \mathbb{F}\\)

**(c)** \\(f \cdot g\\)

**(d)** \\(f/g\\), where \\(g(x) \neq 0\\) on \\(E\\)

**(e)** \\(|f|\\)

### Exercise 3.17



### Exercise 3.18



### Exercise 3.19

Suppose for the sake of counterargument that \\([a, b] \nsubseteq E\\). This would mean that there exists \\(x\\) such that \\(a \leq x \leq b\\) and \\(x \notin E\\). However, this would mean that \\(E = [a, x) \cup (x, b]\\). In other words, \\(E\\) is disconnected, a contradiction. Therefore, \\([a, b] \subseteq E\\).

### Exercise 3.20



### Exercise 3.21



### Exercise 3.22



### Exercise 3.23

First, we show that \\(f(x) = x^n, x \in [0, \infty) \subseteq \mathbb{R}\\) is a strictly increasing function. To show that it is strictly increasing, we need to show that \\(x^n < (x + \varepsilon)^n\\) for \\(\varepsilon > 0\\).

Using Theorem 3.24, we can now see that its inverse function, \\(f^{-1}(x) = \sqrt[n]{x}\\) is continuous.

### Exercise 3.24



### Exercise 3.25



### Exercise 3.26



### Exercise 3.27



### Exercise 3.28


