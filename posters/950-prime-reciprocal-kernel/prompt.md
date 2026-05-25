# Poster prompt: Erdős Problem #950

Create a vertical mathematical poster in the Erdős Atlas visual style:
ivory parchment background, black serif typography, deep red accents, delicate divider lines, elegant framing, and a refined mathematical-art composition.

Poster title:
Prime Echoes Near n

Subtitle:
Erdős Problem #950

Small label:
Reciprocal distances from n to smaller primes

Use the exact problem statement in a compact problem panel:

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

Main visual structure:
1. A panel titled “The Problem”.
2. A panel titled “What is being summed?” explaining:
   - fix an integer \(n\),
   - look at all primes \(p<n\),
   - each prime contributes weight \(1/(n-p)\),
   - nearby primes matter most.
3. A central visual:
   - draw a horizontal number line,
   - place a large marked point \(n\) on the right,
   - mark several smaller primes \(p<n\) to the left,
   - draw arcs or rays from each prime to \(n\),
   - make nearby arcs darker/thicker to show larger reciprocal weight,
   - make distant arcs faint/thin.
4. A formula panel:
   \[
   f(n)=\sum_{p<n}\frac{1}{n-p}
   \]
5. A fluctuation panel:
   \[
   \liminf f(n)\stackrel{?}{=}1,
   \qquad
   \limsup f(n)\stackrel{?}{=}\infty
   \]
6. A growth question panel:
   \[
   f(n)\stackrel{?}{=}o(\log\log n)
   \]
7. Optional average-behaviour note:
   \[
   \sum_{n<x}f(n)\sim \sum_{n<x}f(n)^2\sim x
   \]

Footer:
Status badge: Open
Source: erdosproblems.com/latex/950

Design rules:
- Keep the house style close to the initial Erdős Atlas posters.
- Use ivory, black, and deep red.
- Do not overcrowd the poster.
- Make the central visual about reciprocal echoes from primes below \(n\).
- Keep the formulas crisp and legible.