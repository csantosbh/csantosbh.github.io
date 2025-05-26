---
title: ""
date: 2024-03-19
draft: false
tags: ["limits"]
---

# Chapter X - Inequalities
## Properties


# Chapter 1 - Limits

## Introduction
We say that $f(x)$ approaches $l$ as $x$ approaches $a$ if, for any given tolerance $\epsilon > 0$ (measuring how close $f(x)$ must be to $l$), there exists a corresponding distance $\delta > 0$ (measuring how close $x$ must be to $a$) such that whenever $x$ lies within $\delta$ of $a$ (but is not equal to $a$), the function value $f(x)$ lies within $\epsilon$ of $l$.

More precisely, for every $x$ in the punctured interval $(a-\delta, a+\delta) \setminus \{a\}$, we have $f(x) \in (l-\epsilon, l+\epsilon)$. This fundamental concept can be expressed formally as follows:

$$
\lim\limits_{x \to a}f(x)=l \iff (\forall \epsilon \enspace \exists \delta
\enspace \forall x: 0 < \left|x-a\right| < \delta \Rightarrow
\left|f(x)-l\right|<\epsilon)
$$

## Product rule

Let's expand the definition of limits for $\lim f(x)$ and $\lim g(x)$
individually, taking care to distinguish between their corresponding tolerance values:

$$
\begin{aligned}
\lim\limits_{x \to a}f(x)=l &\iff (\forall \epsilon' \enspace \exists \delta'
\enspace \forall x: 0 < \left|x-a\right| < \delta' \Rightarrow
\left|f(x)-l\right|<\epsilon') \\
\lim\limits_{x \to a}g(x)=m &\iff (\forall \epsilon'' \enspace \exists \delta''
\enspace \forall x: 0 < \left|x-a\right| < \delta'' \Rightarrow
\left|g(x)-m\right|<\epsilon'')
\end{aligned}
$$

We want to prove that $\lim\limits_{x \to a}f(x)g(x)=lm$, which means
$$
\lim\limits_{x \to a}f(x)g(x)=lm \iff (\forall \epsilon''' \enspace \exists \delta'''
\enspace \forall x: 0 < \left|x-a\right| < \delta''' \Rightarrow
\left|f(x)g(x)-lm\right|<\epsilon''').
$$

We know from TODO that $\left|a+b\right| \leq \left|a\right|+\left|b\right|$,
and $\left|a-b\right| \geq \left|a\right|-\left|b\right|$.

