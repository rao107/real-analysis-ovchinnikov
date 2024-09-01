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



### Exercise 3.7



### Exercise 3.8



### Exercise 3.9



### Exercise 3.10



### Exercise 3.11



### Exercise 3.12



### Exercise 3.13



### Exercise 3.14



### Exercise 3.15



### Exercise 3.16



### Exercise 3.17



### Exercise 3.18



### Exercise 3.19



### Exercise 3.20



### Exercise 3.21



### Exercise 3.22



### Exercise 3.23



### Exercise 3.24



### Exercise 3.25



### Exercise 3.26



### Exercise 3.27



### Exercise 3.28


