# Bonjour, je suis Mohamed 👋

🇬🇧 [English version](README.md)

Étudiant en M1 **Intelligence Artificielle** à l'**Université Grenoble Alpes**
(UFR IM²AG et Ensimag), lauréat de la bourse d'excellence **EFELIA-MIAI** et
titulaire du statut national **étudiant-entrepreneur** (SNEE).

Tout ce qui suit, en plus long et avec les figures :
**[tewf.github.io](https://tewf.github.io)**

## Recherche

**[bilinear-tensor-optimization](https://github.com/Tewf/bilinear-tensor-optimization)** · *LJK, Université Grenoble Alpes · sous la direction de Jean-Guillaume Dumas · mai à juillet 2024*

Le rang d'une application bilinéaire est le nombre de multiplications qu'elle demande ; le
sept-au-lieu-de-huit de Strassen en est le cas connu. Une recherche heuristique sur des
bases alternatives fait passer la multiplication de polynômes 5×5 sur GF(2) de **25
multiplications à 14**, et réduit quatre applications de référence de 37 % à 44 %. Elle ne
prouve pas que ces décompositions sont optimales.

**[tensor-rank-toolkit](https://github.com/Tewf/tensor-rank-toolkit)** · [le parcourir ↗](https://tewf.github.io/tensor-rank-toolkit/) · *la même question, poursuivie de façon indépendante en C++20 sur Givaro*

Là où le stage cherchait heuristiquement, celui-ci décide. Il va d'une descente bon marché
jusqu'à un encodage SAT dont les réfutations se vérifient en DRAT. Sur la même application
5×5 sur GF(2) que le stage amenait à 14 produits, une recherche exhaustive fixe le rang à
exactement **13**, en réfutant 12 sur 146 millions de nœuds. Rien ici n'est jamais un
flottant, donc un rang annoncé est un fait sur l'application et non un artefact d'arrondi.

**[IA-Economie-Strategique](https://github.com/Tewf/IA-Economie-Strategique)** · [le parcourir ↗](https://tewf.github.io/IA-Economie-Strategique/) · [l'article ↗](https://tewf.github.io/IA-Economie-Strategique/article/paper.fr.html) · *GAEL, UGA et INRAE · sous la direction d'Alexis Garapin et Olivier Bonroy · janvier à avril 2025*

Les algorithmes de tarification entretiennent-ils la collusion tacite ou la rompent-ils ?
Le stage a proposé deux mécanismes sans en exécuter aucun, et je les ai depuis exécutés
tous les deux. L'agent d'imitation termine **huitième sur huit, derrière un tirage à pile
ou face**. Cinq modèles de langage locaux ont ensuite joué 220 matchs : placés sur une
ouverture de défection mutuelle, **trois des quatre modèles lisibles n'en sortent jamais**,
et un message non contraignant n'en libère exactement qu'un. Sortir d'un régime imposé est
une propriété du modèle plutôt que du canal.

## Projets et cursus

**[after-hours](https://github.com/Tewf/after-hours)** · [parcourir ↗](https://tewf.github.io/after-hours/)

Un CNN qui apprend Flappy Bird à partir des pixels bruts, où le plus grand gain vient de
l'observation et non d'un hyperparamètre : prendre le canal bleu plutôt qu'un niveau de
gris de luminance fait passer l'agent de 0,4 à **12,65** tuyaux au même budget de 250k pas.
À côté, un solveur 3-SAT sur GF(2) et l'impôt français modélisé avec la fonction W de
Lambert.

**[University-Coursework](https://github.com/Tewf/University-Coursework)** · [parcourir ↗](https://tewf.github.io/University-Coursework/)

La Licence MIASHS et le M1 IA à l'UGA, de bout en bout : des prix hédoniques où c'est la
spécification log-linéaire qui fait tenir le modèle, cinq classifieurs évalués sur 24 000
parfums dont les quatre retenus comparés sur ROC, et un bot de bataille navale qui gagne
74,3 % de 300 parties en tournoi toutes rondes.

---

| | |
|---|---|
| **Langages** | C++ · Python · Java · R · Julia · SQL · Prolog |
| **Bibliothèques** | PyTorch · scikit-learn · tidyverse · Quarto |
| **Langues parlées** | arabe · français · anglais |

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Hamlil-blue?logo=linkedin)](https://linkedin.com/in/mohamedalitewfikhamlil)
[![Email](https://img.shields.io/badge/Email-UGA-blue?logo=gmail)](mailto:mohamed.hamlil@etu.univ-grenoble-alpes.fr)
