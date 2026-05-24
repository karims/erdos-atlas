# Poster prompt: Erdős Problem #169

Create a vertical mathematical poster in the Erdős Atlas visual style:
ivory parchment background, black serif typography, deep red accents, delicate divider lines, elegant framing, and a refined mathematical-art composition.

Poster title:
Forbidden Progressions, Heavy Sums

Subtitle:
Erdős Problem #169

Small label:
Reciprocal sums over progression-free sets

Use the exact problem statement in a compact problem panel:

Let $k\geq 3$ and $f(k)$ be the supremum of $\sum_{n\in A}\frac{1}{n}$ as $A$ ranges over all sets of positive integers which do not contain a $k$-term arithmetic progression. Estimate $f(k)$.

Is
\[
\lim_{k\to \infty}\frac{f(k)}{\log W(k)}=\infty
\]
where $W(k)$ is the van der Waerden number?

Main visual structure:
1. A panel titled “The Problem”.
2. A panel titled “What is being maximized?” explaining:
   - choose a set \(A\subseteq\mathbb{N}\),
   - avoid all \(k\)-term arithmetic progressions,
   - maximize the reciprocal sum \(\sum_{n\in A}1/n\).
3. A central visual:
   - draw a number line with selected points belonging to \(A\),
   - show a forbidden \(k\)-term arithmetic progression as evenly spaced ghost points,
   - cross out the forbidden progression,
   - show reciprocal weights \(1/n\) as small descending tokens above selected elements.
4. A formula panel:
   \[
   f(k)=\sup_{A:\,A\text{ has no }k\text{-AP}}
   \sum_{n\in A}\frac{1}{n}.
   \]
5. A comparison panel:
   \[
   \lim_{k\to\infty}\frac{f(k)}{\log W(k)}\stackrel{?}{=}\infty.
   \]
6. A known lower bound panel:
   \[
   f(k)\geq (1-o(1))k\log k.
   \]

Footer:
Status badge: Open
Source: erdosproblems.com/169

Design rules:
- Keep the house style close to the initial Erdős Atlas posters.
- Use ivory, black, and deep red.
- Do not make this too dense.
- Make the central visual about avoiding arithmetic progressions while collecting reciprocal weight.
- Keep the notation \(f(k)\), \(W(k)\), and \(\sum_{n\in A}1/n\) visually central.