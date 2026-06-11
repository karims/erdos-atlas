# Erdős Problem #580

## Title
Large-degree tree containment

## Status
Decidable

## Source
https://www.erdosproblems.com/580

## Problem statement

Let $G$ be a graph on $n$ vertices such that at least $n/2$ vertices have degree at least $n/2$. Must $G$ contain every tree on at most $n/2$ vertices?

## What is being asked?

We are given a graph \(G\) on \(n\) vertices.

At least half of its vertices are “large-degree” vertices:

\[
\deg(v)\geq \frac{n}{2}.
\]

The question asks whether this condition forces \(G\) to contain every tree \(T\) with

\[
|V(T)|\leq \frac{n}{2}.
\]

## Known context

This is a conjecture of Erdős, Füredi, Loebl, and Sós.

Ajtai, Komlós, and Szemerédi proved an asymptotic version, where at least \((1+\epsilon)n/2\) vertices have degree at least \((1+\epsilon)n/2\), for sufficiently large \(n\).

Zhao proved that the conjecture holds for all sufficiently large \(n\).

Komlós and Sós conjectured the broader statement that if at least \(n/2\) vertices have degree at least \(k\), then \(G\) contains every tree with \(k\) vertices.

## Visual idea

Show a graph with \(n\) vertices, where half the vertices are highlighted as high-degree hubs.

Then show a tree with at most \(n/2\) vertices being embedded into the dense/high-degree region of the graph.

The poster should visually emphasize:
- at least \(n/2\) high-degree vertices,
- each has degree at least \(n/2\),
- every tree \(T\) with at most \(n/2\) vertices,
- and the containment question \(T\subseteq G\).

## Poster title
Do Large Degrees Force Every Tree?