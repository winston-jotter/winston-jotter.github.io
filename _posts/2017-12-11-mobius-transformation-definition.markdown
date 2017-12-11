---
layout: post
title:  "Möbius transformation definition"
date:   2017-12-11 22:46:36 +0100
mathjax: true
categories: jekyll update
---
Given a complex number $z \in \mathbb{C}$, there are several elementary maps that can be considered:

- $z \to cz$, $c \in \mathbb{R}$: scaling;
- $z \to z + A$, $A \in \mathbb{C}$: translation;
- $z \to Az, A = e^{i \theta}$: rotation;
- $z \to \bar{z}$: complex conjugation;
- $z \to \displaystyle \frac{1}{z}$: inversion.

A Möbius transformation is the following non-elementary map:

$$f(z) = \displaystyle \frac{az + b}{cz + d}$$

with $a,b,c,d \in \mathbb{C}$ and $ad - bc \neq 0$. It is immediately possible to recognize in $f(z)$ some of the elementary transformations above listed: scaling and/or rotation, translation, inversion.
