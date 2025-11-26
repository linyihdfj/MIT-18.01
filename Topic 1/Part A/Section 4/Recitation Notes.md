Question:

For what values of $a$ and $b$ is the following function?

(1) continuous
(2) differentiable

$$
f(x) = \begin{cases}
x^2 + 1& x > 1\\
ax+b &x\le1
\end{cases}
$$

Solution:

(1):
Need $a$ and $b$ that satisfy at $x=1$, $y = 1 ^ 2 + 1 = 2$，so the answer is:

$$
2 = a + b
$$

(2):
**It equals to this equation:**(要求原函数在 $1$ 处连续且在 $1$ 的去心邻域可导，一般说明是否可导可以考虑导数的定义)

$$
\lim_{x \to 1^-} f'(x) = \lim_{x \to 1^+} f'(x)
$$

And we all know:

$$
\lim_{x \to 1^+}f'(x) = \lim_{x \to 1^+} 2x = 2
$$

And:

$$
\lim_{x \to 1^-}f'(x) = a
$$

If a function is differentiable, it must be continuous. So in this case, $a$ and $b$ must satisfy:

$$
2 = a + b
$$

Then, we can get the answer:

$$
\begin{cases}
a = 2 \\
b = 0
\end{cases}
$$
