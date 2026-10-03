---
title: "Math Problem 29"
date: 2026-10-03 22:15:00 +1000
categories: [math]
tags: [math]     # TAG names should always be lowercase
math: true
description: I did not lock in and fix my life
---

### Question

Let $X$ and $Y$ be discrete random variables such that $Y = 10 - 2X$. It is given that $\operatorname{E}(X) = 1.5$ and $\operatorname{Var}(X) = 1.75$.

(a) Find $\operatorname{E}(Y)$ and $\operatorname{Var}(Y)$. 

(b) Is it possible that $X$ follows a binomial distribution? Show your working.

(c) Is it possible that $Y$ follows a Poisson distribution? Show your working.

(3 + 1 + 1 marks)


---


### Worked solution 

(a) $\operatorname{E}(Y) = 10 - 2(1.5) = 7$ $\space\color{red}{\boxed{\text{1A}}}$

$\operatorname{Var}(Y) = 2^2(1.75) = 7$ $\space\color{red}{\boxed{\text{1A}}}$

$\space\color{red}{\boxed{\text{1M for either } \operatorname{E}(a-bx) \text{ OR } \operatorname{Var}(a-bx)}}$

(b) Suppose $X \sim B(n,p)$. 

Therefore, we have $\displaystyle \begin{cases} np = 1.5\\ np(1-p) = 1.75\end{cases}$

$\displaystyle \implies \frac{1.5}{p}(p)(1-p) = 1.75$

$\displaystyle \implies 1-p = \frac{7}{6}$

$\displaystyle \implies p = \frac{-1}{6}$, which is impossible 

Thus, the claim is disagreed. $\space\color{red}{\boxed{\text{1 f.t.}}}$


(c) Note that $\operatorname{E}(Y)$ and $\operatorname{Var}(Y) = 7$. 

Therefore, $Y$ does follow a Poisson distribution. $\space\color{red}{\boxed{\text{1 f.t.}}}$
