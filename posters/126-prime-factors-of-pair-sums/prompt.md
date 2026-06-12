# Poster prompt: Erdős Problem #126

Create a vertical mathematical poster in the Erdős Atlas visual style:
ivory parchment background, black serif typography, deep red accents, delicate divider lines, elegant framing, and a refined mathematical-art composition.

Poster title:
Prime Shadows of Pair-Sums

Subtitle:
Erdős Problem #126

Small label:
Distinct prime factors forced by all pair-sums

Use the exact problem statement in a compact problem panel:

Let $f(n)$ be maximal such that if $A\subseteq\mathbb{N}$ has $\lvert A\rvert=n$ then
\[
\prod_{a\neq b\in A}(a+b)
\]
has at least $f(n)$ distinct prime factors. Is it true that
\[
\frac{f(n)}{\log n}\to\infty?
\]

Main visual structure:
1. A panel titled “The Problem”.
2. A panel titled “Pair-sums” explaining:
   - choose \(A\subseteq\mathbb{N}\) with \(|A|=n\),
   - form \(a+b\) for every ordered or unordered pair with \(a\neq b\),
   - multiply all pair-sums together.
3. A central visual:
   - show a set \(A=\{a_1,\ldots,a_n\}\) as red/black number tokens,
   - draw arcs between pairs \(a_i,a_j\),
   - each arc produces a sum \(a_i+a_j\),
   - sums flow into a large product symbol.
4. A prime-factor panel:
   - show the product breaking into distinct prime tokens,
   - label them \(p_1,p_2,\ldots,p_{f(n)}\).
5. A guaranteed-count panel:
   \[
   \omega\!\left(\prod_{a\neq b\in A}(a+b)\right)\geq f(n)
   \]
   where \(\omega(m)\) counts distinct prime factors.
6. A growth question panel:
   \[
   \frac{f(n)}{\log n}\stackrel{?}{\longrightarrow}\infty.
   \]
7. A known bounds panel:
   \[
   \log n\ll f(n)\ll \frac{n}{\log n}.
   \]

Footer:
Status badge: Open
Prize badge: $250
Source: erdosproblems.com/126

Design rules:
- Keep the house style close to the initial Erdős Atlas posters.
- Use ivory, black, and deep red.
- Do not overcrowd the poster.
- Make the central visual about pair-sums flowing into distinct prime factors.
- Keep \(f(n)\), \(\prod(a+b)\), and \(f(n)/\log n\) visually prominent.