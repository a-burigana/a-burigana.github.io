---
title: "Modelling Multi-Agent Epistemic Planning in ASP"
date: 2020-09-21
lastmod: 2024-11-13
tags: ["Epistemic Planning","ASP","Possibilities",]
author: ["Alessandro Burigana", "Francesco Fabiano", "Agostino Dovier", "Enrico Pontelli"]
description: "This paper explores the performances of an ASP model for epistemic planning called PLATO. ICLP, TPLP 2020." 
summary: "This paper explores the performances of an ASP model for epistemic planning called PLATO. The ASP paradigm provides a concise and elegant design of the planner, wrt. other imperative implementations, facilitating the development of formal verification of correctness. The paper shows that the planner has competitive performance results on benchmarks collected from the literature." 
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "Theory and Practice of Logic Programming"

---

---

##### Download

+ [Preprint](https://arxiv.org/abs/2008.03007)
+ [Supplementary material](supplementary.pdf)
+ [Code and data](https://github.com/a-burigana/PLATO)

---

##### Abstract

Designing agents that reason and act upon the world has always been one of the main objectives of the Artificial Intelligence community. While for planning in "simple" domains the agents can solely rely on facts about the world, in several contexts, *e.g.*, economy, security, justice and politics, the mere knowledge of the world could be insufficient to reach a desired goal. In these scenarios, *epistemic reasoning*, *i.e.*, reasoning about agents' beliefs about themselves and about other agents' beliefs, is essential to design winning strategies. This paper addresses the problem of reasoning in multi-agent epistemic settings exploiting declarative programming techniques. In particular, the paper presents an actual implementation of a multi-shot *Answer Set Programming*-based planner that can reason in multi-agent epistemic settings, called PLATO (e**P**istemic mu**L**ti-agent **A**nswer se**T** programming s**O**lver). The ASP paradigm enables a concise and elegant design of the planner, w.r.t. other imperative implementations, facilitating the development of formal verification of correctness. The paper shows how the planner, exploiting an ad-hoc epistemic state representation and the efficiency of ASP solvers, has competitive performance results on benchmarks collected from the literature.

---

##### Citation

Burigana, A., Fabiano, F., Dovier, A., and Pontelli, E. 2020. "Modelling Multi-Agent Epistemic Planning in ASP." *Theory and Practice of Logic Programming, 36th International Conference on Logic Programming Special Issue I*, 20(5):593-608

```BibTeX
@article{journals/tplp/BuriganaFDP2020,
    author       = {Alessandro Burigana and
                    Francesco Fabiano and
                    Agostino Dovier and
                    Enrico Pontelli},
    title        = {Modelling Multi-Agent Epistemic Planning in {ASP}},
    journal      = {Theory and Practice of Logic Programming},
    volume       = {20},
    number       = {5},
    pages        = {593--608},
    year         = {2020},
    url          = {https://doi.org/10.1017/S1471068420000289},
    doi          = {10.1017/S1471068420000289}
}
```

---

##### Related material

+ [Slides](slides.pdf)
