# Erdős Problem #96

## Title
Unit distances in convex polygons

## Status
Open

## Source
https://www.erdosproblems.com/96

## Problem statement

If $n$ points in $\mathbb{R}^2$ form a convex polygon then there are $O(n)$ many pairs which are distance $1$ apart.

## What is being counted?

Place \(n\) points in the plane so that they are in convex position: they form the vertices of a convex polygon.

Count the number of pairs of points whose distance is exactly \(1\).

The conjecture says this number should grow only linearly with \(n\):

\[
\#\{\{a,b\}:a,b\in A,\ |a-b|=1\}=O(n).
\]

## Known context

This conjecture is due to Erdős and Moser.

Füredi proved an upper bound of

\[
O(n\log n).
\]

The best known upper bound listed on the source page is

\[
n\log_2 n+4n.
\]

Edelsbrunner and Hajnal constructed examples with

\[
2n-7
\]

unit-distance pairs.

## Visual idea

Show a convex polygon with many chords of length \(1\).

The poster should visually emphasize:
- points in convex position,
- unit-distance chords,
- the count of such pairs,
- known lower examples near \(2n\),
- known upper bound \(n\log_2 n+4n\),
- and the conjectured linear scale \(O(n)\).

## Poster title
Unit Chords in Convex Position