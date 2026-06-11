# Erdős Problem #222

## Title
Gaps between sums of two squares

## Status
Open

## Source
https://www.erdosproblems.com/222

## Problem statement

Let $n_1<n_2<\cdots$ be the sequence of integers which are the sum of two squares. Explore the behaviour of (i.e. find good upper and lower bounds for) the consecutive differences $n_{k+1}-n_k$.

## What is being measured?

An integer belongs to the sequence if it can be written as

\[
n=a^2+b^2
\]

for some integers \(a,b\).

The problem asks how large the gaps can be between consecutive such integers:

\[
n_{k+1}-n_k.
\]

## Known context

Erdős proved that for infinitely many \(k\),

\[
n_{k+1}-n_k
\gg
\frac{\log n_k}{\sqrt{\log\log n_k}}.
\]

Richards improved this to a lower-bound constant on the scale \(\log n_k\), and later work improved the constant further.

The best known general upper bound is

\[
n_{k+1}-n_k\ll n_k^{1/4}.
\]

## Visual idea

Show the number line with special integers marked as sums of two squares.

Most gaps are small, but occasionally a long empty interval appears before the next representable integer.

The poster should visually emphasize:
- integers of the form \(a^2+b^2\),
- consecutive marked values \(n_k,n_{k+1}\),
- the gap \(n_{k+1}-n_k\),
- lower-bound and upper-bound scales,
- and the open question of the true gap behaviour.

## Poster title
Gaps Between Two-Square Numbers