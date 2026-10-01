---
permalink: /
title: ""
excerpt: "Junda Zhao is a PhD candidate at the University of Toronto working on reliable testing and verification for AI coding agents. Seeking a postdoctoral position starting in late 2027."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

About me
======

I am a PhD candidate at the University of Toronto working on reliable testing and verification for AI coding agents in production. I am advised by Prof. [Eldan Cohen](https://www.mie.utoronto.ca/faculty_staff/eldan-cohen/) in the [OptiMaL Lab](https://optimal.mie.utoronto.ca/) ([Mechanical & Industrial Engineering](https://www.mie.utoronto.ca/)) and work closely with Prof. [Shurui Zhou](https://www.eecg.toronto.edu/~shuruiz/) (Electrical & Computer Engineering).

**I am seeking a postdoctoral position starting in late 2027.** My [CV (PDF)]({{ base_path }}/files/jundazhao_CV.pdf) and a [three-page research overview]({{ base_path }}/files/zhao-issta2026-doctoral-symposium-paper.pdf) are here. Contact: junda.zhao (at) mail.utoronto.ca.
{: .notice--success}

Software developers have long quoted Linus Torvalds: "Talk is cheap. Show me the code." With AI coding agents, code itself has become cheap: agents write implementations, fix bugs, and generate tests in seconds. The harder request is now "show me it works". When an agent says "the job is completed", what evidence should we require before we take its word, and how can that evidence be produced reliably and at scale?

My research explores this question through software testing and verification. Our work has shown that LLM-based test generation is prone to being misguided by buggy code, and that the proxy metrics widely used to evaluate it can fail to reflect how effective the generated tests really are; the latter received an ACM SIGSOFT Distinguished Paper Award at ISSTA 2026. One approach I focus on is specification-based testing: how to reliably recover what code is supposed to do, how to turn that intent into tests that expose bugs, and how such validation can fit into real development workflows and improve how people collaborate with AI coding tools.

Earlier, I worked on code summarization with pre-trained language models, and as an undergraduate on geometry processing and physics-based animation with Prof. [Alec Jacobson](https://www.cs.toronto.edu/~jacobson/) and Prof. [David Levin](https://www.diwlevin.com/).

News
======

* **Oct 2026.** At [SPLASH/ISSTA 2026](https://conf.researchr.org/home/issta-2026) in Oakland: two research talks (Oct 9), two posters (Oct 7), and a Doctoral Symposium talk (Oct 4). Happy to meet.
* **Sep 2026.** Our ISSTA 2026 replicability study received an **ACM SIGSOFT Distinguished Paper Award**.
* **Jul 2026.** Two papers accepted at ISSTA 2026; preprints and replication packages are public.
* **Nov 2025.** Presented Variational Prefix Tuning at ASE 2025 (Journal-First), Seoul.
* **May 2025.** Variational Prefix Tuning published in the Journal of Systems and Software.

Selected publications
======

**Do Coverage and Mutation Scores of LLM-Generated Test Suites Correlate with Their Effectiveness? (Replicability Study)**<br/>
**Junda Zhao**, Shurui Zhou, Eldan Cohen<br/>
*ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2026)*<br/>
**ACM SIGSOFT Distinguished Paper Award**<br/>
On 100,000+ LLM-generated tests, coverage and mutation scores track bug detection only when the code can be assumed bug-free.<br/>
[arXiv](https://arxiv.org/abs/2607.22880) · [Replication package](https://github.com/drixs2050/Cov_mut_bug_detect_correlation) · [Slides]({{ base_path }}/files/zhao-issta2026-coverage-mutation-slides.pdf) · [Poster]({{ base_path }}/files/zhao-issta2026-coverage-mutation-poster.pdf)

**Evaluating and Mitigating the Misguidance Effect of Buggy Code in LLM-Generated Unit Tests**<br/>
**Junda Zhao**, Shurui Zhou, Eldan Cohen<br/>
*ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2026)*<br/>
Buggy code steers LLMs toward tests that certify the bug; generating tests from a recovered specification instead counters this.<br/>
[arXiv](https://arxiv.org/abs/2607.22883) · [Replication package](https://github.com/drixs2050/EvalAndMitigate) · [Slides]({{ base_path }}/files/zhao-issta2026-misguidance-slides.pdf) · [Poster]({{ base_path }}/files/zhao-issta2026-misguidance-poster.pdf)

**Variational Prefix Tuning for Diverse and Accurate Code Summarization Using Pre-trained Language Models**<br/>
**Junda Zhao**, Yuliang Song, Eldan Cohen<br/>
*Journal of Systems and Software, 2025*<br/>
Parameter-efficient tuning that lets code language models produce diverse yet accurate summaries.<br/>
[Paper](https://doi.org/10.1016/j.jss.2025.112493) · [Code](https://github.com/drixs2050/VPT) · [Slides]({{ base_path }}/files/zhao-ase2025-vpt-slides.pdf) · [Poster]({{ base_path }}/files/zhao-ase2025-vpt-poster.pdf)

The full list is on the [publications page]({{ base_path }}/publications/) and on [Google Scholar](https://scholar.google.ca/citations?hl=en&user=B57wJ9IAAAAJ).

Talks and posters
======

* **Do Coverage and Mutation Scores of LLM-Generated Test Suites Correlate with Their Effectiveness? (Replicability Study).** Research-track talk, ISSTA 2026, Oakland, California, October 9, 2026, with a poster at the SPLASH/ISSTA poster session on October 7. [Slides]({{ base_path }}/files/zhao-issta2026-coverage-mutation-slides.pdf) · [Poster]({{ base_path }}/files/zhao-issta2026-coverage-mutation-poster.pdf)
* **Evaluating and Mitigating the Misguidance Effect of Buggy Code in LLM-Generated Unit Tests.** Research-track talk, ISSTA 2026, Oakland, California, October 9, 2026, with a poster at the SPLASH/ISSTA poster session on October 7. [Slides]({{ base_path }}/files/zhao-issta2026-misguidance-slides.pdf) · [Poster]({{ base_path }}/files/zhao-issta2026-misguidance-poster.pdf)
* **Variational Prefix Tuning for Diverse and Accurate Code Summarization Using Pre-trained Language Models.** Journal-First presentation and poster, ASE 2025, Seoul, South Korea, November 18, 2025. [Slides]({{ base_path }}/files/zhao-ase2025-vpt-slides.pdf) · [Poster]({{ base_path }}/files/zhao-ase2025-vpt-poster.pdf)
* **Accurate Specification Recovery for Effective Test Generation.** Doctoral Symposium talk, SPLASH/ISSTA 2026, Oakland, California, October 4, 2026. [Paper]({{ base_path }}/files/zhao-issta2026-doctoral-symposium-paper.pdf)

Earlier projects
======

Undergraduate work in graphics, simulation, and vision is on the [projects page]({{ base_path }}/projects/).

Contact
======

* Email: junda.zhao (at) mail.utoronto.ca
* [Google Scholar](https://scholar.google.ca/citations?hl=en&user=B57wJ9IAAAAJ) · [GitHub](https://github.com/drixs2050) · [ORCID](https://orcid.org/0000-0003-4978-4128) · [LinkedIn](https://www.linkedin.com/in/junda-zhao-96b821187/)
* Department of Mechanical & Industrial Engineering, University of Toronto, Toronto, ON, Canada
