# Source notes

## Problem ID
901

## Source link
https://www.erdosproblems.com/901

## Exact statement

Let $m(n)$ be minimal such that there is an $n$-uniform hypergraph with $m(n)$ edges which is $3$-chromatic. Estimate $m(n)$.

## Short label
Three-chromatic uniform hypergraphs

## Status
Open

## Tags
combinatorics, hypergraphs

## Notes

The page explains that this is equivalent to asking for an \(n\)-uniform hypergraph without Property B.

Property B means that there exists a set \(S\) which intersects every edge, while containing no entire edge. Equivalently, the hypergraph is 2-colourable.

Known small values:

\[
m(2)=3,\qquad m(3)=7,\qquad m(4)=23.
\]

Erdős proved:

\[
2^n \ll m(n) \ll n^2 2^n.
\]

Further improvements include lower bounds of the form:

\[
(\log n)2^n \ll m(n),
\]

\[
n^{1/3-o(1)}2^n \ll m(n),
\]

and

\[
\sqrt{\frac{n}{\log n}}2^n \ll m(n).
\]

Erdős and Lovász speculated that the correct order of magnitude is:

\[
n2^n.
\]

## Visual metaphor

A hypergraph with too few edges may still admit a red-blue colouring.  
At \(m(n)\), the edge system becomes dense enough that every two-colouring creates a monochromatic edge, forcing a third colour.