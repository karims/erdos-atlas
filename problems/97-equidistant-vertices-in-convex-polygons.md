# Erdős Problem #97

## Title
Equidistant vertices in convex polygons

## Status
Open (falsifiable)

## Prize
$100

## Source
https://www.erdosproblems.com/97

## Problem statement

Does every convex polygon have a vertex with no other $4$ vertices equidistant from it?

## What is being asked?

Take the vertices of a convex polygon.

For a vertex \(v\), look at the distances from \(v\) to all other vertices:

\[
|v-w|,\qquad w\neq v.
\]

The problem asks whether every convex polygon must contain at least one vertex \(v\) for which no distance occurs four times.

Equivalently, must there be a vertex \(v\) such that there do not exist four distinct other vertices

\[
w_1,w_2,w_3,w_4
\]

with

\[
|v-w_1|=|v-w_2|=|v-w_3|=|v-w_4|?
\]

## Known context

Erdős originally conjectured the analogous statement with \(3\) equidistant vertices, but Danzer found a convex polygon on \(9\) points such that every vertex has three other vertices equidistant from it.

Fishburn and Reeds later found a convex polygon on \(20\) points such that every vertex has three other vertices equidistant from it, and the common distance is the same for all vertices.

The present problem asks whether replacing \(3\) by \(4\) restores the statement.

If true with \(k+1\) vertices, this would imply an upper bound of \(kn\) for the unit-distance problem in convex polygons.

## Visual idea

Show a convex polygon and one chosen vertex \(v\).

Draw concentric circles centered at \(v\), each circle collecting vertices at the same distance from \(v\).

The forbidden situation is one circle passing through four other vertices.

The poster should visually emphasize:
- convex polygon vertices,
- distances from a chosen vertex,
- equal-distance circles,
- the forbidden four-on-one-circle pattern,
- and the question: must some vertex avoid this pattern?

## Poster title
Four at the Same Distance?