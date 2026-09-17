---
title: "Math Problem 25"
date: 2026-09-17 12:00:00 +1000
categories: [math]
tags: [math]     # TAG names should always be lowercase
math: true
description: I lied 
toc: false
---

I said I wasnt gonna use latex anymore but I lied ok 


### Question
Let $f(x) = 2^x + 2^{2-x}$. Denote the graph of $y = f(x)$ by $\Gamma$. 

(a) Find $\displaystyle\int f(x)\,dx$. 

(b) Let $A$ be the area bounded by $\Gamma$, the $x$-axis and the stright lines $L_1: x =1$ and $L_2: x =3$.

(i) Find the exact value of $A$.

(ii) Other than $L_2$, there exsits another vertical line $L$ such that the area of region bounded by $\Gamma$, the $x$-axis, $L_1$ and $L$ is also $A$. Find the equation of $L$. 



---
### Worked solutions

(a) $\displaystyle \int f(x)\,dx = \frac{2^x}{\ln2} + \frac{2^{2-x}}{-\ln2}+C$

$=\displaystyle \frac{2^x}{\ln2} - \frac{4(2^{-x})}{\ln2} + C$

$$\space$$

(b) $\displaystyle A = \int_{1}^{3}f(x)\,dx$

$\displaystyle = \frac{1}{\ln2} \biggl[2^x-4(2^{-x}) \biggr]_1^3$

$=\displaystyle \frac{15}{2\ln2}$

$$\space$$

(c) Let $L: x =a$.

Case 1: $a$ is non-negative.

$\displaystyle \int_{1}^{a} f(x)\,dx = \frac{15}{2\ln2}$ 

$\displaystyle 2^a-4(2^{-a})=\frac{15}{2}$


$\displaystyle (2^a)^2-\frac{15}{2}2^a-4 =0$

$\displaystyle 2^a = \frac{-1}{2}$ (rejected) or $\displaystyle 2^a = 8$

$a =3$ (also rejected, since this is $L_2$)

$$\space$$

Case 2: $a$ is non-positive. 

$\displaystyle \int_{a}^{1} f(x)\,dx = \frac{15}{2\ln2}$ 

$\displaystyle -2^a+4(2^{-a})=\frac{15}{2}$

$\displaystyle -(2^a)^2-\frac{15}{2}2^a+4 =0$

$\displaystyle 2^a = \frac{1}{2}$ or $\displaystyle 2^a = -8$ (rejected)

$a=-1$.


---







