@def title = "Mick's first Franklin test"
@def hasmath = true
@def hascode = true

# Examples of how to:

\toc

## enter text

Learn how to use the Franklin.jl Package. Franklin.jl is a Static Site Generator written in Julia.
In this coding tutorial, you'll learn how to use Franklin to build a custom static website and learn how to use GitHub Desktop to deploy your website onto GitHub Pages.

## render maths equations

## insert Julia code

## insert a table from a CSV file

## insert an image file

## insert a clickable thumbnail to a youtube video

## inject raw HTML


<!--
# Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex.
-->