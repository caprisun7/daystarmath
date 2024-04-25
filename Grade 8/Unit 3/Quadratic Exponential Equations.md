---
layout: default
title: Quadratic Exponential Equations
permalink: "/grade8/QuadraticExponentialEquations"
parent: Unit 3
grand_parent: Grade 8 Higher
nav_order: 3
---

# Solving Quadratic Exponential Equations

## Example 1
**Problem**
Solve the equation $$2(9^{x-1}) - 5(3^{x}) = 27$$.

**Solution**
$$
\begin{align*}
2(9^{x-1}) - 5(3^{x}) &= 27 \\
2\left(\frac{9^x}{9}\right) -5(3^{x}) &= 27 \\
\frac{2}{9}(3^{x})^2 -5(3^{x}) &= 27
\end{align*}
$$
Let $a = 3^{x}$.

$$
\begin{align*}
\frac{2}{9}a^2 - 5a &= 27 \\
2a^2 - 45a &= 243 \\
2a^2 - 45a - 243 &= 0 \\
(2a+9)(a-27) &= 0
\end{align*}
$$

$$
\begin{align*}
2a+9 &= 0 & \text{or} & & a-27 &= 0 \\
2a &= -9 & & & a &= 27 \\
a &= -\frac{9}{2} & & & 3^{x} &= 27 \\
3^{x} &= -\frac{9}{2} & & & 3^{x} &= 3^3 \\
& & & & x &= 3
\end{align*}
$$

Since $3^{x} > 0$, $x = 3$.


## Practice 1.1
**Problem**
Solve the equation $$9^{x} - 10(3^{x}) + 1 = 0$$.

**Answer**
$$x=-2 \text{ or } 0$$

## Practice 1.2
**Problem**
Use an appropriate substitution, or otherwise, solve 
$$ 7^{2x+1} + 20(7^x) = 3 $$.
**Answer**  
$$ x = -1 $$



## Example 2
**Problem:** By using a suitable substitution, solve the equation $$ 2^{3+2x} + 2^{5+x} = 2^x + 4 $$.

**Solution**
$$
\begin{align*}
2^3 \cdot (2^x)^2 + 2^5 \cdot 2^x &= 2^x + 4 \\
8(2^x)^2 + 32(2^x) &= 2^x + 4 \\
8y^2 + 32y &= y + 4 \\
8y^2 + 31y - 4 &= 0 \\
(8y - 1)(y + 4) &= 0 \\
8y - 1 = 0 \quad \text{or} \quad& y + 4 = 0\\
y = \frac{1}{8} \quad \text{or} \quad& y = -4\\
2^x=\frac{1}{8}\\
x=-3
\end{align*}
$$

## Practice 2.1
**Problem**
Find the values of x such that $$ 3^{2x} - 3^{x+2} = 3^x - 9 $$.  
**Answer** 
$$ x = 0 \text{ or }x = 2 $$

## Example 3
**Problem**
Solve $$5^{x+1}=26-5^{1-x}$$
**Solution**
$$
\begin{align*}
5\cdot5^x&=26-5\cdot5^{-x}\\
5\cdot5^x&=26-5\cdot\frac{1}{5^x}\\
5y&=26-5\cdot\frac{1}{y}\\
0&=5y^2-26y+5 \\
0&=(5y-1)(y-5)\\
y&=\frac{1}{5} \text{ or } y=5\\
x&=-1 \text{ or } x=1
\end{align*}
$$

## Practice 3.1
**Problem**
Solve
$$
2^{x+3}+2^{-x}=9
$$

**Answer**
$$-3 \text{ or } 0$$

## Example 4
**Problem**  
Solve $$ 2^{x+1} - 24\sqrt{2^x} + 64 = 0 $$.  
**Solution** 
$$
\begin{align*}
2\cdot2^x-24\sqrt{2^x}+64&=0\\
2y^2-24y+64&=0\\
y^2-12y+32&=0\\
(y-4)(y-8)&=0\\
\end{align*}
$$

$$
\begin{align*}
y=4 &\text{ or } y=8\\
2^x=16 &\text{ or } 2^x=64\\
x=4 &\text{ or } x=6\\
\end{align*}
$$ 

## Practice 4.1
**Problem**
Find the value of $3^x$ if
$$
3^x - \left(\sqrt{3}\right)^{x+4} + 20 = 0
$$
**Answer**
$$16 \text{ or } 25$$

## Example 5
**Problem**
Given that $y = 3^x$, express $$3^{2x} + 81^{\frac{1}{4}(x+2)}-9^{\frac{1}{2}(x+1)}$$ in term of y.

**Solution**
$$
\begin{align*}
&= (3^x)^2 + 3^{x+2} - 3^{x+1} \\
&= y^2 + 9y - 3y \\
&= y^2 + 6y
\end{align*}
$$

## Practice 5.1

**Problem**
Given that $u = 3^x$, express $9^{x-2}$ in terms of $u$.

**Answer**
$$\frac{u^2}{81}$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzM5MDcyMzc3LC04NDAyMzU4MjMsLTc2MT
QwNjI1NSwtNzk4NTA0MTIxLDE4MDk1ODM2NzksLTE1MjIxNDE4
MTMsMTAzMzc0MjA2MCwxNDEwOTU3NjE4LC0yNjgwNTIxMTQsMj
A2MDYzMzI2OV19
-->