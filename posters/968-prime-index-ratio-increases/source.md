# Source notes

## Problem ID
968

## Source link
https://www.erdosproblems.com/forum/thread/968

## Exact statement

Let $u_n=p_n/n$, where $p_n$ is the $n$th prime. Does the set of $n$ such that $u_n<u_{n+1}$ have positive density?

## Short label
Prime index ratio increases

## Status
Open

## Tags
number theory

## Notes

The page notes that Erdős and Prachar proved

\[
\sum_{p_n<x} |u_{n+1}-u_n| \asymp (\log x)^2,
\]

and that the set of \(n\) such that

\[
u_n>u_{n+1}
\]

has positive density.

The page also explains that by “positive density,” Erdős most likely meant positive lower density: there exists a constant \(c>0\) such that, for all large \(x\), the number of such \(n\leq x\) is at least \(cx\).

A useful rearrangement is:

\[
u_n<u_{n+1}
\iff
\frac{p_n}{n}<\frac{p_{n+1}}{n+1}
\iff
p_{n+1}-p_n>\frac{p_n}{n}.
\]

By the prime number theorem, \(\frac{p_n}{n}\) is roughly \(\log n\), so the problem is connected to moderately large prime gaps.

## Visual metaphor

The prime sequence creates a ratio curve \(u_n=p_n/n\).  
The problem asks whether upward steps in that curve occur with positive density.