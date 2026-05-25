# Erdős Problem #950

## Title
Prime reciprocal kernel

## Status
Open

## Source
https://www.erdosproblems.com/latex/950

## Problem statement

Let
\[
f(n) = \sum_{p<n}\frac{1}{n-p}.
\]
Is it true that
\[
\liminf f(n)=1
\]
and
\[
\limsup f(n)=\infty?
\]
Is it true that $f(n)=o(\log\log n)$ for all $n$?

## Visual idea

For each integer \(n\), look backward to all smaller primes \(p<n\).

Each prime contributes a weight

\[
\frac{1}{n-p},
\]

so primes close to \(n\) contribute heavily, while distant primes contribute weakly.

The poster should visually emphasize:
- a fixed integer \(n\),
- primes \(p<n\) lying to the left,
- reciprocal weights decaying with distance,
- the fluctuating size of \(f(n)\),
- and the three questions: \(\liminf\), \(\limsup\), and comparison with \(\log\log n\).

## Poster title
Prime Echoes Near \(n\)