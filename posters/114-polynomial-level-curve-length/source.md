# Source notes

## Problem ID
114

## Source link
https://www.erdosproblems.com/114

## Exact statement

If $p(z)\in\mathbb{C}[z]$ is a monic polynomial of degree $n$ then is the length of the curve
\[
\{ z\in \mathbb{C} : \lvert p(z)\rvert=1\}
\]
maximised when $p(z)=z^n-1$?

## Short label
Polynomial level-curve length

## Status
Open (falsifiable)

## Prize
$250

## Tags
polynomials, analysis

## Notes

This is a problem of Erdős, Herzog, and Piranian.

Let \(f(n)\) be the maximal length of such a curve over monic polynomials of degree \(n\).

The source page states that when

\[
p(z)=z^n-1,
\]

the length is

\[
2n+O(1).
\]

Known progress listed on the page includes:

\[
f(n)\leq 4\pi n
\]

by Dolzhenko,

\[
f(n)\ll n
\]

by Borwein,

\[
f(n)\leq 9.173n
\]

by Eremenko and Hayman,

\[
f(n)\leq 2\pi n
\]

by Danchenko,

and the asymptotic estimate

\[
f(n)\leq 2n+O(n^{7/8})
\]

by Fryntov and Nazarov.

The page also states that Tao proved \(p(z)=z^n-1\) is the unique maximiser, up to rotation and translation, for all sufficiently large \(n\).

## Visual metaphor

A monic polynomial draws a level curve in the complex plane.  
The problem asks whether the symmetric curve from \(z^n-1\) is the longest possible one.