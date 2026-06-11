# Source notes

## Problem ID
271

## Source link
https://www.erdosproblems.com/271

## Exact statement

Let $A(n)=\{a_0<a_1<\cdots\}$ be the sequence defined by $a_0=0$ and $a_1=n$, and for $k\geq 1$ define $a_{k+1}$ as the least positive integer such that there is no three-term arithmetic progression in $\{a_0,\ldots,a_{k+1}\}$.

Can the $a_k$ be explicitly determined? How fast do they grow?

## Short label
Stanley sequences

## Status
Open

## Tags
additive combinatorics, arithmetic progressions

## Notes

The page notes that sequences formed by starting from an initial segment and then greedily avoiding three-term arithmetic progressions are known as Stanley sequences.

It is easy to see that \(A(1)\) is the set of integers whose base-3 expansion contains no digit \(2\).

Odlyzko and Stanley found similar characterisations for \(A(3^k)\) and \(A(2\cdot 3^k)\), and conjectured that such sequences eventually satisfy either

\[
a_k\asymp k^{\log_2 3}
\]

or

\[
a_k\asymp \frac{k^2}{\log k}.
\]

No known sequence is proved to satisfy the second growth rate, though data suggests that \(A(4)\) may do so.

Moy proved that, for all such sequences and every \(\epsilon>0\),

\[
a_k\leq \left(\frac12+\epsilon\right)k^2
\]

for all sufficiently large \(k\). The page also notes an explicit bound:

\[
a_k\leq \frac{(k-1)(k+2)}{2}+n.
\]

## Visual metaphor

A greedy builder walks along the number line, accepting the next integer only if it does not complete a forbidden three-term arithmetic progression.