# Source notes

## Problem ID
96

## Source link
https://www.erdosproblems.com/96

## Exact statement

If $n$ points in $\mathbb{R}^2$ form a convex polygon then there are $O(n)$ many pairs which are distance $1$ apart.

## Short label
Unit distances in convex polygons

## Status
Open

## Tags
geometry, distances, convex

## Notes

The page says the problem was conjectured by Erdős and Moser.

Erdős later credited the conjecture that the true upper bound is \(2n\) to himself and Fishburn.

Füredi proved an upper bound of

\[
O(n\log n).
\]

The best known upper bound listed on the page is due to Aggarwal:

\[
\leq n\log_2 n+4n.
\]

Edelsbrunner and Hajnal constructed \(n\) points in convex position with

\[
2n-7
\]

unit-distance pairs.

This disproved an earlier stronger conjecture that the true answer was \(\frac{5}{3}n+O(1)\).

## Visual metaphor

A convex polygon is threaded by special chords of length \(1\).  
The mystery is whether only linearly many such unit chords can exist.