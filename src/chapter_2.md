# Chapter 2: Real Numbers

### Exercise 2.1

Suppose there are two supremums for a nonempty subset of an ordered field called \\(a\\) and \\(b\\). This means they are both upper bounds and they are both less than or equal to all other upper bounds of this subset. As a result, \\(a \leq b\\) and \\(b \leq a\\) implying that \\(a = b\\).

The same argument can be made for infimums as well with the infimums \\(a\\) and \\(b\\) having to satisfy \\(a \geq b\\) and \\(b \geq a\\). Therefore, \\(a = b\\) must be true.

### Exercise 2.2

Every bounded above subset of a field has an associated subset that is bounded below taking every element in the original subset to its additive inverse. We know it is bounded below since \\(x \leq b\\) implies \\(-b \leq -x\\) for all elements in the original subset \\(x\\) and the original supremum \\(b\\). Moreover, \\(-b\\) is the infimum of the new subset since \\(b \leq b'\\) for any upper bound \\(b'\\) implies \\(-b' \leq -b\\) for any lower bound \\(-b'\\). Therefore, the two definitions are equivalent.

### Exercise 2.3

If \\(p < r < s < q\\), then \\(p < r\\) and \\(s < q\\). This means that \\(s + p < q + r\\). Rearranging, we get \\(s - r < q - p\\).

### Exercise 2.4

Let \\(m = n + i\\) and we will show via induction that \\(a_n \leq a_m\\) and \\(b_n \geq b_m\\) for natural numbers \\(n < m\\). When \\(i = 1\\), previous part of the Lemma proves this. Now we assume that for \\(m = n + i\\), \\(a_n \leq a_m\\) and \\(b_n \geq b_m\\) and must prove \\(a_n \leq a_{m + 1}\\) and \\(b_n \geq b_{m + 1}\\). From the previous part, we know that \\(a_m \leq a_{m + 1}\\) and \\(b_{m} \geq b_{m + 1}\\). From transitivity, this must mean that \\(a_n \leq a_{m + 1}\\) and \\(b_n \geq b_{m + 1}\\).

### Exercise 2.5



### Exercise 2.6

For the sake of contradiction, assume the opposite: that \\(\sup A > \inf B\\). This means that there exists \\(\varepsilon > 0\\) such that \\(\sup A - \inf B = \varepsilon\\). From Theorem 2.1, there exists an element \\(x \in A\\) where \\(x > \sup A - \varepsilon\\). Substituting \\(\varepsilon\\) for \\(\sup A - \inf B\\) reveals the contradiction, \\(x > \inf B\\). From our assumptions, \\(a \leq b\\) for all \\(a \in A\\) and \\(b \in B\\) so \\(x > \inf B\\) violates our premise proving that \\(\sup A \leq \inf B\\).

### Exercise 2.7

Let \\(\sup A = a\\) and \\(\sup B = b\\).

First, let's assume \\(a < b\\). This means that for all \\(x \in B\\), \\(x \leq a\\). In other words, \\(a\\) is an upper bound of \\(B\\) as well. Moreover, the supremum of \\(A \cup B\\) must be \\(a\\) since if there was a smaller upper bound than \\(a\\) then it would need to also be the supremum of \\(A\\) as well. Therefore \\(\sup(A \cup B) = \sup A\\) when \\(a < b\\).

The same argument can be made when \\(b < a\\) to show that the supremum of \\(A \cup B\\) in this scenario would be \\(sup B\\). When \\(a = b\\), then both are supremums of each set so \\(\sup(A \cup B) = a = b\\). Taking everything in, we get that \\(\sup(A \cup B) = \max\\{a, b\\}\\).

### Exercise 2.8

Let \\(\sup A = a\\) and \\(\sup B = b\\).

We know that \\(a + b\\) is an upper bound for \\(A + B\\) since \\(x \leq a\\) and \\(y \leq b\\) for all \\(x \in A\\) and \\(y \in B\\) so \\(x + y \leq a + b\\). If there was a smaller lower bound \\(c\\), then \\(0 < \varepsilon = a + b - c\\). Since \\(a\\) and \\(b\\) are suprema, then there exists \\(x \in A\\) such that \\(\varepsilon/2 > a - x\\) and \\(y \in B\\) such that \\(\varepsilon/2 > b - y\\). Therefore, \\(x + y > a + b - \varepsilon\\) so \\(\varepsilon > a + b - (x + y)\\). Putting everything together,

