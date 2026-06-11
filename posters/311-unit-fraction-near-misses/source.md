# Source notes

## Problem ID
311

## Source link
https://www.erdosproblems.com/311

## Exact statement

Let $\delta(N)$ be the minimal non-zero value of $\lvert 1-\sum_{n\in A}\frac{1}{n}\rvert$ as $A$ ranges over all subsets of $\{1,\ldots,N\}$. Is it true that
\[
\delta(N)=e^{-(c+o(1))N}
\]
for some constant $c\in (0,1)$?

## Short label
Unit fraction near-misses

## Status
Open

## Tags
number theory, unit fractions

## Notes

The page notes the trivial lower bound
\[
\delta(N)\geq \frac{1}{[1,\ldots,N]}=e^{-(1+o(1))N},
\]
where \([1,\ldots,N]\) is the least common multiple of \(\{1,\ldots,N\}\).

It also states that Tang has shown
\[
\delta(N)\leq
\exp\left(
-c\frac{N}{(\log N\log\log N)^3}
\right)
\]
for some constant \(c>0\).

## Visual metaphor

Subset sums of unit fractions try to strike the target value \(1\).  
The problem asks how tiny the closest nonzero miss can be.