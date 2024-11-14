---
title: "PLATO - ePistemic muLti-agent Answer seT programming sOlver"
date: 2020-02-27
lastmod: 2024-11-14
url: /projects/plato/
tags: ["Epistemic Planner", "Possibilities", "Answer Set Programming"]
author: ["Alessandro Burigana", "Francesco Fabiano"]
description: "ePistemic muLti-agent Answer seT programming sOlver. Solver for epistemic planning problems based on the mA* language."
summary: "PLATO is an Answer Set Programming (ASP) model implementing an epistemic planner that is built on top a fragment of Dynamic Epistemic Logic called $m\\mathcal{A}^*$. The fragment comprises (public and private) ontic actions and (public, private and semi-private) sensing and announcement actions. The planner implements both a Kripke semantics for the fragment and a novel alternative semantics based on objects called *possibilities*. PLATO is implemented using the *clingo* solver for ASP programs, which provides some useful APIs that allow for solving problems in an iterative fashion. In this way, we can try to compute plans of increasing length, akin to a BFS visit. The goal of PLATO is to investigate the practical usability of ASP in the implementation of epistemic planners."
showToc: false
disableAnchoredHeadings: false

---

---

#### Code and data
+ [GitHub repository](https://github.com/a-burigana/PLATO)

---

#### Description

PLATO is an Answer Set Programming (ASP) model implementing an epistemic planner that is built on top a fragment of Dynamic Epistemic Logic called $m\\mathcal{A}^*$. The fragment comprises (public and private) ontic actions and (public, private and semi-private) sensing and announcement actions. The planner implements both a Kripke semantics for the fragment and a novel alternative semantics based on objects called *possibilities*. PLATO is implemented using the *clingo* solver for ASP programs, which provides some useful APIs that allow for solving problems in an iterative fashion. In this way, we can try to compute plans of increasing length, akin to a BFS visit. The goal of PLATO is to investigate the practical usability of ASP in the implementation of epistemic planners.

---

#### Publications
+ [Modelling Multi-Agent Epistemic Planning in ASP.](../../papers/2020-09-21-tplp/) Burigana, A., Fabiano, F., Dovier, A., and Pontelli, E. (TPLP 2020)
