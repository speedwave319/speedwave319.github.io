---
title: "Math Problem 24"
date: 2026-09-16 9:45:00 +1000
categories: [math]
tags: [math]     # TAG names should always be lowercase
math: true
description: It's been a while
toc: false
---



## Questions 

### Question 1 
Let $f(x) = x^2 \ln x$. Find $f'(x)$ from first principles. 

(4 marks)


---

###  Question 2
(a) Using mathematical induction, prove that $\displaystyle \sum_{k=1}^{n} \frac{1}{1+2+3+\dots+k} = \frac{2n}{n+1}$ for all positive integers $n$. 

(b) Using (a), evaulate 
$$\displaystyle \frac{1}{2+4+6+\dots+100}+\frac{1}{2+4+6+\dots+102}+\frac{1}{2+4+6+\dots+104}+\dots+\frac{1}{2+4+6+\dots+200}.$$

(4+2 marks)

---

### Question 3
(a) Prove that $\displaystyle 1- \cos2x+\cos4x-\cos6x = 4\sin x\cos2x\sin3x.$

(b) Solve the equation $\displaystyle 1- \cos2x+\cos4x-\cos6x = 4 \cos x \cos2x\cos3x$, for $\displaystyle x \in \biggl[0, \frac{\pi}{3}\biggr]$. 

(3+3 marks)


---
### Question 4 
(a) Let $a$ be a constant greater than $1$. Define $g(x) =\displaystyle \frac{x^2(a^x-a^{2x})}{1+a^{3x}}$ for all $x \in \mathbb{R}$. Is $g(x)$ an odd function? Explain your answer.

(b) Using the result of (a), evaluate $\displaystyle\int_{-2026}^{2026} \frac{2^{x+2}x^2-4^{x+1}x^2+8^x}{1+8^x}\, dx$. 

(3+3 marks)



---
##  Worked Solutions

### Question 1

$\displaystyle f'(x) = \lim_{h \to 0} \frac{(x+h)^2\ln(x+h)- x^2\ln x}{h}$ 

$\displaystyle = \lim_{h \to 0} \frac{ (x^2 + 2xh + h^2)\ln(x+h)- x^2\ln x}{h}$

$\displaystyle = \lim_{h \to 0} \frac{x^2(\ln(x+h)-\ln x)}{h}+\frac{(2xh+h^2)\ln(x+h)}{h}$

$\displaystyle = \lim_{h \to 0} \frac{x^2}{h}\ln{\biggr(1+\frac{h}{x}\biggr)}+ (2x+h)\ln(x+h)$

$\displaystyle = \lim_{h \to 0}  \space x\ln{\biggr(1+\frac{h}{x}\biggr)}^\frac{x}{h}+ \lim_{h \to 0} \space (2x+h)\ln(x+h)$

$\displaystyle = \lim_{t \to 0}  \space x\ln{(1+t)}^\frac{1}{t}+ \lim_{h \to 0} \space (2x+h)\ln(x+h)$  $\space$ (by letting $t = \frac{x}{h}$)

$\displaystyle = x\ln e + 2x\ln x$ 

$\displaystyle = x + 2x\ln x$ 



---

### Question 2 

(a) Let $P(n): \displaystyle \sum_{k=1}^{n} \frac{1}{1+2+3+\dots+k} = \frac{2n}{n+1}$ for all positive integers $n$. 

When $n =1$, LHS = $\displaystyle \frac{1}{1} = 1$ and RHS = $\displaystyle \frac{2(1)}{1+1} = 1$

LHS = RHS, therefore $P(1)$ is true.

Suppose $P(m)$ is true for some postitive integer $k$, 

i.e. $\displaystyle \sum_{k=1}^{m} \frac{1}{1+2+3+\dots+k} = \frac{2m}{m+1}$

When $n = m+1$,

LHS $\displaystyle =\sum_{k=1}^{m+1} \frac{1}{1+2+3+\dots+k}$

$\displaystyle =\sum_{k=1}^{m} \biggl[ \frac{1}{1+2+3+\dots+k} \biggl] + \frac{1}{1+2+3+\dots+m+1}$

$\displaystyle =  \frac{2m}{m+1} +\frac{1}{1+2+3+\dots+m+1}$

