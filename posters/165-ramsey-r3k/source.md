# Source notes

## Problem ID
165

## Source link
https://www.erdosproblems.com/165

## Exact statement

Give an asymptotic formula for $R(3,k)$.

## Short label
Ramsey number \(R(3,k)\)

## Status
Open

## Prize
$250

## Tags
graph theory, Ramsey theory

## Background

\(R(3,k)\) is the smallest \(N\) such that every graph on \(N\) vertices contains either a triangle \(K_3\) or an independent set of size \(k\).

Equivalently, it measures how large a triangle-free graph can be while still avoiding an independent set of size \(k\).

## Known bounds

For large \(k\), it is known that there exists some constant \(c>0\) such that

\[
(c+o(1))\frac{k^2}{\log k}
\leq
R(3,k)
\leq
(1+o(1))\frac{k^2}{\log k}.
\]

The source page notes:
- Kim proved the lower bound of this order.
- Shearer proved the upper bound.
- Later work improved the known lower-bound constant.
- Recent work suggests that the correct constant may be \(1/2\).

## Visual metaphor

A graph near \(R(3,k)\) lives between two forbidden structures:
a triangle and a large independent set.