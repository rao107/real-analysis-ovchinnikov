# Appendix A: Natural Numbers and Integers

### Exercise A.1

We can see that \\(s\\) is one-to-one from **P2** of the Peano Axioms.

Every element in \\(N \setminus \\{1\\}\\) can be expressed as \\(a + s(b)\\). From Theorem 1, there is \\(s(a + b)\\) that equals this element so \\(s\\) is onto.

Therefore, \\(s\\) is a bijection.

This can be done over and over with no end and the resulting set can still have a bijection to a smaller one. Therefore, the set \\(N\\) must be an infinite collection of elements.

### Exercise A.2

From **P1** of the Peano Axioms, we know that \\(s(1) \neq 1\\). Given that \\(s(a) \neq a\\), then \\(s(s(a)) \neq s(a)\\) from **P2** of the Peano Axioms.

### Exercise A.3

Given \\(a \in N\\), define \\(M = \\{b \in N : a + b \neq b\\}\\). We can see that \\(1 \in M\\) since \\(a + 1 \neq 1\\). Moreover, if \\(c \in M\\) then \\(s(c)\\) must also be in \\(M\\) since \\(a + c \neq c\\) implies \\(s(a + c) \neq s(c)\\) and finally \\(a + s(c) \neq s(c)\\).

From the Axiom of Induction, \\(M = N\\) so \\(a + b \neq b\\) for all \\(a, b \in N\\).

### Exercise A.4

**(a)** Suppose there are two different least elements \\(a, b \in N\\). By definition, \\(a \leq b\\) and \\(b \leq a\\). It is not possible for either \\(a < b\\) or \\(b < a\\) without contradicting prior definitions. Therefore, \\(a = b\\).

**(b)** If there was an element \\(a \in N\\) that was not 1 that was the least element of \\(N\\), then there exists \\(n\\) such that \\(1 = a + n\\). However, from **P1** of the Peano Axioms, \\(s(a) \neq 1\\) for all \\(a\\). This is a contradiction so 1 must be the least element of \\(N\\).

Suppose there was a greatest element of \\(N\\) called \\(a\\). This element is greater than or equal to all other elements in \\(N\\). However, \\(s(a) > a\\) which is a contradiction. Therefore, there is no greatest element of \\(N\\).

### Exercise A.5

We know that \\((m', n') \sim (m, n)\\) and \\((p', q') \sim (p, q)\\). By definition, this means \\(m' + n = n' + m\\) and \\(p' + q = q' + p\\).

For the equality to hold, this requires \\((m' + p', n' + q') \sim (m + p, n + q)\\). In turn, this means \\((m' + p') + (n + q) = (n' + q') + (m + p)\\). Using the equalities above, this is true.

### Exercise A.6

\\[
  \begin{align}
    [m', n'] \cdot [p', q'] &= [m, n] \cdot [p, q] \\\\
    [m' q' + n' p', n' q' + m' p'] &= [m q + n p, n q + m p] \\\\
  \end{align}
\\]

To prove the above equality, we want to show that
\\[(m' q' + n' p') + (n q + m p) = (n' q' + m' p') + (m q + n p)\\]

Since \\((m', n') \sim (m, n)\\) and \\((p', q') \sim (p, q)\\), this means \\(m' + n = n' + m\\) and \\(p' + q = q' + p\\).

TODO

TODO

TODO

### Exercise A.7

There must be a zero element due to condition **R3**. To show the zero element is unique, assume there are two zero elements, \\(0\\) and \\(0'\\), for the sake of contradiction. By **R1**, \\(0 + 0' = 0' + 0\\). Since both are zero elements, this simplifies to \\(0 = 0'\\). Therefore, the zero element is unique.

### Exercise A.8

There must exist a unique additive inverse \\(-a\\) due to **R3**. To show this additive inverse is unique, assume there are two additive inverses, \\(-a\\) and \\(-a'\\), for the element \\(a\\). From **R2**, \\(-a + (a + -a') = (-a + a) + -a'\\). Since they are additive inverses, ths simplifies to \\(-a = -a'\\). Therefore, the additive inverse is unique.

### Exercise A.9

