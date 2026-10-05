---
title: "Math Problem 29"
date: 2026-10-05 20:15:00 +1100
categories: [math]
tags: [math]     # TAG names should always be lowercase
math: true
description: Normal approximation to the Binomial 
---

This question actually is out-syll now. Learnt it in my stat uni class so I know how to do it now


### Question

A magazine publisher wants to estimate the proportion $p$ of its current subscribers who will continue to subscribe next year. It is given that the publisher randomly selects $841$ current subscribers, and $441$ of them will continue to subscribe. 

(a) Find an _approximate_ $95\%$ confidence interval for $p$. 

(b) An approximate $\beta\%$ confidence interval for $p$ is now constructed. The width of the confidence interval is $0.088$. Find $\beta$ correct to the nearest integer. 

(3 + 3 marks)


---


### Worked solution 

(a) approximate $95\%$ confidence interval 

$\displaystyle = \left(\frac{441}{841}-1.96\sqrt\frac{\frac{441}{841}\left(1-\frac{441}{841}\right)}{841}, \frac{441}{841}+1.96\sqrt\frac{\frac{441}{841}\left(1-\frac{441}{841}\right)}{841}\right)$ $\space\color{red}{\boxed{\text{1M+1A}}}$

$= \displaystyle \left(\frac{59829}{121945}, \frac{68061}{121945}\right)$ $\space\color{red}{\boxed{\text{1A}}}$

r.t. $(0.4906,0.5581)$

(b) $\displaystyle 2z\sqrt\frac{\frac{441}{841}\left(1-\frac{441}{841}\right)}{841} = 0.088$

$z \approx 2.55503895$ $\space\color{red}{\boxed{\text{1M}}}$

by looking at the normal dist. table

$\beta\% = (0.4946)(2)(100\%)$ $\space\color{red}{\boxed{\text{1M}}}$

$\beta = 99$ (corrected to nearest integer). $\space\color{red}{\boxed{\text{1A}}}$


