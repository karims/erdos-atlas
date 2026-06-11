# Erdős Problem #901

## Title
Three-chromatic uniform hypergraphs

## Status
Open

## Source
https://www.erdosproblems.com/901

## Problem statement

Let $m(n)$ be minimal such that there is an $n$-uniform hypergraph with $m(n)$ edges which is $3$-chromatic. Estimate $m(n)$.

## What is being measured?

An \(n\)-uniform hypergraph is a hypergraph in which every edge contains exactly \(n\) vertices.

A hypergraph is \(3\)-chromatic if its vertices cannot be coloured with only two colours without creating a monochromatic edge.

So \(m(n)\) asks:

What is the smallest number of \(n\)-element edges needed to force chromatic number at least \(3\)?

## Known context

Equivalently, this asks for the smallest number of edges in an \(n\)-uniform hypergraph without Property B.

Known small values include:

\[
m(2)=3,\qquad m(3)=7,\qquad m(4)=23.
\]

Known bounds include:

\[
2^n \ll m(n) \ll n^2 2^n.
\]

Erdős and Lovász speculated that the correct order may be:

\[
m(n)\asymp n2^n.
\]

## Visual idea

Show a collection of \(n\)-element hyperedges as overlapping red and black regions.

A failed 2-colouring should be visualized as every red/blue vertex colouring producing at least one monochromatic hyperedge.

The poster should visually emphasize:
- \(n\)-uniform edges,
- the minimum edge count \(m(n)\),
- failure of 2-colourability,
- and the suspected scale \(n2^n\).

## Poster title
Forcing a Third Colour