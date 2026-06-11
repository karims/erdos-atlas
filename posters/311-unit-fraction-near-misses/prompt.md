# Poster prompt: Erdős Problem #311

Create a vertical mathematical poster in the Erdős Atlas visual style:
ivory parchment background, black serif typography, deep red accents, delicate divider lines, elegant framing, and a refined mathematical-art composition.

Poster title:
Unit Fraction Near-Misses

Subtitle:
Erdős Problem #311

Small label:
How close can subset sums of unit fractions get to 1?

Use the exact problem statement in a compact problem panel:

Let $\delta(N)$ be the minimal non-zero value of
\[
\left|1-\sum_{n\in A}\frac{1}{n}\right|
\]
as $A$ ranges over all subsets of $\{1,\ldots,N\}$. Is it true that
\[
\delta(N)=e^{-(c+o(1))N}
\]
for some constant $c\in(0,1)$?

Main visual structure:
1. A panel titled “The Problem”.
2. A panel titled “What is being measured?” explaining:
   - choose \(A\subseteq\{1,\ldots,N\}\),
   - form the unit-fraction sum \(\sum_{n\in A}1/n\),
   - measure its nonzero distance from \(1\).
3. A central visual:
   - draw a horizontal target line or number scale centered at \(1\),
   - show many subset-sum marks clustered near \(1\),
   - highlight the closest nonzero miss as \(\delta(N)\),
   - show unit fractions as small tiles or weights feeding into the sum.
4. A formula panel:
   \[
   \delta(N)=
   \min_{\substack{A\subseteq\{1,\ldots,N\}\\
   \sum_{n\in A}1/n\neq 1}}
   \left|1-\sum_{n\in A}\frac{1}{n}\right|.
   \]
5. A scale question panel:
   \[
   \delta(N)\stackrel{?}{=}e^{-(c+o(1))N},
   \qquad 0<c<1.
   \]
6. A known lower bound panel:
   \[
   \delta(N)\geq \frac{1}{[1,\ldots,N]}
   =
   e^{-(1+o(1))N}.
   \]

Footer:
Status badge: Open
Source: erdosproblems.com/311

Design rules:
- Keep the house style close to the initial Erdős Atlas posters.
- Use ivory, black, and deep red.
- Do not overcrowd the poster.
- Make the central visual about “almost hitting 1” with unit-fraction subset sums.
- Keep \(\delta(N)\) and \(e^{-cN}\) visually prominent.