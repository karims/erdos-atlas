# Source notes

## Problem ID
222

## Source link
https://www.erdosproblems.com/222

## Exact statement

Let $n_1<n_2<\cdots$ be the sequence of integers which are the sum of two squares. Explore the behaviour of (i.e. find good upper and lower bounds for) the consecutive differences $n_{k+1}-n_k$.

## Short label
Gaps between sums of two squares

## Status
Open

## Tags
number theory, squares

## Notes

The page states that Erdős proved that, for infinitely many \(k\),

\[
n_{k+1}-n_k
\gg
\frac{\log n_k}{\sqrt{\log\log n_k}}.
\]

Richards improved this to

\[
\limsup_{k\to\infty}
\frac{n_{k+1}-n_k}{\log n_k}
\geq \frac14.
\]

The page says this constant has since been improved, most recently to \(0.868\cdots\) by Dietmann, Elsholtz, Kalmynin, Konyagin, and Maynard.

The best known upper bound listed on the page is due to Bambah and Chowla:

\[
n_{k+1}-n_k\ll n_k^{1/4}.
\]

## Visual metaphor

The integers representable as sums of two squares are marked stars on a number line.  
The mystery lies in the long dark gaps between consecutive stars.