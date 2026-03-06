# Reading concordances in the 21st century: Teaching materials

This repository collects teaching materials created by the [RC21 project](https://www.dhss.phil.fau.eu/research/current-projects/reading-concordances-in-the-21st-century-rc21/).

All materials are available for reuse under the terms of the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license (see file `LICENSE`).

![CC BY-NC-SA 4.0](media/by-nc-sa.eu.png)

---

## FlexiConc: Reading Concordances with Algorithms

Tutorial at the Konvens 2025 conference, 9 September 2025, Hildesheim, Germany.

**Stephanie Evert** and **Alexander Piperski** (FAU Erlangen-Nürnberg)

> Concordance analysis is a central technique in corpus linguistics, computational lexicography, discourse analysis, digital humanities, and other fields. In this tutorial, we show how concordance reading can be supported with well-established as well as innovative computational algorithms. We present **FlexiConc**, a Python library developed specifically for this purpose which works with concordance data from various corpus tools (including CWB, Sketch Engine, KorAP, and CLiC). Following a theoretical introduction to the principles and five key strategies of concordance reading, we introduce a general mathematical framework for algorithms organised around the five strategies, as well as our approach to comprehensive research documentation in terms of analysis trees. We also discuss the practical implementation of FlexiConc, its integration with host apps, and the challenges we have faced. The last part of the tutorial is a hands-on session showing how to use FlexiConc in a Jupyter Notebook environment, which enables a tight integration of quantitative and qualitative approaches.

### Slides

- [RC21 Tutorial Part 1](slides/RC21_tutorial_part1.pdf)  
- [RC21 Tutorial Part 2](slides/RC21_tutorial_part2.pdf)

These slides introduce the theoretical foundations and computational framework for algorithmic concordance reading.

### Jupyter notebooks

Hands-on materials demonstrating how to use FlexiConc.

- [FlexiConc introduction notebook](tutorials/konvens2025/flexiconc_introduction_Konvens_2025.ipynb)  
- [Loading your own data notebook](tutorials/konvens2025/flexiconc_loading_data_Konvens_2025.ipynb)

These notebooks demonstrate concordance analysis workflows and FlexiConc algorithms.

They can be run locally or in **Google Colab**.

### Example datasets

Example data used in the tutorial.

- [CQPweb concordance export](data/CQPweb_WaterSanitation_ParlUK.txt)  
- [WMatrix corpus export](data/WMatrix_Water_ParlUK.db)

These files allow you to reproduce the examples used in the notebooks.

### Citation

Stephanie Evert, Alexander Piperski (2025).  
FlexiConc: Reading Concordances with Algorithms. Tutorial at the 21st Conference on Natural Language Processing (KONVENS 2025), 9 September 2025, Hildesheim, Germany.  
https://github.com/reading-concordances/teaching/tutorials/konvens2025

---

## Handout: Using FlexiConc via CLiC

A hands-on guide to concordance analysis using FlexiConc via the **[CLiC web app](https://clic-fiction.com)**.

This PDF walks through all currently available algorithms, illustrated with a case study on body part nouns in 19th-century English fiction. Includes exercises and worked examples.

- [Handout](handouts/flexiconc_clic_handout_all_steps.pdf)

### Citation

Nathan Dykes, Stephanie Evert, Michaela Mahlberg, Alexander Piperski (2026).  
*Using FlexiConc via CLiC: a case study on literary fiction.*