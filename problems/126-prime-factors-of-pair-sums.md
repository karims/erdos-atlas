# Erdős Problem #126

## Title
Prime factors of pair-sums

## Status
Open

## Prize
$250

## Source
https://www.erdosproblems.com/126

## Problem statement

Let $f(n)$ be maximal such that if $A\subseteq\mathbb{N}$ has $\lvert A\rvert=n$ then
\[
\prod_{a\neq b\in A}(a+b)
\]
has at least $f(n)$ distinct prime factors. Is it true that
\[
\frac{f(n)}{\log n}\to\infty?
\]

## What is being measured?

Take any set \(A\subseteq\mathbb{N}\) of size \(n\).

Form all pair-sums

\[
a+b,\qquad a\neq b,\quad a,b\in A.
\]

Multiply all of those sums together, then count how many distinct prime numbers divide the product.

The function \(f(n)\) is the largest guaranteed lower bound: no matter which \(n\)-element set \(A\) is chosen, the product must have at least \(f(n)\) distinct prime factors.

## Known context

Erdős and Turán proved

\[
\log n \ll f(n)\ll \frac{n}{\log n}.
\]

The upper bound comes from taking

\[
A=\{1,\ldots,n\}.
\]

The open question asks whether the guaranteed number of distinct prime factors grows faster than \(\log n\).

## Visual idea

Show a set \(A\) of \(n\) numbers producing many pair-sums.

Each pair-sum breaks into prime factors, and the poster counts the distinct primes appearing anywhere in the whole product.

The poster should visually emphasize:
- pair-sums \(a+b\),
- the product over \(a\neq b\),
- distinct prime factors,
- the guaranteed lower bound \(f(n)\),
- and the growth question \(f(n)/\log n\to\infty\).

## Poster title
Prime Shadows of Pair-Sums