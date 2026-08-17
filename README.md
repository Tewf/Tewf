# Hi, I'm Mohamed 👋

🇫🇷 [Version française](README.fr.md)

I'm an M1 student in **Artificial Intelligence** at **Université Grenoble Alpes**
(UFR IM²AG and Ensimag), holder of the **EFELIA-MIAI** excellence scholarship and
of the French **student-entrepreneur** status (SNEE).

Everything below, at more length and with the figures:
**[tewf.github.io](https://tewf.github.io)**

## Research

**[bilinear-tensor-optimization](https://github.com/Tewf/bilinear-tensor-optimization)** · *LJK, Université Grenoble Alpes · supervised by Jean-Guillaume Dumas · May to July 2024*

The rank of a bilinear map is the number of multiplications it needs, which is where
Strassen's seven-instead-of-eight comes from. A heuristic search over alternative bases
cuts 5×5 polynomial multiplication over GF(2) from **25 multiplications to 14**, and
reduces four benchmark maps by 37% to 44%. It is a heuristic: it does not prove the
decompositions it finds are optimal.

**[IA-Economie-Strategique](https://github.com/Tewf/IA-Economie-Strategique)** · [browse it ↗](https://tewf.github.io/IA-Economie-Strategique/) · *GAEL, UGA and INRAE · supervised by Alexis Garapin and Olivier Bonroy · January to April 2025*

In repeated price competition, human players tend to settle on tacitly collusive prices
rather than the competitive equilibrium. Whether algorithms sustain that behaviour, break
it or intensify it is an open question, and one with direct consequences for competition
policy. The internship surveyed the literature and proposed two mechanisms without running
either; I have since run both, on shared opponents and one measure. The imitation agent the
report expected Tit-for-Tat to emerge from finishes **eighth of eight, behind a coin
flip**, because the update it implements cannot depend on the last round. Five local
language models then played 220 matches of the same game: handed a mutually defecting
opening they did not choose, **three of the four readable models never leave it**, and a
non-binding message frees exactly one of the three. Communication is neither necessary nor
sufficient for escaping an imposed regime — which model you ask decides it. It remains
exploratory: five small quantised models are not a population.

## Projects and studies

**[after-hours](https://github.com/Tewf/after-hours)** · [browse it ↗](https://tewf.github.io/after-hours/)

A CNN learning Flappy Bird from raw pixels, where the largest gain came from the
observation rather than from any hyperparameter: the bird is yellow and the sky is light
blue, so the two are nearly equiluminant, and taking the blue channel instead of a
luminance greyscale moved the agent from 0.4 pipes to **12.65** at the same 250k steps.
Alongside it, a 3-SAT solver over GF(2), matrix algorithms written from scratch and
checked against NumPy to 1e-13, and the French income tax modelled with the Lambert W
function.

**[University-Coursework](https://github.com/Tewf/University-Coursework)** · [browse it ↗](https://tewf.github.io/University-Coursework/)

The Licence MIASHS and the M1 AI at UGA, end to end. Hedonic pricing that cuts RMSE from
€265k to €59k, four classifiers compared on ROC over 24 000 fragrances, and a Battleship
bot winning 74.3% of its games, which you can watch playing a recorded game.

---

| | |
|---|---|
| **Languages** | Python · Java · R · Julia · SQL · Prolog |
| **Libraries** | PyTorch · scikit-learn · tidyverse · Quarto |
| **Spoken** | Arabic · French · English |

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Hamlil-blue?logo=linkedin)](https://linkedin.com/in/mohamed-hamlil-4aa3a7335)
[![Email](https://img.shields.io/badge/Email-UGA-blue?logo=gmail)](mailto:mohamed.hamlil@etu.univ-grenoble-alpes.fr)
