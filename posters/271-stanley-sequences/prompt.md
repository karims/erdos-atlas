# Poster prompt: Erdős Problem #271

Create a vertical mathematical poster in the Erdős Atlas visual style:
ivory parchment background, black serif typography, deep red accents, delicate divider lines, elegant framing, and a refined mathematical-art composition.

Poster title:
Greedy Progression-Free Sequences

Subtitle:
Erdős Problem #271

Small label:
Stanley sequences and three-term arithmetic progressions

Use the exact problem statement in a compact problem panel:

Let $A(n)=\{a_0<a_1<\cdots\}$ be the sequence defined by $a_0=0$ and $a_1=n$, and for $k\geq 1$ define $a_{k+1}$ as the least positive integer such that there is no three-term arithmetic progression in $\{a_0,\ldots,a_{k+1}\}$.

Can the $a_k$ be explicitly determined? How fast do they grow?

Main visual structure:
1. A panel titled “The Problem”.
2. A panel titled “The Greedy Rule” explaining:
   - start with \(a_0=0\), \(a_1=n\),
   - scan positive integers in order,
   - accept the least candidate that creates no 3-term AP.
3. A central visual:
   - draw a horizontal number line,
   - mark accepted terms in deep red,
   - mark rejected candidates in faint black or grey,
   - show a rejected candidate completing a forbidden pattern
     \[
     x,\quad x+d,\quad x+2d.
     \]
4. A formula panel:
   \[
   a_{k+1}=\min\{t>0:\{a_0,\ldots,a_k,t\}\text{ has no }3\text{-AP}\}.
   \]
5. A special example panel:
   \[
   A(1)=\{\text{integers with no digit }2\text{ in base }3\}.
   \]
6. A growth question panel:
   \[
   a_k\asymp k^{\log_2 3}
   \quad\text{or}\quad
   a_k\asymp \frac{k^2}{\log k}?
   \]
7. Optional bound panel:
   \[
   a_k\leq \frac{(k-1)(k+2)}{2}+n.
   \]

Footer:
Status badge: Open
Source: erdosproblems.com/271

Design rules:
- Keep the house style close to the initial Erdős Atlas posters.
- Use ivory, black, and deep red.
- Do not overcrowd the poster.
- Make the central visual about the greedy accept/reject process.
- Keep the forbidden 3-term arithmetic progression visually clear.