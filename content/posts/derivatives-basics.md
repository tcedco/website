---
title: "Exploring Derivatives: The Foundation of Calculus"
date: 2024-10-05
description: "Installment 6 of Codects"
tags: ["Math", "Calculus", "Derivatives"]
categories: ["Codects"]
math: true
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.13.13/dist/katex.min.css" integrity="sha384-RZU/ijkSsFbcmivfdRBQDtwuwVqK7GMOw6IMvKyeWL2K5UAlyp6WonmB8m7Jd0Hn" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.13.13/dist/katex.min.js" integrity="sha384-pK1WpvzWVBQiP0/GjnvRxV4mOb0oxFuyRxJlk6vVw146n3egcN5C925NCP7a7BY8" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.13.13/dist/contrib/auto-render.min.js" integrity="sha384-vZTG03m+2yp6N6BNi5iM4rW4oIwk5DfcNdFfxkk9ZWpDriOkXX8voJBFrAO7MpVl" crossorigin="anonymous"
    onload="renderMathInElement(document.body);"></script>

**Derivatives** are one of the most fundamental concepts in calculus. At their core, they represent how a quantity changes with respect to another. Whether you’re studying physics, economics, or engineering, derivatives allow you to model change, which is a critical part of understanding the world around us.

In this installment of Codect, I’ll explain what derivatives are, how they are computed, and why they’re so important.

## What is a Derivative?

Imagine you're driving a car. At any given moment, your speedometer tells you how fast you’re going. Your speed is how much distance you cover per unit of time. If you think about it, that’s a rate of change—a measure of how your position is changing with respect to time. A derivative does exactly that: it measures the rate of change of a function at any point.

<p>
Mathematically, the derivative of a function \(f(x)\) with respect to \(x\) at a particular point \(x = a\) is defined in terms of a limit as:

$$
f^\prime(a) = \lim_{{h \to 0}} \frac{f(a + h) - f(a)}{h}
$$

<p>
This formula expresses how \(f(x)\) changes as \(x\) moves slightly from \(a\). The limit ensures we're looking at an infinitesimal change—that is, how the function changes when \(h\) is incredibly small.

## Slope and Tangents

In simpler terms, the derivative of a function gives us the slope of the tangent line at any given point on the graph of the function. A tangent line is a straight line that touches the curve at only one point, representing the best linear approximation to the curve at that point.

For example, let’s take a simple linear function:

$$
f(x) = 3x + 2
$$

<p>
The slope of this line is constant, and its derivative is just \(3\) everywhere. That makes sense because a straight line has the same slope at every point. However, with non-linear functions, the slope varies, and that’s where derivatives come in handy.

Consider a quadratic function:

$$
f(x) = x^2
$$

<p>
The derivative of \(f(x) = x^2\) is \(f^\prime(x) = 2x\), which means that the slope of the curve changes depending on the value of \(x\).

## Derivatives in Action

Let's break this down further with some common types of functions and their derivatives:

### Power Rule

<p>
If \(f(x) = x^n\), then the derivative is:

$$
f^\prime(x) = n \cdot x^{n - 1}
$$

<p>
This rule works for any power of \(x\), including fractions and negative exponents. For instance, if \(f(x) = x^3\), then \(f^\prime(x) = 3x^2\).

### Product Rule

When you have two functions multiplied together, the derivative of their product is:

$$
(fg)^\prime = f^\prime \cdot g + f \cdot g^\prime
$$

This means you differentiate each function separately and then apply this rule.

### Chain Rule

<p>
The chain rule is used when you have a function inside another function. If \(f(x) = g(h(x))\), then the derivative is:

$$
f^\prime(x) = g^\prime(h(x)) \cdot h^\prime(x)
$$

In other words, you differentiate the outer function and multiply it by the derivative of the inner function.

## Higher-Order Derivatives

<p>
Sometimes, we need to look at how the rate of change itself changes. This is where <strong>second derivatives</strong> and higher-order derivatives come into play. The second derivative, denoted as \(f^{\prime\prime}(x)\), measures the rate of change of the first derivative, providing insight into the <strong>concavity</strong> of the function.

<p>
<ul><li>If \(f^{\prime\prime}(x) > 0\), the graph of the function is concave up (shaped like a "U").</li>
<li>If \(f^{\prime\prime}(x) < 0\), the graph is concave down (shaped like an upside-down "U").</li>
</ul>

Second derivatives are especially useful in physics for analyzing acceleration, which is the rate of change of velocity (itself the first derivative of position with respect to time).

## Partial Derivatives

<p>
So far, we’ve been talking about functions with a single input, but what happens when we have multiple variables? For functions like \(f(x, y)\), we can take <strong>partial derivatives</strong> to see how the function changes with respect to each variable independently.

<p>
The partial derivatives of \(f(x,y)\) with respect to \(x\) is written as \(\frac{\partial f}{\partial x}\) and with respect to \(y\) as \(\frac{\partial f}{\partial y}\). These derivatives help us understand how the function changes along each axis.

<p>
The partial symbol \(\partial\) comes from the Greek letter <strong>delta</strong> \(\delta\), which is used to represent change in mathematics.

<p>
Partial derivatives is especially useful in fields like machine learning and physics, where we often deal with multivariable functions. For instance, consider a surface in 3D space—the partial derivatives give the slopes in the \(x\), \(y\) directions respectively.

## A Physics Example

<p>
Let’s consider a more concrete example of derivatives in action: the motion of a falling object. According to the laws of physics, the position of the object as a function of time can be given by this equation: \(s(t) = \frac{1}{2}gt^2\) where \(g\) is the acceleration due to gravity.

<p>
The derivative of this function with respect to \(t\) gives the velocity of the object at any given time. This would give us an equation of \(v(t)=s^\prime(t)=gt\)

<p>
Taking the derivative again, we get the acceleration of the object: \(a(t)=v^\prime(t)=s^{\prime\prime}(t)=g\). In this case, the accleration is constant, but the velocity changes with time—a perfect demonstration of derivatives in action.

## Why Derivatives Matter

While the mathematics behind derivatives can get quite complex, the core idea remains simple: they help us understand how things change. Whether you're dealing with simple functions or complex systems, derivatives provide a powerful tool for analyzing motion, growth, decay, and much more. The next time you see a curve, remember that derivatives are the key to unlocking its secrets.

---

*Sami Elsayed is a Senior at TJHSST, and the current Lead Sysadmin at the tjCSL. He's the Co-Founder of the Cardinal Development Organization, and the current Head Writer of "The Techbook."*