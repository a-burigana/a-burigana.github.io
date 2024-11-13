---
title: "Glocal Conformance Checking"
date: 2024-09-02
lastmod: 2024-11-12
tags: ["Conformance Checking","Collaborative Processes","Local Alignments", "Data Petri Nets"]
author: ["Alessandro Burigana", "Alessandro Gianola", "Marco Montali", "Sarah Winkler"]
description: "This paper presents EFP 2.0, a multi-agent epistemic planner based on an alternative state representations called possibilities. ICAPS 2020."
summary: "Conformance checking is a process mining task where observed process executions are compared with the conduct prescribed by a process model. Even in the case where multiple parties interact in the process, it is typically assumed that the process itself provides a monolithic, global description of the overall, expected behaviour. However, it may very well be the case that such a global process is not explicitly available, and that each agent comes with its own local view of the process, while the overall behaviour is only be implicitly obtained by composing such local views. In this paper, we provide for the first time a formal framework for *glocal conformance checking*, where a global observed trace of a multi-party process is related to local Data Petri nets, each representing the subjective view of each participating agent. We formulate conformance checking in this multi-agent setting as an alignment problem, and show how it can be tackled by \"acting locally, and thinking globally\", that is, pairing local alignments with a suitable global compatibility condition. We then observe that in this setting, cost functions must take the context of activities in the global trace into account, which is realised through a new schema of regular expression-based cost functions. We pair the foundational investigation of the problem with a proof-of-concept SMT-based implementation."
editPost:
    URL: "https://doi.org/10.1007/978-3-031-70396-6_5"
    Text: "Proceedings of the 30th International Conference on Automated Planning and Scheduling, ICAPS 2020"

---

---

##### Download

+ [Paper](https://link.springer.com/content/pdf/10.1007/978-3-031-70396-6.pdf)

---

##### Abstract

Conformance checking is a process mining task where observed process executions are compared with the conduct prescribed by a process model. Even in the case where multiple parties interact in the process, it is typically assumed that the process itself provides a monolithic, global description of the overall, expected behaviour. However, it may very well be the case that such a global process is not explicitly available, and that each agent comes with its own local view of the process, while the overall behaviour is only be implicitly obtained by composing such local views. In this paper, we provide for the first time a formal framework for *glocal conformance checking*, where a global observed trace of a multi-party process is related to local Data Petri nets, each representing the subjective view of each participating agent. We formulate conformance checking in this multi-agent setting as an alignment problem, and show how it can be tackled by "acting locally, and thinking globally", that is, pairing local alignments with a suitable global compatibility condition. We then observe that in this setting, cost functions must take the context of activities in the global trace into account, which is realised through a new schema of regular expression-based cost functions. We pair the foundational investigation of the problem with a proof-of-concept SMT-based implementation.

---

##### Citation

Burigana, A., Gianola, A., Montali, M., and Winkler, S. 2024. "Glocal Conformance Checking", *Business Process Management - 22nd International Conference, {BPM} 2024, Krakow, Poland, September 1-6, 2024, Proceedings*, Vol. 14940: 75--92. https://doi.org/10.1007/978-3-031-70396-6_5.

```BibTeX
@inproceedings{DBLP:conf/bpm/BuriganaGMW24,
    author    = {Alessandro Burigana and
                 Alessandro Gianola and
                 Marco Montali and
                 Sarah Winkler},
    editor    = {Andrea Marrella and
                 Manuel Resinas and
                 Mieke Jans and
                 Michael Rosemann},
    title     = {Glocal Conformance Checking},
    booktitle = {Business Process Management - 22nd International Conference, {BPM}
                 2024, Krakow, Poland, September 1-6, 2024, Proceedings},
    series    = {Lecture Notes in Computer Science},
    volume    = {14940},
    pages     = {75--92},
    publisher = {Springer},
    year      = {2024},
    url       = {https://doi.org/10.1007/978-3-031-70396-6\_5},
    doi       = {10.1007/978-3-031-70396-6\_5}
}
```

---

##### Related material

+ [Slides]()
