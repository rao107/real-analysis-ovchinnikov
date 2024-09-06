# Chapter 4: Differentiation

### Exercise 4.1

Since \\(\lim_{x \to c} f(x) = L\\), we know that for all \\(\varepsilon > 0\\), there exists \\(\delta > 0\\) such that for all \\(x \in U_\delta(c)\\), \\(L - \varepsilon < f(x) < L + \varepsilon\\).

Multiplying by \\(k > 0\\), we get \\(kL - k\varepsilon < k \cdot f(x) < kL + k\varepsilon\\). For \\(\varepsilon' = k\varepsilon > 0\\), we know there exists \\(\delta > 0\\) where all \\(x \in U_\delta(c)\\) satisfies \\(kL - \varepsilon' < k \cdot f(x) < kL + \varepsilon'\\). Therefore, \\(kf\\) converges to \\(kL\\) as \\(x\\) approaches \\(c\\) for \\(k > 0\\). If \\(k < 0\\), then changing \\(\varepsilon'\\) to \\(-k\varepsilon\\) maintains the same inequality. When \\(k = 0\\), it is trivial to show the same inequality is true. Therefore, \\(kf\\) converges to \\(kL\\) as \\(x\\) approaches \\(c\\).

### Exercise 4.2

We know that for all \\(\varepsilon > 0\\), there exists \\(\delta > 0\\) such that for any \\(x \in U_\delta(c)\\), \\(-\varepsilon < |f(x)| < \varepsilon\\). If \\(f(x) > 0\\), then \\(-\varepsilon < f(x) < \varepsilon\\). Otherwise, \\(-\varepsilon < -f(x) < \varepsilon\\) which means \\(\varepsilon > f(x) > -\varepsilon\\). Therefore, \\(-\varepsilon < f(x) < \varepsilon\\) so \\(\lim_{x \to c} f(x) = 0\\).

### Exercise 4.3

If \\(\lim_{x \to c} f(x) = L\\), then for any \\(\varepsilon > 0\\) there exists \\(\delta > 0\\) such that for all \\(x \in U_\delta(c)\\), \\(L - \varepsilon < f(x) < L + \varepsilon\\). The same holds for \\(\lim_{x \to 0} f(x + c) = L\\) except for all \\(x \in U_\delta(0)\\), \\(L - \varepsilon < f(x + c) < L + \varepsilon\\). We can write any \\(x \in U_\delta(c)\\) as a \\(x' \in U_\delta(0)\\) plus \\(c\\). We can also go the other way for any \\(x \in U_\delta(0)\\) written as a \\(x' \in U_\delta(c)\\) minus \\(c\\). Therefore, the two claims are equivalent.

### Exercise 4.4

For any limit point, we know that 

### Exercise 4.5

If an ordered field is countably cofinal,

If an ordered field contains a convergent sequence which is not eventually constant,

### Exercise 4.6



### Exercise 4.7

**(a)**

