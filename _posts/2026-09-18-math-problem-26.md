---
title: "Math Problem 26"
date: 2026-09-16 20:00:00 +1000
categories: [math]
tags: [math]     # TAG names should always be lowercase
math: true
description: suddenly I got addicted
toc: false
---

I don't know why. maybe because she dumped me 

### Question

(a) Let $f(x)$ be a continous function for $x \in [0, a]$, where $a$ is a constant. Prove that 

$$\displaystyle \int_{0}^{a} f(x)\,dx = \int_{0}^{a} f(a-x)\,dx$$ 

Hence, prove that 

$$\displaystyle \int_{0}^{a} f(x)\,dx = \frac{1}{2}\int_{0}^{a} \Bigl[f(x) +f(a-x)\Bigr]\,dx$$

$$\space$$

(b) Evaluate $\displaystyle \int_{0}^{6} \frac{dx}{x^2-6x+18}$. 

(c) Using (a) and (b), or otherwise, evaluate $\displaystyle \int_{0}^{6} \frac{dx}{(x^2-6x+18)(e^{x-3}+1)}$. 

(3 + 3 + 5 marks)


---


### Worked solution 

(a) Let $u = a-x,$ then $-du = dx$.  $\space\boxed{\text{1M}}$

$\displaystyle \int_{0}^{a} f(a-x)\,dx = \int_{a}^{0} -f(u)\,du$

$\displaystyle = \int_{0}^{a} f(u)\,du$

$\displaystyle = \int_{0}^{a} f(x)\,dx$   $\space\boxed{\text{1}}$

$$\space$$

RHS  $\displaystyle = \frac{1}{2}\int_{0}^{a} \Bigl[f(x) +f(a-x)\Bigr]\,dx$

$\displaystyle = \frac{1}{2}\int_{0}^{a} f(x)\,dx + \frac{1}{2}\int_{0}^{a}f(a-x)\,dx$

$\displaystyle = \frac{1}{2}\int_{0}^{a} f(x)\,dx + \frac{1}{2}\int_{0}^{a}f(x)\,dx$

$\displaystyle = \int_{0}^{a} f(x)\,dx$ $\space\boxed{\text{1}}$

$$\space$$

(b) $x^2-6x+18 = (x-3)^2+9$

let $x-3 = 3\tan\theta$, then $dx= 3\sec^2\theta$. $\space\boxed{\text{1M}}$

$\displaystyle \int_{0}^{6} \frac{dx}{x^2-6x+18} = \int_{0}^{6} \frac{dx}{(x-3)^2+9}$

$=\displaystyle \int_{\frac{-\pi}{4}}^{\frac{\pi}{4}} \frac{3\sec^2\theta}{9\tan^2\theta+9}\,d\theta$

$=\displaystyle \int_{\frac{-\pi}{4}}^{\frac{\pi}{4}} \frac{1}{3}\, d\theta$ $\space\boxed{\text{1M}}$

$\displaystyle =\frac{1}{3}\,\Bigl[\theta\Bigr]_{\frac{-\pi}{4}}^{\frac{\pi}{4}}$

$\displaystyle = \frac{\pi}{6}$ $\space\boxed{\text{1A}}$

$$\space$$

(c)$\displaystyle \int_{0}^{6} \frac{dx}{(x^2-6x+18)(e^{x-3}+1)}$

$=\displaystyle \frac{1}{2}\int_{0}^{6} \frac{dx}{(x^2-6x+18)(e^{x-3}+1)}
+\frac{1}{2}\int_{0}^{6}
\frac{dx}{((6-x)^2-6(6-x)+18)(e^{3-x}+1)}$ $\space\boxed{\text{1M for using (a)}}$


$=\displaystyle \frac{1}{2}\int_{0}^{6} \frac{dx}{(x^2-6x+18)(e^{x-3}+1)}
+\frac{1}{2}\int_{0}^{6}
\frac{dx}{(x^2-6x+18)(e^{3-x}+1)}$

$=\displaystyle \frac{1}{2}\int_{0}^{6}
\frac{e^{3-x}+1+e^{x-3}+1}
{(x^2-6x+18)(e^{x-3}+1)(e^{3-x}+1)}\,dx$ $\space\boxed{\text{1M}}$

$=\displaystyle \frac{1}{2}\int_{0}^{6}
\frac{1}{x^2-6x+18}\,dx$ $\space\boxed{\text{1M}}$


$\displaystyle =\frac{1}{2} \Big(\frac{\pi}{6}\Big)$ $\space\boxed{\text{1M for using (b)}}$

$\displaystyle =\frac{\pi}{12}$ $\space\boxed{\text{1A}}$



---
