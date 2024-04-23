---
layout: default
title: Quadratic Fractional Equations
permalink: "/grade8/QuadraticFractionalEquations"
parent: Unit 3
grand_parent: Grade 8 Higher
nav_order: 5
---

### Example 1

**Problem:**

Solve the equation:

$$ \frac{4}{p} - \frac{5}{p+3} = \frac{p+8}{(p+3)^2} $$

**Solution:**

$$
\begin{align}
4(p+3)^2 - 5p(p+3) &= (p+8)p \\
4(p^2 + 6p + 9) - 5p^2 - 15p &= p^2 + 8p \\
-p^2 + 9p + 36 &= p^2 + 8p \\
2p^2 + 8p - p^2 - 9p - 36 &= 0 \\
2p^2 - p - 36 &= 0 \\
(2p-9)(p+4) &= 0 \\
2p - 9 = 0 \quad &\text{or} \quad p + 4 = 0 \\
p = 4.5 \quad &\text{or} \quad p = -4 \\
\end{align}
$$

Therefore, the solutions are $$ p = 4.5 $$ and $$ p = -4 $$.

**Criteria C Question: Why does multiplying both side by $$ (p)(p+3)^2 $$ clear the fractions**

The equation involves fractions with denominators $$ p $$ and $$ p + 3 $$. The least common denominator (LCD) for these fractions is $$ p(p+3)^2 $$. Multiplying the entire equation by this LCD clears the fractions because each term is multiplied by the LCD, resulting in the denominators being canceled out. Here's why:

The first term $$ \frac{4}{p} $$ is multiplied by $$ p(p+3)^2 $$, which cancels the $$ p $$ in the denominator:

$$ \frac{4}{p} \times p(p+3)^2 = 4(p+3)^2 $$

The second term $$ \frac{5}{p+3} $$ is multiplied by $$ p(p+3)^2 $$, which cancels the $$ p+3 $$ in the denominator:

$$ \frac{5}{p+3} \times p(p+3)^2 = 5p(p+3) $$

The right side of the equation $$ \frac{p+8}{(p+3)^2} $$ is multiplied by $$ p(p+3)^2 $$, which cancels the $$ (p+3)^2 $$ in the denominator:

$$ \frac{p+8}{(p+3)^2} \times p(p+3)^2 = (p+8)p $$

By doing this, all the denominators are eliminated, resulting in an equation with no fractions, which is often  the denominators are eliminated, resulting in an equation with no fractions, which is often easier to solve.


### Example 2

**Problem:**

Solve the equation:

$$ \frac{1}{4x^2 - 4x + 1} + \frac{3}{2x - 1} = 4 $$

**Solution:**

First, notice that $$ 4x^2 - 4x + 1 $$ is a perfect square trinomial:

$$ \frac{1}{(2x - 1)^2} + \frac{3}{2x - 1} = 4 $$

Multiply through by $$ (2x - 1)^2 $$ to clear the fractions:

$$ 1 + 3(2x - 1) = 4(2x - 1)^2 $$

Expand and simplify:

$$ 1 + 6x - 3 = 16x^2 - 16x + 4 $$

Combine like terms and move everything to one side:

$$ 0 = 16x^2 - 16x + 4 - 6x + 2 $$

$$ 16x^2 - 22x + 6 = 0 $$

Divide through by 2 to simplify:

$$ 8x^2 - 11x + 3 = 0 $$

Factor the quadratic equation:

$$ (8x - 3)(x - 1) = 0 $$

Set each factor equal to zero and solve for $$ x $$:

$$ 8x - 3 = 0 \quad \text{or} \quad x - 1 = 0 $$

$$ x = \frac{3}{8} \quad \text{or} \quad x = 1 $$

Therefore, the solutions are $$ x = \frac{3}{8} $$ and $$ x = 1 $$.

**Criteria C Question: Why do we factorise before clearing the fractions**

If we were to clear the fractions without factorising, we'd have to multiply by the least common denominator $$ (4x^2 - 4x + 1)(2x - 1) $$, which is more complex and could lead to more complicated algebra than necessary. Recognizing the square trinomial simplifies this to just $$ (2x - 1)^2 $$, making the algebra more manageable.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI5NDcxNTkxMl19
-->