# Mohamed Hamlil

🇫🇷 [Version française](README.fr.md)

M1 in the [**Master of Artificial Intelligence**](https://m-ai.imag.fr/) at
Université Grenoble Alpes — jointly delivered by UFR IM²AG and Ensimag
(Grenoble INP). **EFELIA–MIAI** excellence scholar, and student-entrepreneur
under the French **SNEE** status.

**What I'm after.** The interesting question in my field is rarely *which model*.
It is what a computation actually costs, and how agents actually behave once you
let them optimise. That thread runs from algebraic complexity through game theory
to applied statistics, and it is why the four things below look unrelated and
are not.

---

## Research

Two internships, both in Université Grenoble Alpes laboratories.

### [Bilinear tensor optimisation](https://github.com/Tewf/bilinear-tensor-optimization) — LJK

The rank of a bilinear map is the number of multiplications needed to compute it.
Strassen's 7-instead-of-8 for 2×2 matrices is the reason fast matrix
multiplication exists at all, and finding such decompositions in general is still
open. I built heuristics for lowering that rank over finite fields, implemented in
Python and Julia, and a method for sparsifying the operators these algorithms rely
on. Supervised by Jean-Guillaume Dumas.

### [AI & strategic pricing](https://github.com/Tewf/IA-Economie-Strategique) — GAEL, INRAE/UGA

Humans tacitly collude in repeated price competition rather than converge to the
competitive equilibrium. Do algorithms do the same? I approached it from three
sides: the experimental-economics literature, a model of imitation grounded in
mirror neurons, and a Prolog agent put up against other students' agents in a
tournament.

---

## What I build on my own

[**Side_Projects**](https://github.com/Tewf/Side_Projects) — things I built
because I wanted to know whether they would work.

- **A CNN that learns Flappy Bird from raw pixels.** REINFORCE policy gradient on
  84×84 grayscale frames, with no access to game state — only what the screen
  shows.
- **A 3-SAT solver built on Gröbner bases over GF(2).** Clauses become polynomials,
  triangular elimination propagates, branching finishes the job. Verified against
  exhaustive enumeration, and the write-up is candid about exactly where the
  algebra stops helping.
- **The French income tax, solved.** Exponential fits per bracket, then the
  Lambert W function to locate the fiscal tipping point — €62,114 gross.

---

## Applied work

[**University-Coursework**](https://github.com/Tewf/University-Coursework) —
statistics, econometrics and machine learning on real data, with the source and
its rendered output side by side so it reads without cloning anything.

The piece I would open first predicts customer satisfaction for perfumes,
comparing five classifiers on ROC curves and confusion matrices with a
leakage-proof split — [readable in full online](https://tewf.github.io/University-Coursework/Bachelor/L3/S6/ComplementMath2/Projet/rapport/).

---

**Python · C++ · Java · R · Julia · SQL · Prolog**
Arabic (native) · French · English

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Hamlil-blue?logo=linkedin)](https://linkedin.com/in/mohamed-hamlil-4aa3a7335)
[![Email](https://img.shields.io/badge/Email-UGA-lightgrey?logo=gmail)](mailto:mohamed.hamlil@etu.univ-grenoble-alpes.fr)
