---
title: "Evaluating and Mitigating the Misguidance Effect of Buggy Code in LLM-Generated Unit Tests"
collection: publications
permalink: /publication/2026-issta-misguidance-effect
excerpt: 'Buggy code steers LLMs toward tests that confirm the bug instead of exposing it. We quantify this misguidance effect across 11 LLMs on Defects4J and mitigate it with specification-based test generation.'
date: 2026-07-24
venue: 'ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2026)'
paperurl: 'https://arxiv.org/abs/2607.22883'
arxiv: 'https://arxiv.org/abs/2607.22883'
citation: 'Junda Zhao, Shurui Zhou, and Eldan Cohen. &quot;Evaluating and Mitigating the Misguidance Effect of Buggy Code in LLM-Generated Unit Tests.&quot; <i>ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2026)</i>.'
---

{% include base_path %}

**Junda Zhao**, Shurui Zhou, Eldan Cohen. ISSTA 2026.

LLMs show great promise for automating unit test generation, but the quality of the generated tests can suffer when the model is prompted with buggy code. This paper presents a new metric to quantify the *misguidance effect*, a phenomenon where buggy code steers LLMs toward generating tests that validate its erroneous behavior rather than expose it. Across 318 focal methods from Defects4J and 11 LLMs (13 configurations), prompting with buggy code has a twofold impact: it significantly increases misguided tests that assert the incorrect behavior, while suppressing the generation of effective, bug-finding tests. We corroborate the effect from a model-internal perspective, showing that buggy code skews an LLM's preference toward tests that assert the same erroneous behavior.

To counter this, we introduce a specification-based unit test generation paradigm that replaces the code under test in the prompt with an LLM-generated specification docstring. This paradigm reduces misguided tests while substantially increasing effective tests, improves multi-round, feedback-driven test generation pipelines, and remains applicable to both buggy and bug-free code.

* [arXiv](https://arxiv.org/abs/2607.22883)
* [Replication package on GitHub](https://github.com/drixs2050/EvalAndMitigate) and [archived on Zenodo](https://doi.org/10.5281/zenodo.21428153)
* [Slides]({{ base_path }}/files/zhao-issta2026-misguidance-slides.pdf) and [poster]({{ base_path }}/files/zhao-issta2026-misguidance-poster.pdf) from ISSTA 2026
