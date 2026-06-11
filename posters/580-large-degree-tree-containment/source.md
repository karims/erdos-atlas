# Source notes

## Problem ID
580

## Source link
https://www.erdosproblems.com/580

## Exact statement

Let $G$ be a graph on $n$ vertices such that at least $n/2$ vertices have degree at least $n/2$. Must $G$ contain every tree on at most $n/2$ vertices?

## Short label
Large-degree tree containment

## Status
Decidable

## Tags
graph theory

## Notes

This is a conjecture of Erdős, Füredi, Loebl, and Sós.

Ajtai, Komlós, and Szemerédi proved an asymptotic version, where at least
\[
(1+\epsilon)n/2
\]
vertices have degree at least
\[
(1+\epsilon)n/2,
\]
for sufficiently large \(n\), depending on \(\epsilon\).

Zhao proved that the conjecture holds for all sufficiently large \(n\).

Komlós and Sós conjectured the generalisation that if at least \(n/2\) vertices have degree at least \(k\), then \(G\) contains any tree with \(k\) vertices.

## Visual metaphor

Half the graph forms a reservoir of high-degree vertices.  
The question asks whether this reservoir is rich enough to contain every small tree.