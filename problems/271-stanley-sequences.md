# Erdős Problem #271

## Title
Stanley sequences

## Status
Open

## Source
https://www.erdosproblems.com/271

## Problem statement

Let $A(n)=\{a_0<a_1<\cdots\}$ be the sequence defined by $a_0=0$ and $a_1=n$, and for $k\geq 1$ define $a_{k+1}$ as the least positive integer such that there is no three-term arithmetic progression in $\{a_0,\ldots,a_{k+1}\}$.

Can the $a_k$ be explicitly determined? How fast do they grow?

## What is being constructed?

Start with

\[
a_0=0,\qquad a_1=n.
\]

Then keep adding the smallest possible positive integer that does not create a three-term arithmetic progression among the terms already chosen.

This produces a greedy progression-free sequence, known as a Stanley sequence.

## Known context

For \(A(1)\), the sequence is the set of integers whose base-3 expansion contains no digit \(2\).

Odlyzko and Stanley found similar characterisations for \(A(3^k)\) and \(A(2\cdot 3^k)\), and conjectured that such sequences eventually have one of two possible growth behaviours:

\[
a_k\asymp k^{\log_2 3}
\]

or

\[
a_k\asymp \frac{k^2}{\log k}.
\]

## Visual idea

A number line is built greedily.

Each candidate integer is either accepted or rejected depending on whether it would complete a forbidden three-term arithmetic progression.

The poster should visually emphasize:
- the greedy construction,
- accepted terms \(a_k\),
- rejected candidates that would create a 3-term AP,
- the special base-3/no-digit-2 example,
- and the two possible growth scales.

## Poster title
Greedy Progression-Free Sequences