# Source notes

## Problem ID
169

## Source link
https://www.erdosproblems.com/169

## Exact statement

Let $k\geq 3$ and $f(k)$ be the supremum of $\sum_{n\in A}\frac{1}{n}$ as $A$ ranges over all sets of positive integers which do not contain a $k$-term arithmetic progression. Estimate $f(k)$.

Is
\[
\lim_{k\to \infty}\frac{f(k)}{\log W(k)}=\infty
\]
where $W(k)$ is the van der Waerden number?

## Short label
Progression-free reciprocal sums

## Status
Open

## Tags
additive combinatorics, arithmetic progressions

## Notes

The page states that Berlekamp proved
\[
f(k)\geq \frac{\log 2}{2}k.
\]

It also states that Gerver proved
\[
f(k)\geq (1-o(1))k\log k.
\]

The page notes that it is trivial that
\[
\frac{f(k)}{\log W(k)}\geq \frac{1}{2},
\]
but improving the right-hand side to any constant greater than \(1/2\) is open.

## Visual metaphor

A set \(A\) tries to be large in harmonic weight while avoiding the rigid structure of a \(k\)-term arithmetic progression.