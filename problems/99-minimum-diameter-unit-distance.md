# Erdős Problem #99

## Title
Minimum diameter unit-distance sets

## Status
Open

## Prize
$100

## Source
https://www.erdosproblems.com/99

## Problem statement

Let $A\subseteq\mathbb{R}^2$ be a set of $n$ points with minimum distance equal to 1, chosen to minimise the diameter of $A$. If $n$ is sufficiently large then must there be three points in $A$ which form an equilateral triangle of size 1?

## What is being optimized?

We choose \(n\) points in the plane.

The closest pair of points must be exactly distance \(1\):

\[
\min_{a\neq b\in A}|a-b|=1.
\]

Among all such point sets, choose one with the smallest possible diameter:

\[
\operatorname{diam}(A)=\max_{a,b\in A}|a-b|.
\]

The question asks whether, for sufficiently large \(n\), every such diameter-minimizing set must contain a unit equilateral triangle.

## Known context

Thue proved that the minimal diameter is asymptotically achieved by taking points from the triangular lattice inside a circle.

Erdős believed that extremal sets should have very large overlap with the triangular lattice, perhaps as many as \((1-o(1))n\) points.

The statement is false for \(n=4\), for example using the four vertices of a square.

## Visual idea

Show a compact cloud of points with minimum spacing \(1\), squeezed into the smallest possible disk.

The triangular lattice should appear faintly in the background, suggesting the expected extremal structure.

The poster should visually emphasize:
- minimum pairwise distance \(1\),
- minimizing the diameter,
- triangular-lattice packing,
- and the question of whether a unit equilateral triangle must appear.

## Poster title
The Smallest Diameter Trap