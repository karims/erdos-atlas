# Source notes

## Problem ID
950

## Source link
https://www.erdosproblems.com/latex/950

## Exact statement

Let
\[
f(n) = \sum_{p<n}\frac{1}{n-p}.
\]
Is it true that
\[
\liminf f(n)=1
\]
and
\[
\limsup f(n)=\infty?
\]
Is it true that $f(n)=o(\log\log n)$ for all $n$?

## Short label
Prime reciprocal kernel

## Status
Open

## Tags
number theory, primes

## Notes

The page says this function was considered by de Bruijn, Erdős, and Turán, who showed that
\[
\sum_{n<x}f(n)\sim \sum_{n<x}f(n)^2\sim x.
\]

It also notes that the study of \(f(p)\) is even harder, and Erdős could not prove that
\[
\sum_{p<x}f(p)^2\sim \pi(x).
\]

## Visual metaphor

An integer \(n\) listens backward to all smaller primes.  
Nearby primes give loud reciprocal echoes; distant primes give faint ones.