We can show that \\((x^n)' = nx^{n-1}\\) for \\(n > 0\\) using induction. When \\(n = 1\\), we need to prove that \\((x)' = 1\\). This is simple since \\(\lim_{t \to x} \frac{t - x}{t - x} = 1\\). Now we assume \\((x^n)' = nx^{n-1}\\) and must show that \\((x^{n+1})' = (n+1)x^n\\). We can do this by following the following equalities \\((x^{n+1})' = (x \cdot x^n)' = (x)' \cdot x^n + x \cdot (x^n)' = x^n + x \cdot nx^{n-1} = (n+1)x^n\\). Therefore, \\((x^n)' = nx^{n-1}\\) for \\(n > 0\\).

**(b)**



**(c)**

### Exercise 4.8

\\[ 
  \begin{align}
    \frac{d}{dx} \sqrt{x + \sqrt{x + \sqrt{x}}} &= \frac{1}{2}\left(x + \sqrt{x + \sqrt{x}}\right)^{-1/2}\left(\frac{d}{dx}\left(x + \sqrt{x + \sqrt{x}}\right)\right) \\\\
    &= \frac{1}{2}\left(x + \sqrt{x + \sqrt{x}}\right)^{-1/2}\left(1 + \frac{1}{2}(x + \sqrt{x})^{-1/2}\right)\left(\frac{d}{dx}\left(x + \sqrt{x}\right)\right) \\\\
    &= \frac{1}{2}\left(x + \sqrt{x + \sqrt{x}}\right)^{-1/2}\left(1 + \frac{1}{2}(x + \sqrt{x})^{-1/2}\right)\left(1 + \frac{1}{2}x^{-1/2}\right) \\\\
  \end{align}
\\]

### Exercise 4.9

False, consider \\(f(x) = |x|\\) and \\(g(x) = -|x|\\). Both functions are not differentiable at \\(x = 0\\). However, \\(f(x) + g(x) = |x| - |x| = 0\\) is differentiable at \\(x = 0\\).

### Exercise 4.10

If \\(f(x) = g(x) + C\\), then the derivative of \\(f\\) is \\(g'(x) + 0 = g'(x)\\). Therefore, \\(f'(x) = g'(x)\\).

If \\(f'(x) = g'(x)\\), then \\(f'(x) - g'(x) = 0\\). Since the derivative of \\(f(x) - g(x)\\) is \\(0\\), then \\(f(x) - g(x) = C\\) for some constant \\(C\\) since the field of real numbers is complete and satisfies the Zero Derivative Property. Therefore, \\(f(x) = g(x) + C\\).

### Exercise 4.11



### Exercise 4.12

Since the real numbers is a complete ordered field, we can prove that the derivative of \\((1 + x)^{r} - rx - 1\\) is greater than or equal to 0 for all \\(x \geq -1\\).

### Exercise 4.13



### Exercise 4.14

Since \\(x_1 < x_2\\), there exists \\(c\\) such that \\(x_2 = x_1 + c\\). Moreover, since \\(x \in [x_1, x_2]\\), there exists \\(x = x_1 + d\\).

Suppose for the sake of contradiction that there exist \\(\lambda, \lambda' \in [0, 1]\\) such that \\(x = \lambda x_1 + (1 - \lambda) x_2\\) and \\(x = \lambda' x_1 + (1 - \lambda') x_2\\). Rewriting \\(x\\) and \\(x_2\\) above and simpifying gives us \\(d = x_1 + (1 - \lambda) c\\) and \\(d = x_1 + (1 - \lambda') c\\). These two equations show us that \\(\lambda = \lambda'\\).

### Exercise 4.15



### Exercise 4.16

First, we show that \\(\min\\{x_1, \dotsc, x_n\\} \leq x\\). Since \\(x = \lambda_1 x_1 + \dotsb + \lambda_n x_n\\), we can rewrite \\(x\\) so the inequality is \\(\min\\{x_1, \dotsc, x_n\\} \leq \lambda_1 x_1 + \dotsb + \lambda_n x_n\\). Let the minimum of \\(x_1, \dotsc, x_n\\) be \\(c\\). Since \\(c \leq x_k\\) for all \\(1 \leq k \leq n\\), we can write \\(d_k = x_k - c > 0\\). Substituting \\(x_k\\) in the original inequality shows us \\(c \leq \lambda_1 (c + d_1) + \dotsb + \lambda_n (c + d_n)\\) which means \\(c \leq (\lambda_1 + \dotsb + \lambda_n) c + (\lambda_1 d_1 + \dotsb + \lambda_n d_n)\\). Since \\(\lambda_1 + \dotsb + \lambda_n = 1\\), \\(c \leq c + \lambda_1 d_1 + \dotsb + \lambda_n d_n\\) and so this inequality is true.

The argument to show that \\(x \leq \max\\{x_1, \dotsc, x_n\\}\\) follows a similar structure. We let \\(c\\) be the maximum of \\(x_1, \dotsc, x_n\\) and since \\(x_k \leq c\\) for all \\(1 \leq k \leq n\\), we can write \\(d_k = c - x_k > 0\\). This gives us \\(\lambda_1 (c - d_1) + \dotsb + \lambda_n (c - d_n) \leq c\\) so \\((\lambda_1 + \dotsb + \lambda_n) c - (\lambda_1 d_1 + \dotsb + \lambda_n d_n) \leq c\\) and so \\(c - (\lambda_1 d_1 + \dotsb + \lambda_n d_n) \leq c\\). Therefore, this inequality is true as well.

### Exercise 4.17

Assume \\(f\\) is convex.

Assume...

### Exercise 4.18

To show the power function is a convex function over the interval \\((a, b)\\) where \\(a \geq 0\\), we can show that its second derivative is always greater than or equal to 0. If \\(f(x) = x^p\\), then \\(f''(x) = p(p - 1) \cdot x^{p - 2}\\). Since \\(p \geq 1\\), \\(p(p - 1) \geq 0\\). Moreover, \\(x^{p - 2} > 0\\) for all \\(x \in (a, b)\\) and the following proves this inequality. Since \\(p - 2\\) is a rational number, we can write \\(p - 2 = a/b\\) and so \\(\sqrt[b]{x^a}\\). Since \\(x > 0\\), \\(x^a > 0\\) and taking the \\(b\\)-th root of a positive number will also be positive so \\(x^{p - 2} > 0\\). Since \\(p(p - 1) \geq 0\\) and \\(x^{p - 2} > 0\\), this means \\(p(p - 1) x^{p - 2} \geq 0\\) and so the power function is convex.

### Exercise 4.19


