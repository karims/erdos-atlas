# Poster prompt: Erdős Problem #96

Create a vertical mathematical poster in the Erdős Atlas visual style:
ivory parchment background, black serif typography, deep red accents, delicate divider lines, elegant framing, and a refined mathematical-art composition.

Poster title:
Unit Chords in Convex Position

Subtitle:
Erdős Problem #96

Small label:
Unit distances among vertices of a convex polygon

Use the exact problem statement in a compact problem panel:

If $n$ points in $\mathbb{R}^2$ form a convex polygon then there are $O(n)$ many pairs which are distance $1$ apart.

Main visual structure:
1. A panel titled “The Problem”.
2. A panel titled “What is being counted?” explaining:
   - choose \(n\) points in convex position,
   - every point is a vertex of the convex hull,
   - count pairs at distance exactly \(1\).
3. A central visual:
   - draw a convex polygon with many vertices,
   - highlight several unit-distance chords in deep red,
   - keep other polygon edges/chords faint black or grey,
   - label a highlighted chord \(|a-b|=1\).
4. A counting panel:
   \[
   U(A)=\#\{\{a,b\}:a,b\in A,\ |a-b|=1\}.
   \]
5. A conjecture panel:
   \[
   U(A)\stackrel{?}{=}O(n).
   \]
6. A known upper bound panel:
   \[
   U(A)\leq n\log_2 n+4n.
   \]
7. A construction panel:
   \[
   U(A)\geq 2n-7
   \]
   for known examples.

Footer:
Status badge: Open
Source: erdosproblems.com/96

Design rules:
- Keep the house style close to the initial Erdős Atlas posters.
- Use ivory, black, and deep red.
- Do not overcrowd the poster.
- Make the central visual geometric: convex polygon vertices and highlighted unit chords.
- Keep the \(O(n)\) conjecture visually prominent.