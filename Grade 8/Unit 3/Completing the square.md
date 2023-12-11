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

## Why Add $$ \left(\frac{b}{2}\right)^2 $$?

The reason for adding $$ \left(\frac{b}{2}\right)^2 $$ to complete the square in expressions like $$ x^2 \pm bx $$ is based on the algebraic identity for squaring a binomial:

$$
(a + b)^2 = a^2 + 2ab + b^2
$$

### Understanding the Binomial Square Identity

1. **Square of the First Term**: $$ a^2 $$
2. **Twice the Product of the Two Terms**: $$ 2ab $$
3. **Square of the Second Term**: $$ b^2 $$

### Applying the Identity to Complete the Square

In the expressions $$ x^2 + bx $$ or $$ x^2 - bx $$, we have the first two parts of the binomial square identity:

- $$ x^2 $$ (the square of the first term)
- $$ \pm bx $$ (twice the product of the two terms, but we only have the first half, $$ bx $$)

To complete the square, we need to add the square of the second term in the binomial, which is missing.

## Example 3: Solving $$ x^2 + 8x - 5 = 0 $$

1. **Original Equation**: $$ x^2 + 8x - 5 = 0 $$
2. **Add and Subtract 16**: $$ x^2 + 8x + 16 - 16 $$
3. **Complete Square**: $$ (x + 4)^2 - 16 $$
4. **Solve for $$ x $$**:
   - $$ (x + 4)^2 = 21 $$
   - $$ x + 4 = \pm\sqrt{21} $$
   - $$ x = -4 \pm\sqrt{21} $$

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