$\displaystyle =  \frac{2m}{m+1} +\frac{2}{(m+1)(m+2)}$


$\displaystyle = \frac{2m^2+4m+2}{(m+1)(m+2)}$

$\displaystyle = \frac{2(m+1)^2}{(m+1)(m+2)}$

$\displaystyle = \frac{2(m+1)}{m+2} = RHS$

Therefore, $P(m+1)$ is also true.

By the pricinple of mathematical induction, $P(n)$ is true for all positive integers $n$. 

$$\space$$

(b) The required value 

$\displaystyle = \frac{1}{2} \biggl[\frac{1}{1+2+3+\dots+50}+ \frac{1}{1+2+3+\dots+51} + \dots +\frac{1}{1+2+3+\dots+100} \biggr]$

$\displaystyle = \frac{1}{2} \biggl[\frac{2(100)}{100+1} - \frac{2(49)}{49+1}\biggr]$

$\displaystyle = \frac{51}{5050}$




---

### Question 3
(a) $\displaystyle LHS = 1- \cos2x+\cos4x-\cos6x$

$= 1+\cos4x- \cos2x-\cos6x$

$= 1-2\sin3x\sin x-\cos6x$

$= 1-2\sin3x\sin x - (1-2\sin^33x)$

$= -2\sin3x\sin x +2\sin^33x$

$= 2\sin3x(\sin3x- \sin x)$

$=4\sin x\cos2x\sin3x$

$$\space$$

(b) $$\displaystyle 1- \cos2x+\cos4x-\cos6x = 4 \cos x \cos2x\cos3x$$

$$\displaystyle 4\sin x\cos2x\sin3x = 4 \cos x \cos2x\cos3x$$

$$\displaystyle \sin3x \sin x - \cos3x \cos x = 0 $$

$$\displaystyle \cos4x = 0$$

$$\displaystyle 4x = \frac{\pi}{2}$$

$$\displaystyle x= \frac{\pi}{8}$$



---
### Question 4

(a) 

$\displaystyle g(-x) = \frac{(-x)^2 \left(a^{-x} - a^{-2x}\right)}{1 + a^{-3x}}$


$\displaystyle  = \frac{x^2 \left(a^{-x} - a^{-2x}\right)(a^{3x})}{(1 + a^{-3x})(a^{3x})}$


$\displaystyle = \frac{x^2 \left(a^{2x} - a^x\right)}{a^{3x} + 1}$

$\displaystyle =-\frac{x^2 \left(a^x - a^{2x}\right)}{1 + a^{3x}} = -g(x)$



Since $g(-x) = -g(x)$ for all $x \in \mathbb{R}$, $g(x)$ is an odd function.

$$\space$$


(b) $\displaystyle \int_{-2026}^{2026}\frac{4x^2 \cdot 2^x - 4x^2 \cdot 4^x + 8^x}{1 + 8^x}\, dx = \int_{-2026}^{2026}\frac{4x^2(2^x - 2^{2x})}{1 + 2^{3x}} + \frac{8^x}{1 + 8^x}\, dx$


$\displaystyle = 4 (0) + \int_{-2026}^{2026} \frac{8^x}{1 + 8^x} \, dx$

$\displaystyle =\frac{1}{\ln8} \int_{-2026}^{2026} \frac{1}{1+8^x}\, d(1+8^x)$

$\displaystyle = \frac{1}{\ln8}\biggl[\ln(1+8^x)\biggr]_{-2026}^{2026}$

$\displaystyle = \frac{1}{\ln8}\biggl[\ln(1+8^{2026})- \ln\biggl(\frac{1+8^{2026}}{8^{2026}}\biggr)\biggr]$

$\displaystyle = \frac{\ln8^{2026}}{\ln8}$

$= 2026$



---
#### Footnotes/ bs / notes / whatever you want to call this
* This took me way too long I aint doing this ever again 
* typing the worked solutions in latex genuinely is a nightmare 
* As you can see I've published multiple questions at once. Consider this as compensation for me not posting for so long. 
* The set of questions came from the same paper. 
* fml kms
* https://www.youtube.com/watch?v=dQw4w9WgXcQ


---









