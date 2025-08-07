---
aliases: []
---


# 2 - Algebra
Algebra is a branch of mathematics that deals with finding an unknown quantity. It involves studying mathematical structures, relationships, and operations, and it uses letters and symbols to represent numbers and quantities in equations and formulas.

Algebra is extremely important for learning more advanced math (which in turn is used in science, engineering, and other fields that we will use to advance technology). As you advance into higher levels of math, you will undoubtedly use Algebra, so it is very important you understand the concepts of Algebra thoroughly.

With that said, you will need to read these textbooks (and in this order too):

1. [ ] [Prealgebra 2e](../../Media/Mathematics/Prealgebra%202e.pdf).
2. [ ] [College Algebra 2e](../../Media/Mathematics/College%20Algebra%202e.pdf).

Both books are licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Manual Computation Methods
The textbooks given assume that you have a calculator. However, we anticipate that you may not have a calculator! Thus, we provide you some methods to calculate square roots without a calculator.

#todo: computing square roots without a calculator

### Compute Square Roots Without a Calculator

A square root of a number is a value that, when multiplied by itself, gives the original number. For example, the square root of 9 is 3 because $3 \times 3 = 9$.

To compute the square root of a number, use the following formula:

$$\sqrt{s} \approx a + \frac{b}{2a}$$

where
- $s$ is the number you want to find the square root of.
- $a$ is the closest perfect square to $s$.
- $b=s-a^2$.

To do this step-by-step:
1. Identify $s$, the number you want to find the square root of.
2. Identify $a$, the closest perfect square root to $s$.
3. Calculate $b$, which is $s-a^2$.
4. Use the formula above to find the approximation. Let's call this result $r$.
5. If you want a more accurate approximation, repeat steps 1-4 on $r$. However, this time set $a=r$.

#### Example 1
Find the square root of $69$.

Firstly, we know that $69$ is the number we want to find the square root of. So, $s=69$.

Secondly, the closest perfect square root to $69$ is $64$, which equals $8^2$. So, $a=8$.

Thirdly, find $b$.

$$\begin{align*}
b &= s-a^{2} \\
&= 69-8^{2} \\
&= 69-64 \\
&= 5
\end{align*}$$

So, $b=5$.

Fourthly, use the formula above to find the approximation.

$$\begin{align*}
\sqrt{s} &\approx a + \frac{b}{2a} \\
\sqrt{69} &\approx 8 + \frac{5}{2(8)} \\
&\approx 8 + \frac{5}{16} \\
&\approx 8.3125
\end{align*}$$

The actual value of $\sqrt{69}$ is approximately $8.306629$. So, the above approximation is very close to the actual value.

If you would like a more accurate approximation, repeat steps 1-4 on the value $8.3125$. This time, however, $a=8.3125$.

$$\begin{align*}
\sqrt{s} &\approx a + \frac{b}{2a} \\
\sqrt{69} &\approx a + \frac{s-a^{2}}{2a} \\
&\approx 8.3125 + \frac{69-(8.3125)^{2}}{2(8.3125)} \\
&\approx 8.3125 + \frac{69-69.0977}{16.625} \\
&\approx 8.3125 + \frac{-0.0977}{16.625} \\
&\approx 8.3125 - 0.0059 \\
&\approx 8.3066
\end{align*}$$

As you can see, the above steps give a better approximation of $\sqrt{69}$.

## Next Steps
Once you have completed algebra, please move on to [3 - Geometry](3%20-%20Geometry.md).