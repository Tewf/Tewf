# Hi, I'm Mohamed 👋

🇫🇷 [Version française](README.fr.md)

I'm an M1 student in **Artificial Intelligence** at **Université Grenoble Alpes**
(UFR IM²AG and Ensimag), holder of the **EFELIA-MIAI** excellence scholarship and
of the French **student-entrepreneur** status (SNEE).

Everything below, at more length and with the figures:
**[tewf.github.io](https://tewf.github.io)**

## Research

**[bilinear-tensor-optimization](https://github.com/Tewf/bilinear-tensor-optimization)** · [browse it ↗](https://tewf.github.io/bilinear-tensor-optimization/) · *LJK, Université Grenoble Alpes · supervised by Jean-Guillaume Dumas · May to July 2024*

The rank of a bilinear map is the number of multiplications it needs; Strassen's
seven-instead-of-eight is the known case. A heuristic search over alternative bases takes
5×5 polynomial multiplication over GF(2) from **25 multiplications to 14**, and four
benchmark maps down by 37% to 44%. It does not prove those decompositions optimal.

**[tensor-rank-toolkit](https://github.com/Tewf/tensor-rank-toolkit)** · [browse it ↗](https://tewf.github.io/tensor-rank-toolkit/) · *the same question, continued independently in C++20 on Givaro*

Where the internship searched heuristically, this decides. It runs from a cheap descent up
to a SAT encoding whose refutations are checkable as DRAT. On the same 5×5 map over GF(2)
that the internship took to 14 products, an exhaustive search settles the rank at exactly
**13**, refuting 12 over 146 million nodes. Nothing here is ever a float, so a reported
rank is a fact about the map and not an artefact of rounding.

**[IA-Economie-Strategique](https://github.com/Tewf/IA-Economie-Strategique)** · [browse it ↗](https://tewf.github.io/IA-Economie-Strategique/) · [the article ↗](https://tewf.github.io/IA-Economie-Strategique/article/paper.html) · *GAEL, UGA and INRAE · supervised by Alexis Garapin and Olivier Bonroy · January to April 2025*

Do pricing algorithms sustain tacit collusion or break it? The internship proposed two
mechanisms without running either, and I have since run both. The imitation agent finishes
**eighth of eight, behind a coin flip**. Five local language models then played 220
matches: handed a mutually defecting opening, **three of the four readable ones never leave
it**, and a non-binding message frees exactly one. Escaping an imposed regime is a property
of the model rather than of the channel.

## Projects and studies

**[after-hours](https://github.com/Tewf/after-hours)** · [browse it ↗](https://tewf.github.io/after-hours/)

A CNN learning Flappy Bird from raw pixels, where the largest gain came from the
observation rather than a hyperparameter: taking the blue channel instead of a luminance
greyscale moved the agent from 0.4 pipes to **12.65** at the same 250k steps. Alongside it,
a 3-SAT solver over GF(2) and the French income tax modelled with the Lambert W function.

**[University-Coursework](https://github.com/Tewf/University-Coursework)** · [browse it ↗](https://tewf.github.io/University-Coursework/)

The Licence MIASHS and the M1 AI at UGA, end to end: hedonic pricing where the log-linear
specification is what makes the model work, five classifiers evaluated over 24 000
fragrances and the four retained compared on ROC, and a Battleship bot winning 74.3% of
300 round-robin games.

---

| | |
|---|---|
| **Languages** | C++ · Python · Java · R · Julia · SQL · Prolog |
| **Libraries** | PyTorch · scikit-learn · tidyverse · Quarto |
| **Spoken** | Arabic · French · English |

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Hamlil-blue?logo=linkedin)](https://linkedin.com/in/mohamedalitewfikhamlil)
[![Email](https://img.shields.io/badge/Email-UGA-blue?logo=gmail)](mailto:mohamed.hamlil@etu.univ-grenoble-alpes.fr)
