---
layout: default
title: Quadratic Exponential Equations
permalink: "/grade8/QuadraticExponentialEquations"
parent: Unit 3
grand_parent: Grade 8 Higher
nav_order: 7
---

# Lecture Note: Solving Quadratic Exponential Equations

## Objective
To understand and solve quadratic exponential equations using suitable substitutions and factoring.

---

## Example 1
**Question:** Solve the equation $$ 2(9^{x-1}) - 5(3^x) = 27 $$.

### Solution:

1. Write the equation:
   $$ 2(9^{x-1}) - 5(3^x) = 27 $$

2. Simplify the base:
   $$ 2\left(\frac{3^{2x}}{9}\right) - 5(3^x) = 27 $$

3. Recognize that $$ 9 = 3^2 $$ and simplify:
   $$ \frac{2}{9}(3^x)^2 - 5(3^x) = 27 $$

4. Let $$ a = 3^x $$:
   $$ \frac{2}{9}a^2 - 5a = 27 $$

5. Multiply through by 9 to clear the fraction:
   $$ 2a^2 - 45a = 243 $$

6. Rearrange into a quadratic equation:
   $$ 2a^2 - 45a - 243 = 0 $$

7. Factor the quadratic equation:
   $$ (2a + 9)(a - 27) = 0 $$

8. Solve for $$ a $$:
   $$ 2a + 9 = 0 \quad \text{or} \quad a - 27 = 0 $$

   $$ a = -\frac{9}{2} \quad \quad \quad a = 27 $$

9. Solve for $$ x $$ using $$ a = 3^x $$:
   $$ 3^x = 27 $$

   $$ 3^x = 3^3 $$

   $$ x = 3 $$

**Conclusion:** Since $$ 3^x > 0 $$, $$ x = 3 $$.

---

## Example 2
**Question:** By using a suitable substitution, solve the equation $$ 2^{3+2x} + 2^{5+x} = 2^x + 4 $$.

### Solution:

1. Write the equation:
   $$ 2^{3+2x} + 2^{5+x} = 2^x + 4 $$

2. Express each term with the same base where possible:
   $$ 2^3 \cdot (2^x)^2 + 2^5 \cdot 2^x = 2^x + 4 $$

3. Simplify the coefficients:
   $$ 8(2^x)^2 + 32(2^x) = 2^x + 4 $$

4. Let $$ y = 2^x $$:
   $$ 8y^2 + 32y = y + 4 $$

5. Rearrange into a quadratic equation:
   $$ 8y^2 + 31y - 4 = 0 $$

6. Factor the quadratic equation:
   $$ (8y - 1)(y + 4) = 0 $$

7. Solve for $$ y $$:
   $$ 8y - 1 = 0 \quad \text{or} \quad y + 4 = 0 $$

   $$ y = \frac{1}{8} \quad \quad \quad \text{(No Solution for } y = -4 \text{)} $$

8. Solve for $$ x $$ using $$ y = 2^x $$:
   $$ 2^x = \frac{1}{8} $$

   $$ 2^x = 2^{-3} $$

   $$ x = -3 $$

**Conclusion:** The solution for $$ x $$ is $$ x = -3 $$, since $$ 2^x $$ cannot be negative.

---

## Practice Questions with Full Solutions

### Questions with Answers

**Question 1:**  
Use an appropriate substitution, or otherwise, solve $$ 7^{2x+1} + 20(7^x) = 3 $$.  
_Answer:_ $$ x = -1 $$

**Question 2:**  
By using the substitution $$ u = 3^x $$, find the values of x such that $$ 3^{2x} - 3^{x+2} = 3^x - 9 $$.  
_Answer:_ $$ x = 0 $$ or $$ x = 2 $$

**Question 3:**  
Solve the equation $$ 5^{x+1} = 8 + 4(5^{-x}) $$.  
_Answer:_ $$ x = 0.431 $$

**Question 4:**  
Solve $$ 2^{x+1} - 24\sqrt{2^x} + 64 = 0 $$.  
_Answer:_ $$ x = 4 $$ or $$ x = 6 $$

**Question 5:**  
Solve the equation $$ \sqrt[3]{27 \cdot 27^{2x+3}} = \frac{1}{3^{x-2} \cdot 9^{3x}} $$.  
_Answer:_ $$ x = -\frac{1}{4} $$

**Question 6:**  
Solve the equation $$ \frac{3^{2(x+1)}}{9^{x+2}} = \frac{27^x}{3} $$.  
_Answer:_ $$ x = -\frac{1}{3} $$

