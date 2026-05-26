# Source notes

## Problem ID
567

## Source link
https://www.erdosproblems.com/567

## Exact statement

Let $G$ be either $Q_3$ or $K_{3,3}$ or $H_5$ (the last formed by adding two vertex-disjoint chords to $C_5$). Is it true that, if $H$ has $m$ edges and no isolated vertices, then
\[
R(G,H)\ll m?
\]

## Short label
Ramsey size linear graphs

## Status
Open

## Tags
graph theory, Ramsey theory

## Notes

The page explains the problem as asking whether \(G\) is Ramsey size linear.

The three candidate graphs are:
- \(Q_3\), the 3-dimensional cube graph,
- \(K_{3,3}\), the complete bipartite graph with parts of size 3,
- \(H_5\), formed by adding two vertex-disjoint chords to \(C_5\).

The page also says \(H_5\) can be described as \(K_4^*\), obtained from \(K_4\) by subdividing one edge.

It notes that Bradać, Gishboliner, and Sudakov proved that every subdivision of \(K_4\) on at least 6 vertices is Ramsey size linear, and also that
\[
R(H_5,H)\ll m
\]
whenever \(H\) is bipartite with \(m\) edges and no isolated vertices.

## Visual metaphor

A fixed forbidden graph \(G\) is tested against every graph \(H\) of size \(m\).  
The question is whether the Ramsey threshold grows only linearly with the number of edges in \(H\).