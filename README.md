# An elementary proof of nonexistence of Landau-Siegel zeros

An expository continuation of Chapter 10 of Tom M. Apostol's
*Introduction to Analytic Number Theory*, covering Sections 10.14--10.21.

[Read the PDF](apostol_chapter10_sections_10_14_onward.pdf)

## Overview

This note develops an elementary and fully explicit argument for excluding
real zeros of primitive Dirichlet $L$-functions that are too close to $1$
without complex analysis.
Its main result is the following estimate:

> Let $\chi$ be a real primitive character modulo $q$, where $q\ge 3$.
> If $0<\beta<1$ and $L(\beta,\chi)=0$, then

$$
(1-\beta)\log q\ge 10^{-6}.
$$

The proof combines the classification of real primitive characters, a
Frobenius congruence in $\mathbb Z[\sqrt d]$, a determinant constructed from
triangular lattice points, and explicit upper and lower estimates for a
weighted sum over primes satisfying $\chi(p)=-1$.

All constants are explicit. The exposition is intended for readers familiar
with the material developed earlier in Apostol's book.

## Background and Prior Work

The classical background begins with Siegel's ineffective estimate for real
zeros of Dirichlet $L$-functions and the Deuring--Heilbronn phenomenon.
Later elementary treatments include work of Pintz and Stopple. The
nonvanishing and interpolation-determinant ideas used in this area have
antecedents in work of Stepanov, Masser, Laurent, and Bombieri--Vaaler.

The immediate line of work to which this exposition belongs includes the
OpenAI Math Release, and subsequent accounts or refinements by Green, Banks,
Kerr, Tao, and van Dijk, together with the Stepanov-type presentation posted
by J. Pescador. The integer-minor construction and the refinement stated in
Exercise 23 are attributed to K. Barreto through those later accounts. This
note claims no new theorem or priority.

Selected references:

- [Tom M. Apostol, *Introduction to Analytic Number Theory* (1976)](https://doi.org/10.1007/978-1-4757-5579-4)
- [Hugh L. Montgomery and Robert C. Vaughan, *Multiplicative Number Theory I: Classical Theory* (2006)](https://doi.org/10.1017/CBO9780511618314)
- [OpenAI, *Uniform exclusion of Landau--Siegel zeros* (2026)](https://github.com/openai/math/blob/adc7f1241b42e322a6451854ab7e4b4c146bf78a/preprints/Uniform-exclusion-of-Landau-Siegel-zeros-October-1-2026/paper.pdf)
- [Ben Green, *On Landau--Siegel zeros* (2026)](https://hexagonmath.org/2610.00311v2)
- [GPT-6 Pro and Claude Opus 5.5, *Landau--Siegel zeros and a Stepanov-type nonvanishing lemma* (2026)](https://jacobpescador.github.io/ai-math/papers/landau-siegel-stepanov/)
- [William D. Banks, *On the OpenAI proof that Landau--Siegel zeros do not exist* (2026)](https://arxiv.org/abs/2610.15483v1)
- [Bryce Kerr, *A simpler proof that there are no Landau--Siegel zeros* (2026)](https://arxiv.org/abs/2610.21099v1)
- [Terence Tao, *A sketch of the proof of non-existence of Siegel zeroes* (2026)](https://terrytao.wordpress.com/2026/10/19/a-sketch-of-the-proof-of-non-existence-of-siegel-zeroes/)
- [Roelof van Dijk, *A Frobenius determinant proof of the non-existence of Landau--Siegel zeros* (2026)](https://hexagonmath.org/2610.00409v2)
- [C. L. Siegel, *Über die Classenzahl quadratischer Zahlkörper* (1935)](https://doi.org/10.4064/aa-1-1-83-86)
- [Jeffrey Stopple, *Elementary Deuring--Heilbronn phenomenon* (2012)](https://doi.org/10.4064/aa156-3-5)
- [Sergei A. Stepanov, *On the number of points of a hyperelliptic curve over a finite prime field* (1969)](https://doi.org/10.1070/IM1969v003n05ABEH000834)
- [David Masser, *On polynomials and exponential polynomials in several complex variables* (1981)](https://doi.org/10.1007/BF01389194)
- [Enrico Bombieri and Jeffrey Vaaler, *On Siegel's lemma* (1983)](https://eudml.org/doc/143033)

The article itself contains the full bibliography and more detailed
attribution.

## AI Contributions

GPT-6 Astra and GPT-5.6 Sol played a substantial role in the creation of this
article. Their contributions included developing and refining proofs,
independent mathematical review, improving the exposition and organization,
and preparing the LaTeX manuscript. 

## Contents

- 10.14 Real characters and real zeros
- 10.15 Elementary estimates with constants
- 10.16 The Frobenius congruence and root counting
- 10.17 A determinant from triangular lattice points
- 10.18 An upper bound for $S_-(X)$
- 10.19 A lower bound for $S_-(X)$
- 10.20 Weighted divisor sums at a real zero
- 10.21 Exclusion of real zeros near $1$
- Exercises
- Notes and references

## Files

- [LaTeX source](apostol_chapter10_sections_10_14_onward.tex)
- [Compiled PDF](apostol_chapter10_sections_10_14_onward.pdf)

## Scope and attribution

This note is a hypothetical continuation of Apostol's original book.

The mathematical and historical sources used in preparing the note are listed
in its references section. 
