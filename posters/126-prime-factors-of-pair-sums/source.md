# Source notes

## Problem ID
126

## Source link
https://www.erdosproblems.com/126

## Exact statement

Let $f(n)$ be maximal such that if $A\subseteq\mathbb{N}$ has $\lvert A\rvert=n$ then $\prod_{a\neq b\in A}(a+b)$ has at least $f(n)$ distinct prime factors. Is it true that $f(n)/\log n\to\infty$?

## Short label
Prime factors of pair-sums

## Status
Open

## Prize
$250

## Tags
number theory

## Notes

The page says this problem was investigated by Erdős and Turán in their first joint paper, prompted by a question of Lázár and Grünwald.

They proved

\[
\log n \ll f(n)\ll \frac{n}{\log n}.
\]

The page notes that the upper bound is trivial by taking

\[
A=\{1,\ldots,n\}.
\]

It also says Erdős remarked that even proving

\[
f(n)=o\left(\frac{n}{\log n}\right)
\]

has never been proved, and perhaps never seriously attacked.

## Visual metaphor

Every pair of numbers in \(A\) casts a sum \(a+b\).  
The product of all these sums gathers prime divisors, and the problem asks how many distinct primes are unavoidable.