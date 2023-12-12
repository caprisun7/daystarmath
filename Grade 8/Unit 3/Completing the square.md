---
layout: default
title: Completing the Sqaure
permalink: "/grade8/CompletingtheSquare"
parent: Unit 3
grand_parent: Grade 8 Higher
nav_order: 3
---

# Completing the Square: Concept and Examples

Completing the square is a technique used in algebra to transform an expression of the form $$ x^2 \pm bx $$ into a perfect square of the form $$ (x+a)^2 $$ or $$ (x-a)^2 $$. This method is particularly useful for solving quadratic equations.

## Example 1: Completing the Square for $$ x^2 + bx $$

1. **Expression**: $$ x^2 + bx $$
2. **Add**: $$ \left(\frac{b}{2}\right)^2 $$ to make it a perfect square.
3. **Resulting Expression**: $$ x^2 + bx + \left(\frac{b}{2}\right)^2 $$
4. **Rewrite as a Square**: $$ \left( x + \frac{b}{2} \right)^2 $$

### Worked Example

Let's say $$ b = 6 $$ in $$ x^2 + 6x $$.

1. **Expression**: $$ x^2 + 6x $$
2. **Add**: $$ \left(\frac{6}{2}\right)^2 = 9 $$
3. **Resulting Expression**: $$ x^2 + 6x + 9 $$
4. **Complete Square**: $$ (x + 3)^2 $$

### Self-explanation Exercise (Criteria C): Why Add $$ \left(\frac{6}{2}\right)^2 $$?

The reason for adding $$ \left(\frac{6}{2}\right)^2 $$ to complete the square is based on the formula:

$$
(x + a)^2 = x^2 + 2ax + a^2
$$

In the expressions $$ x^2 + 6x $$, we have the first two parts of $$ (x + a)^2 $$, namely $$ x^2 $$ and $$ 2ax $$ if $$ a = \frac{6}{2} $$:

To complete the square, we need to add $$ a^2 $$, which is $$ \left(\frac{6}{2}\right)^2 $$.

## Example 2: Completing the Square for $$ x^2 - bx $$

1. **Expression**: $$ x^2 - bx $$
2. **Add**: $$ \left(\frac{b}{2}\right)^2 $$ to make it a perfect square.
3. **Resulting Expression**: $$ x^2 - bx + \left(\frac{b}{2}\right)^2 $$
4. **Rewrite as a Square**: $$ \left( x - \frac{b}{2} \right)^2 $$

### Worked Example

Let's say $$ b = 4 $$ in $$ x^2 - 4x $$.

1. **Expression**: $$ x^2 - 4x $$
2. **Add**: $$ \left(\frac{4}{2}\right)^2 = 4 $$
3. **Resulting Expression**: $$ x^2 - 4x + 4 $$
4. **Complete Square**: $$ (x - 2)^2 $$

### Self-explanation Exercise (Criteria C): Why Add $$ \left(\frac{4}{2}\right)^2 $$?

The reason for adding $$ \left(\frac{4}{2}\right)^2 $$ to complete the square is based on the formula:

$$
(x - a)^2 = x^2 - 2ax + a^2
$$

In the expressions $$ x^2 - 4x $$, we have the first two parts of $$ (x - a)^2 $$, namely $$ x^2 $$ and $$ -2ax $$ if $$ a = \frac{4}{2} $$:

To complete the square, we need to add $$ a^2 $$, which is $$ \left(\frac{4}{2}\right)^2 $$.

## Example 3: Solving $$ x^2 + 8x - 5 = 0 $$

1. **Original Equation**: $$ x^2 + 8x - 5 = 0 $$
2. **Add and Subtract 16**: $$ x^2 + 8x + 16 - 16 - 5 = 0 $$
3. **Complete Square**: $$ (x + 4)^2 - 16 - 5 = 0 $$
4. **Solve for $$ x $$**:
   - $$ (x + 4)^2 = 21 $$
   - $$ x + 4 = \pm\sqrt{21} $$
   - $$ x = -4 \pm\sqrt{21} $$

### Self-explanation Exercise (Criteria C): In step 2, why did we add 16 and then minus 16?

To create a perfect square on the left side of the equation, we add and then subtract the square of half the coefficient of $$ x $$ in $$ x^2 + 8x $$. This is because the perfect square is $$ (x + a)^2 = x^2 + 2ax + a^2 $$, and here $$ a $$ is $$ 4 $$ since $$ 2a = 8 $$ leads to $$ a = 4 $$. Therefore, $$ a^2 = 16 $$. We add $$ 16 $$ to $$ x^2 + 8x $$ to complete the square and immediately subtract \(16\) to maintain the equality of the equation.

## Example 4: Solving $$ x^2 - 5x + 2 = 0 $$

1. **Original Equation**: $$ x^2 - 5x + 2 = 0 $$
2. **Add and Subtract $$ \frac{25}{4} $$**: $$ x^2 - 5x + \frac{25}{4} - \frac{25}{4} $$
3. **Complete Square**: $$ (x - \frac{5}{2})^2 - \frac{25}{4} $$
4. **Solve for $$ x $$**:
   - $$ (x - \frac{5}{2})^2 = \frac{17}{4} $$
   - $$ x - \frac{5}{2} = \pm\sqrt{\frac{17}{4}} $$
   - $$ x = \frac{5}{2} \pm\frac{\sqrt{17}}{2} $$

## Example 5: Solving $$ 2x^2 + 8x - 6 = 0 $$

1. **Original Equation**: $$ 2x^2 + 8x - 6 = 0 $$
2. **Divide by 2**: $$ x^2 + 4x - 3 = 0 $$
3. **Add and Subtract 4**: $$ x^2 + 4x + 4 - 4 $$
4. **Complete Square**: $$ (x + 2)^2 - 4 $$
5. **Solve for $$ x $$**:
   - $$ (x + 2)^2 = 7 $$
   - $$ x + 2 = \pm\sqrt{7} $$
   - $$ x = -2 \pm\sqrt{7} $$

### Self-explanation Exercise (Criteria C): why did we divide both side by 2 before completing the square?

To complete the square, it's necessary to use the formula $$ (x + a)^2 $$, which assumes a quadratic expression where the coefficient of $$ x^2 $$ is 1. In the given equation $$ 2x^2 + 8x - 6 = 0 $$, the coefficient of $$ x^2 $$ is 2, which does not fit the standard form needed to complete the square. To bring the equation into a form that allows us to apply the $$ (x + a)^2 $$ formula effectively, we first eliminate the coefficient of 2 by dividing the entire equation by 2. This simplification step is crucial for completing the square without introducing fractions or additional complexity.

## Example 6: Solving $$ 3x^2 - 9x = 6x - 18 $$

1. **Original Equation**: $$ 3x^2 - 9x = 6x - 18 $$
2. **Rearrange**: $$ 3x^2 - 15x + 18 = 0 $$
3. **Divide by 3**: $$ x^2 - 5x + 6 = 0 $$
4. **Add and Subtract $$ \frac{25}{4} $$**: $$ x^2 - 5x + \frac{25}{4} - \frac{25}{4} $$
5. **Complete Square**: $$ (x - \frac{5}{2})^2 - \frac{25}{4} $$
6. **Solve for $$ x $$**:
   - $$ (x - \frac{5}{2})^2 = \frac{1}{4} $$
   - $$ x - \frac{5}{2} = \pm\frac{1}{2} $$
   - $$ x = \frac{5}{2} \pm\frac{1}{2} $$