\\[
  \begin{align}
    a + b - (x + y) &< \varepsilon = a + b - c \\\\
    - (x + y) &< - c \\\\
    c &< x + y \\\\
  \end{align}
\\]

This is an obvious contradiction, the supremum of \\(A + B\\) cannot be less than an element in \\(A + B\\). Therefore, \\(a + b\\) is the supremum of \\(A + B\\).

### Exercise 2.9

Let \\(\sup E = f\\) and \\(\inf E = g\\).

We know that, for all \\(x \in E\\), \\(x \leq f\\) and \\(g \leq x\\). Multiplying by the given \\(c > 0 \in \mathbb{R}\\), we get \\(cx \leq cf\\) and \\(cg \leq cx\\). This implies that \\(cf\\) is an upper bound for \\(cE\\) and \\(cg\\) is a lower bound. We can also see that these are the supremum and infimum of \\(cE\\). This is because we know that \\(f \leq f'\\) for any upper bound \\(f'\\) and \\(g' \leq g\\) for any lower bound \\(g'\\). Again, multiplying by \\(c\\) on both sides shows that \\(cf\\) and \\(cg\\) are the least upper bound and greatest lower bound respectively when \\(c > 0\\).

When \\(c < 0\\), we can obtain similar but different results. Instead, we can multiply by \\(-c\\) to find \\(cf \leq cx\\) and \\(cx \leq cg\\) for \\(x \in E\\). In other words, \\(cf\\) is a lower bound and \\(cg\\) is an upper bound for \\(cE\\). We can similarly find that \\(cf' \leq cf\\) and \\(cg \leq cg'\\) for any upper bound \\(f'\\) and lower bound \\(g'\\). Therefore, \\(cf\\) and \\(cg\\) are the greatest lower bound and least upper bound respectively when \\(c < 0\\).

### Exercise 2.10

