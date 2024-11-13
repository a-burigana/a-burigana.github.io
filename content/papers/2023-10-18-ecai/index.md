---
title: "A Semantic Approach to Decidability in Epistemic Planning"
date: 2023-10-18
lastmod: 2024-11-12
tags: ["Epistemic Planning","Dynamic Epistemic Logic","Decidability"]
author: ["Alessandro Burigana", "Paolo Felli", "Marco Montali", "Nicolas Troquard"]
description: "ECAI 2023."
summary: ""
editPost:
    URL: "https://doi.org/10.3233/FAIA230286"
    Text: "Proceedings of the 26th European Conference on Artificial Intelligence, ECAI 2023"

---

---

##### Download

+ [Paper](https://doi.org/10.3233/FAIA230286)
+ [Supplementary material](supplementary.pdf)

---

##### Abstract

The use of Dynamic Epistemic Logic (DEL) in multi-agent planning has led to a widely adopted action formalism that can handle nondeterminism, partial observability and arbitrary knowledge nesting. As such expressive power comes at the cost of undecidability, several decidable fragments have been isolated, mainly based on syntactic restrictions of the action formalism. In this paper, we pursue a novel *semantic approach* to achieve decidability. Namely, rather than imposing syntactical constraints, the semantic approach focuses on the axioms of the logic for epistemic planning. Specifically, we augment the logic of knowledge S5$_n$ and with an interaction axiom called *(knowledge) commutativity*, which controls the ability of agents to unboundedly reason on the knowledge of other agents. We then provide a threefold contribution. First, we show that the resulting epistemic planning problem is decidable. In doing so, we prove that our framework admits a finitary non-fixpoint characterization of common knowledge, which is of independent interest. Second, we study different generalizations of the commutativity axiom, with the goal of obtaining decidability for more expressive fragments of DEL. Finally, we show that two well-known epistemic planning systems based on action templates, when interpreted under the setting of knowledge, conform to the commutativity axiom, hence proving their decidability.

---

##### Citation

Fabiano, F., Burigana, A., Dovier, A., and Pontelli, E. 2020. "EFP 2.0: A Multi-Agent Epistemic Solver with Multiple E-State Representations", *Proceedings of the Thirtieth International Conference on Automated Planning and Scheduling, Nancy, France, October 26-30, 2020*, Vol. 30: 101--109. https://ojs.aaai.org/index.php/ICAPS/article/view/6650.

```BibTeX
@inproceedings{conf/ecai/BuriganaFMT2023,
    author    = {Alessandro Burigana and
                Paolo Felli and
                Marco Montali and
                Nicolas Troquard},
    editor    = {Kobi Gal and
                Ann Now{\'{e}} and
                Grzegorz J. Nalepa and
                Roy Fairstein and
                Roxana Radulescu},
    title     = {A Semantic Approach to Decidability in Epistemic Planning},
    booktitle = {{ECAI} 2023 - 26th European Conference on Artificial Intelligence,
                September 30 - October 4, 2023, Krak{\'{o}}w, Poland - Including
                12th Conference on Prestigious Applications of Intelligent Systems
                ({PAIS} 2023)},
    series    = {Frontiers in Artificial Intelligence and Applications},
    volume    = {372},
    pages     = {319--326},
    publisher = {{IOS} Press},
    year      = {2023},
    url       = {https://doi.org/10.3233/FAIA230286},
    doi       = {10.3233/FAIA230286}
}
```

---

##### Related material

+ [Slides](slides.pdf)
