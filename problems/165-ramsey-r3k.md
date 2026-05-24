# Erdős Problem #165

## Title
The Ramsey number \(R(3,k)\)

## Status
Open

## Prize
$250

## Source
https://www.erdosproblems.com/165

## Problem statement

Give an asymptotic formula for $R(3,k)$.

## What is \(R(3,k)\)?

The Ramsey number \(R(3,k)\) is the smallest integer \(N\) such that every graph on \(N\) vertices contains either:

- a triangle, \(K_3\), or
- an independent set of size \(k\).

Equivalently, it is the threshold where one can no longer build a triangle-free graph while also avoiding an independent set of size \(k\).

## Known scale

It is known that for some constant \(c>0\),

\[
(c+o(1))\frac{k^2}{\log k}
\leq
R(3,k)
\leq
(1+o(1))\frac{k^2}{\log k}.
\]

The main mystery is the correct asymptotic constant.

## Visual idea

A large graph tries to avoid two opposite patterns:

- no red triangle / no triangle structure,
- no large independent set of \(k\) vertices.

The poster should visually show a graph balanced between two forbidden shapes: a triangle and a large empty set.

## Poster title
The Triangle–Independence Threshold