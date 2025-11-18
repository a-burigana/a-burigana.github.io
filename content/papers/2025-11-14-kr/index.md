---
title: "Depth-Bounded Epistemic Planning"
date: 2025-11-14
lastmod: 2025-11-18
tags: ["Epistemic Planning","Dynamic Epistemic Logic","Bounded Bisimulations","Bisimulation Contractions", "DAEDALUS"]
author: ["Thomas Bolander", "Alessandro Burigana", "Marco Montali"]
description: "This paper introduces the Iterative Bound-Deepening Search (IBDS) algorithm for epistemic planning, showing theoretical results and effective empirical performances. KR 2025."
summary: "We propose a novel algorithm for epistemic planning based on dynamic epistemic logic (DEL). The novelty is that we limit the depth of reasoning of the planning agent to an upper bound $b$, meaning that the planning agent can only reason about higher-order knowledge to at most (modal) depth $b$. We then compute a plan requiring the lowest reasoning depth by iteratively incrementing the value of $b$. The algorithm relies at its core on a new type of \"canonical\" $b$-bisimulation contraction that guarantees unique minimal models by construction. This yields smaller states wrt. standard bisimulation contractions, and enables to efficiently check for visited states. We show soundness and completeness of our planning algorithm, under suitable bounds on reasoning depth, and that, for a bound $b$, it runs in $(b{+}1)$-EXPTIME. We implement the algorithm in a novel epistemic planner, DAEDALUS, and compare it to the EFP 2.0 planner on several benchmarks from the literature, showing effective performance improvements."
editPost:
    URL: "https://doi.org/10.24963/kr.2025/70"
    Text: "Proceedings of the 22nd International Conference on Principles of Knowledge Representation and Reasoning, KR 2025"

---

---

##### Download

+ [Paper](https://doi.org/10.24963/kr.2025/70)

---

##### Abstract

We propose a novel algorithm for epistemic planning based on dynamic epistemic logic (DEL). The novelty is that we limit the depth of reasoning of the planning agent to an upper bound $b$, meaning that the planning agent can only reason about higher-order knowledge to at most (modal) depth $b$. We then compute a plan requiring the lowest reasoning depth by iteratively incrementing the value of $b$. The algorithm relies at its core on a new type of "canonical" $b$-bisimulation contraction that guarantees unique minimal models by construction. This yields smaller states wrt. standard bisimulation contractions, and enables to efficiently check for visited states. We show soundness and completeness of our planning algorithm, under suitable bounds on reasoning depth, and that, for a bound $b$, it runs in $(b{+}1)$-EXPTIME. We implement the algorithm in a novel epistemic planner, DAEDALUS, and compare it to the EFP 2.0 planner on several benchmarks from the literature, showing effective performance improvements.

---

##### Citation

Bolander, T., Burigana, A., and Montali, M. 2025. "Depth-Bounded Epistemic Planning", *Proceedings of the 22nd International Conference on Principles of Knowledge Representation and Reasoning, KR 2025, Melbourne, Australia, November 11-17, 2025*, 729--739. https://doi.org/10.24963/kr.2025/70.

```BibTeX
@inproceedings{conf/kr/BolanderBM2025,
    title     = {{Depth-Bounded Epistemic Planning}},
    author    = {Bolander, Thomas and Burigana, Alessandro and Montali, Marco},
    booktitle = {{Proceedings of the 22nd International Conference on Principles of Knowledge Representation and Reasoning}},
    pages     = {729--739},
    year      = {2025},
    month     = {10},
    doi       = {10.24963/kr.2025/70},
    url       = {https://doi.org/10.24963/kr.2025/70},
  }
```

---

##### Related material

+ [Slides](slides.pdf)