Suppose, for the sake of contradiction, that \\(\inf E > \inf E'\\). Since it is a lower bound, \\(\inf E \leq x\\) for any \\(x \in E\\). Since \\(E'\\) is a subset of \\(E\\), this means \\(\inf E\\) is a lower bound for \\(E'\\) as well. It is also a greater lower bound than \\(\inf E'\\) by our assumption resulting in our contradiction. Therefore, \\(\inf E \leq \inf E'\\).

Showing that \\(\inf E' \leq \sup E'\\) is trivial and results by definition of upper bound and lower bound.

Suppose, for the sake of contradiction, that \\(\sup E' > \sup E\\). Since it is an upper bound, \\(x \leq \sup E\\) for any \\(x \in E\\). Since \\(E'\\) is a subset of \\(E\\), this means \\(\sup E\\) is an upper bound for \\(E'\\) as well. It is also a smaller upper bound than \\(\sup E'\\) by our assumption resulting in our contradiction. Therefore, \\(\sup E' \leq \sup E\\).

### Exercise 2.11

Suppose \\(b\\) is the supremum. Since \\(b\\) is the least upper bound and \\(b - 1/n < b\\), \\(b - 1/n\\) cannot be an upper bound or it would contradict the definition of supremum. Moreover, since \\(b + 1/n > b\\) and \\(b\\) is an upper bound, \\(b + 1/n\\) must also be an upper bound as well.

Suppose for every natural number \\(n\\) that \\(b - 1/n\\) is not an upper bound and \\(b + 1/n\\) is an upper bound. Since \\(\lim(b + 1/n) = b\\), this means \\(b\\) is also an upper bound. Moreover, if there existed a lower upper bound \\(b'\\) such that \\(b' = b - \varepsilon\\) where \\(\varepsilon > 0\\), then for \\(n > 1/\varepsilon\\) we can see that \\(b - \varepsilon\\) is not an upper bound so \\(b'\\) cannot be a supremum. Therefore, \\(b\\) is the supremum.

### Exercise 2.12

For the sake of contradiction, suppose \\(\sqrt{2} + \sqrt{3}\\) is a rational number. That is, \\(\sqrt{2} + \sqrt{3} = p/q\\).

### Exercise 2.13

Let \\(a = p/q\\).

For the sake of contradiction, suppose \\(a + b = r/s\\). Substituting \\(a = p/q\\), we get \\(b = (qr - ps)/qs\\) which is a contradiction as \\(b\\) is irrational.

For the sake of contradiction, suppose \\(a - b = r/s\\). Substituting \\(a = p/q\\), we get \\(b = (qr + ps)/qs\\) which is a contradiction as \\(b\\) is irrational.

For the sake of contradiction, suppose \\(a/b = r/s\\). Substituting \\(a = p/q\\), we get \\(b = ps/qr\\) which is a contradiction as \\(b\\) is irrational.

For the sake of contradiction, suppose \\(b/a = r/s\\). Substituting \\(a = p/q\\), we get \\(b = pr/qs\\) which is a contradiction as \\(b\\) is irrational.

### Exercise 2.14

Reflexivity: Since \\(\lim(a_n - a_n) = \lim(0) = 0\\), the relation is reflexive.

Symmetry: If \\((a_n) \sim (b_n)\\), then \\(\lim(a_n - b_n) = 0\\). This means \\(\lim(a_n) - \lim(b_n) = 0\\) so \\(\lim(a_n) = \lim(b_n)\\) so \\(0 = \lim(b_n) - \lim(a_n)\\) so \\(0 = \lim(b_n - a_n)\\). Therefore, \\((b_n) \sim (a_n)\\) and the relation is symmetric.

Transitivity: If \\((a_n) \sim (b_n)\\) and \\((b_n) \sim (c_n)\\), then \\(\lim(a_n - b_n) = 0\\) and \\(\lim(b_n - c_n) = 0\\). This means \\(\lim(a_n) = \lim(b_n)\\) and \\(\lim(b_n) = \lim(c_n)\\). Therefore, \\(\lim(a_n) = \lim(c_n)\\) so \\(\lim(c_n - a_n) = 0\\) and \\((a_n) \sim (c_n)\\).

### Exercise 2.15



### Exercise 2.16

Since \\(E\\) is a dense subset, this means for any \\(a \in \mathbb{F}\\) and \\(\varepsilon > 0 \in \mathbb{F}\\), there is an element \\(x \in E\\) such that \\(|x - a| < \varepsilon\\). Equivalently, \\(a - \varepsilon < x < a + \varepsilon\\). We are given \\(x < y\\) so \\(y = x + \varepsilon\\) for some \\(\varepsilon > 0\\). From the definition of a dense subset, there is \\(r \in E\\) such that \\(x - \varepsilon < r < x + \varepsilon\\). Therefore, \\(x < r < y\\).

### Exercise 2.17



### Exercise 2.18

**(a)** \\(\phi\\) is a one-to-one mapping

To show \\(\phi\\) is a one-to-one mapping, we must show that \\(\phi(x) = \phi(y) \implies x = y\\). The left hand side of the implication shows that \\(\phi(x) - \phi(y) = 0\\) which consequently show \\(\phi(x - y) = 0\\). Since \\(\phi(0) = 0\\) (this is proven in the next section), this means \\(\phi(x - y) = \phi(0)\\) and so \\(x - y = 0\\) meaning \\(x = y\\).

**(b)** \\(\phi(0) = 0\\) and \\(\phi(1) = 1\\)

We start by showing that \\(\phi(0) = \phi(0 + 0) = \phi(0) + \phi(0)\\). Since \\(\phi(0) = \phi(0) + \phi(0)\\), this means \\(\phi(0) = 0\\).

Similarly, \\(\phi(1) = \phi(1 \cdot 1) = \phi(1) \cdot \phi(1)\\). Since \\(\phi(1) = \phi(1) \cdot \phi(1)\\), this means \\(\phi(1) = 1\\).

**(c)** \\(\phi(\mathbb{F})\\) is an ordered subfield of \\(\mathbb{G}\\)

I'm pretty sure the requirements for an embedding, that \\(\phi(a + b) = \phi(a) + \phi(b)\\) and \\(\phi(a \cdot b) = \phi(a) \cdot \phi(b)\\) and \\(a < b\\) iff \\(\phi(a) < \phi(b)\\), directly prove that \\(\phi(\mathbb{F})\\) is an ordered subfield of \\(\mathbb{G}\\).

### Exercise 2.19



### Exercise 2.20



### Exercise 2.21



### Exercise 2.22



### Exercise 2.23



### Exercise 2.24



### Exercise 2.25



### Exercise 2.26



### Exercise 2.27



### Exercise 2.28



### Exercise 2.29



### Exercise 2.30



### Exercise 2.31