**Question 7:**  
Solve the equation $$ 4^{3x-2} = \left(\frac{1}{8}\right)^{x-1} $$.  
_Answer:_ $$ x = \frac{7}{9} $$

---

### Solutions

**Solution to Question 1:**

$$ 7^{2x+1} + 20(7^x) = 3 $$,

$$ 7^{2x} \cdot 7^1 + 20(7^x) - 3 = 0 $$,

$$ 7(7^x)^2 + 20(7^x) - 3 = 0 $$,

Let $$ u = 7^x. $$

$$ 7u^2 + 20u - 3 = 0 $$,

$$ (7u - 1)(u + 3) = 0 $$,

$$ u = \frac{1}{7} $$ or $$ u = -3 $$ (no solution, reject)

$$ 7^x = 7^{-1} $$,

$$ x = -1 $$,

**Solution to Question 2:**

$$ 3^{2x} - 3^{x+2} = 3^x - 9 $$,

$$ (3^x)^2 - 3^2 \cdot 3^x = 3^x - 9 $$,

$$ (3^x)^2 - 9(3^x) = 3^x - 9 $$,

Let $$ u = 3^x. $$

$$ u^2 - 9u = u - 9 $$,

$$ u^2 - 10u + 9 = 0 $$,

$$ (u - 9)(u - 1) = 0 $$,

$$ u = 9 $$ or $$ u = 1 $$

$$ 3^x = 3^2 $$ or $$ 3^x = 3^0 $$

$$ x = 2 $$ or $$ x = 0 $$

Hence, $$ x = 0 $$ or $$ x = 2 $$.

**Solution to Question 3:**

$$ 5^{x+1} = 8 + 4(5^{-x}) $$,

$$ 5(5^x) = 8 + 4(5^x)^{-1} $$,

Let $$ u = 5^x. $$

$$ 5u = 8 + \frac{4}{u} $$,

$$ 5u^2 = 8u + 4 $$,

$$ (5u + 2)(u - 2) = 0 $$,

$$ u = \frac{-2}{5} $$ (rejected) or $$ u = 2 $$

$$ 5^x = 2 $$,

$$ x \approx 0.431 $$,

**Solution to Question 4:**

$$ 2^{x+1} - 24\sqrt{2^x} + 64 = 0 $$,

$$ 2 \cdot (2^{\frac{x}{2}})^2 - 24 \cdot 2^{\frac{x}{2}} + 64 = 0 $$,

$$ (2^{\frac{x}{2}})^2 - 12 \cdot 2^{\frac{x}{2}} + 32 = 0 $$,

Let $$ y = 2^{\frac{x}{2}}. $$

$$ y^2 - 12y + 32 = 0 $$,

$$ (y - 4)(y - 8) = 0 $$,

$$ y = 4 $$ or $$ y = 8 $$

$$ 2^{\frac{x}{2}} = 4 $$ or $$ 2^{\frac{x}{2}} = 8 $$,

$$ \frac{x}{2} = 2 $$ or $$ \frac{x}{2} = 3 $$,

Hence, $$ x = 4 $$ or $$ x = 6 $$.

**Solution to Question 5:**

$$ \sqrt[3]{27 \cdot 27^{2x+3}} = \frac{1}{3^{x-2} \cdot 9^{3x}} $$,

$$ (3^3)^{2x+3 \cdot \frac{1}{3}} = \frac{1}{3^{x-2} \cdot (3^2)^{3x}} $$,

$$ 3^{\frac{6x+9}{2}} = \frac{1}{3^{x-2} \cdot 3^{6x}} $$,

$$ \frac{3^{6x+9}}{3^2} = \frac{1}{3^{7x-2}} $$,

$$ 3^{\frac{6x+9}{2} + 7x - 2} = 3^0 $$,

$$ 20x + 5 = 0 $$,

$$ x = -\frac{1}{4} $$,

**Solution to Question 6:**

$$ \frac{3^{2(x+1)}}{9^{x+2}} = \frac{27^x}{3} $$,

$$ \frac{3^{2x+2}}{3^{2x+4}} = \frac{3^{3x}}{3} $$,

$$ 3^{2x+2 - 2x-4} = 3^{3x-1} $$,

$$ 3x - 1 = -2 $$,

$$ x = -\frac{1}{3} $$,

**Solution to Question 7:**

$$ 4^{3x-2} = \left(\frac{1}{8}\right)^{x-1} $$,

$$ 2^{2(3x-2)} = (2^3)^{-x+1} $$,

$$ 6x - 4 = -3x + 3 $$,

$$ x = \frac{7}{9} $$.
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjYwNzk4MzU5XX0=
-->