**(a)** \\(R = \\{0\\}\\)

By exhaustion, we can see that for all elements in \\(\\{0\\}\\),

\\[
  0 + 0 = 0 + 0 \\\\
  0 + (0 + 0) = (0 + 0) + 0 \\\\
  \text{There is } 0 \in R \text{ such that } 0 + 0 = 0 \\\\
  0 \cdot (0 \cdot 0) = (0 \cdot 0) \cdot 0 \\\\
  0 \cdot (0 + 0) = 0 \cdot 0 + 0 \cdot 0 \text{ and } (0 + 0) \cdot 0 = 0 \cdot 0 + 0 \cdot 0
\\]

All of these expressions evaluate to 0.

**(b)** \\(R = \mathbb{Z}_2\\)

Proving **R1**:
When \\(a = b\\), this is proven by reflexivity. For \\(0 + 1 = 1 + 0\\), both sides evaluate to \\(1\\).

Proving **R2**:
When \\(a = 0\\), both sides simplify to \\(b + c = b + c\\) which is true by reflexivity. Looking at the case where \\(a = 1\\), when \\(b = 0\\) both sides simplify to \\(1 + c = 1 + c\\) which is true by reflexivity. Now when \\(a = b = 1\\), we can look at both cases where \\(c = 0\\) and \\(c = 1\\) and see the equality holds and is equal to \\(0\\) and \\(1\\) respectively.

Proving **R3**:
When \\(a = 0\\), then \\(x = 0\\) for \\(b = 0\\) or \\(x = 1\\) for \\(b = 1\\). When \\(a = 1\\), then \\(x = 1\\) for \\(b = 0\\) or \\(x = 0\\) for \\(b = 1\\).

Proving **R4**:
When \\(a = 0\\) or \\(b = 0\\) or \\(c = 0\\), the product is \\(0\\) on both sides. When \\(a = b = c = 1\\), then both sides evaluate to \\(1\\).

Proving **R5**:
For \\(a \cdot (b + c)\\), when \\(a = 0\\) this is true since \\(0\\) or \\(1\\) times \\(0\\) is \\(0\\). When \\(a = 1\\), then the equality evaluates to \\(b + c = b + c\\) which is trivially true by reflexivity.

**(c)** \\(R = 2\mathbb{Z}\\)

Since addition and multiplication are taken from \\(\mathbb{Z}\\), **R1**, **R2**, **R4**, and **R5** are all still true. To show **R3** is true, we must show \\(x \in 2\mathbb{Z}\\). Fix \\(a = 2m\\) and \\(b = 2n\\). Solving for \\(x\\), we find \\(x = 2n - 2m = 2(n - m)\\). Therefore, \\(x \in 2\mathbb{Z}\\).

**(d)** \\(R = 2^X\\)

Proving **R1**:

\\(A \bigtriangleup B = (A \setminus B) \cup (B \setminus A) = (B \setminus A) \cup (A \setminus B) = B \bigtriangleup A\\)

Proving **R2**:

\\(A \bigtriangleup (B \bigtriangleup C) = A \bigtriangleup ((B \setminus C) \cup (C \setminus B)) = (A \setminus ((B \setminus C) \cup (C \setminus B))) \cup (((B \setminus C) \cup (C \setminus B)) \setminus A) \\)

???

TODO

TODO

TODO

**(e)** \\(R = \langle F, +, \cdot \rangle\\)

TODO

TODO

TODO

### Exercise A.10

From Theorem 18, every element has a unique additive inverse. Therefore, if we add the additive inverse of \\(c\\), \\(-c\\), to both sides of \\(a + c = b + c\\), then these cancel to leave us with \\(a + b\\).

### Exercise A.11

For the sake of contradiction, let's assume there are two identity elements of a ring, \\(1\\) and \\(1'\\). This means that \\(1 \cdot 1' = 1\\). However, since this is the identity element, it also means that \\(1 \cdot 1' = 1' \cdot 1 = 1'\\). Therefore, \\(1 = 1'\\).

### Exercise A.12

TODO

TODO

TODO

### Exercise A.13

TODO

TODO

TODO

### Exercise A.14

TODO

TODO

TODO
