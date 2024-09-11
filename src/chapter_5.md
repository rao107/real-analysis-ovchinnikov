# Chapter 5: Integration

### Exercise 5.1

We can prove that a finite subset of an ordered field containing more than one element can be enumerated by using induction on the size of the subset \\(n\\). For the base case of \\(n = 2\\), it is obvious that the two elements can be sorted whether the first is smaller than the second or vice versa. For the inductive case, we can assume that we can order a finite subset of size \\(n\\) and must show that a finite subset of size \\(n + 1\\) can be ordered in the same way.

TODO

TODO

TODO

### Exercise 5.2

Let \\(n\\) be the number of elements in the nonempty subset of an ordered field. If \\(n = 1\\), then the maximum element of the subset is the only element in the subset. For the inductive case, we assume that there is a maximum element for an \\(n\\) element subset and must show there is a maximum element for a subset with \\(n + 1\\) elements. We can find the maximum of \\(n\\) elements in the \\(n + 1\\) subset and compare this maximum to the leftover element. If the leftover element is greater than the maximum, then it is the maximum of the entire subset due to transitivity. Otherwise, the maximum is still the maximum.

### Exercise 5.3

We only need to show that a refinement with one extra element satisfies these since refinements with more elements can be created through successive refinements adding an additional element each time. Let \\(q \in Q\\) be this element. By definition of refinement, \\(P \subset Q\\) and \\(q \notin P\\). We can easily see that all the subintervals of \\(Q\\) are the same as \\(P\\) except for the subinterval containing \\(q\\). For this subinterval in \\(Q\\), it is split into two at \\(q\\). Both of these are subintervals of the original subinterval in \\(P\\). Therefore, the first claim is proven.

Again, we only prove that \\(\|Q\| \leq \|P\|\\) for a refinement with one extra element. If this extra element \\(q\\) is in the largest subinterval, then this subinterval must shrink in \\(Q\\) making \\(\|Q\| < \|P\|\\). Otherwise, the largest subinterval does not change so \\(\|Q\| = \|P\|\\). Therefore, \\(\|Q\| \leq \|P\|\\).

### Exercise 5.4

**(a)**

For any \\(x \in \mathcal{I}(\mathbb{F})\\), we know that for every \\(n\\) that \\(|x| < 1/n\\). Since \\(1/n \leq 1\\), this means \\(|x| < 1\\) by transitivity. Therefore, \\(x\\) must also be in \\(\mathcal{F}(\mathbb{F})\\) so \\(\mathcal{I}(\mathbb{F}) \subseteq \mathcal{F}(\mathbb{F})\\).

**(b)**

Suppose for the sake of counterargument that there exists \\(x \in \mathbb{F}\\) that is not in \\(\mathcal{F}(\mathbb{F}) \cup \mathcal{L}(\mathbb{F})\\). This \\(x\\) could not satisfy either requirements of the sets. That is, \\(|x|\\) must be greater or equal to than any \\(n \in \mathbb{N}\\). However, if \\(|x| = n\\) then \\(|x| < n + 1\\) so \\(|x| > n\\) for all \\(n \in \mathbb{N}\\). This is the exact requirement for \\(x\\) to be in \\(\mathcal{L}(\mathbb{F})\\).

**(c)**

If \\(x \in \mathcal{L}(\mathbb{F})\\), then by definition \\(|x| > n\\) for any \\(n \in \mathbb{N}\\). If this same \\(x\\) was in \\(\mathcal{F}(\mathbb{F})\\), then there would be a natural number that \\(|x|\\) was less than. However, this would contradict the requirement to be in \\(\mathcal{L}(\mathbb{F})\\). Therefore, \\(\mathcal{F}(\mathbb{F}) \cap \mathcal{L}(\mathbb{F}) = \emptyset\\).

### Exercise 5.5



### Exercise 5.6



### Exercise 5.7



### Exercise 5.8



### Exercise 5.9



### Exercise 5.10



### Exercise 5.11



### Exercise 5.12



### Exercise 5.13



### Exercise 5.14



### Exercise 5.15



### Exercise 5.16



### Exercise 5.17



### Exercise 5.18


