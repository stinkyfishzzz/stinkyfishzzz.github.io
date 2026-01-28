---
layout: post
title: "A tiny-integer trick: irrationality of e"
---

We prove \(e\) is irrational via an integral that is both an integer and in \((0,1)\).

## Key idea
Construct \(I_n = \int_0^1 \frac{x^n(1-x)^n}{n!} e^x \, dx\).

Then show:
1. \(I_n = A_n e - B_n\) with \(A_n,B_n\in\mathbb{Z}\).
2. \(0 < I_n < 1/q\) for large \(n\).
So if \(e=p/q\), then \(qI_n\) is an integer in \((0,1)\), contradiction.
