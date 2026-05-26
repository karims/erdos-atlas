# Source notes

## Problem ID
122

## Source link
https://www.erdosproblems.com/122

## Exact statement

For which number theoretic functions $f$ is it true that, for any $F(n)$ such that $F(n)/f(n)\to 0$ for almost all $n$, there are infinitely many $x$ such that
\[
\frac{\#\{ n\in \mathbb{N} : n+f(n)\in (x,x+F(x))\}}{F(x)}\to \infty?
\]

## Short label
Shifted arithmetic functions

## Status
Open

## Tags
number theory

## Notes

The page notes that Erdős was mainly considering number-theoretic functions that grow slowly, for example slower than
\[
(\log n)^{1-c}
\]
for some \(c>0\).

The page also states that Erdős, Pomerance, and Sárközy proved the more general claim for functions such as:
- \(\tau(n)\), the divisor function,
- \(\omega(n)\), the number of distinct prime divisors of \(n\).

It also says Erdős thought the statement probably fails for:
- \(\phi(n)\),
- \(\sigma(n)\).

## Visual metaphor

Each integer \(n\) is shifted forward by an arithmetic function \(f(n)\).  
The mystery is whether these shifted values must crowd into infinitely many tiny windows.