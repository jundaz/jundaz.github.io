---
title: "Variational Prefix Tuning for Diverse and Accurate Code Summarization Using Pre-trained Language Models"
collection: publications
permalink: /publication/2025-jss-variational-prefix-tuning
excerpt: 'A parameter-efficient method that lets pre-trained language models of code generate diverse yet accurate sets of code summaries, by integrating a conditional variational autoencoder as a modular prefix component.'
date: 2025-11-01
venue: 'Journal of Systems and Software, 2025'
paperurl: 'https://doi.org/10.1016/j.jss.2025.112493'
citation: 'Junda Zhao, Yuliang Song, and Eldan Cohen. &quot;Variational Prefix Tuning for Diverse and Accurate Code Summarization Using Pre-trained Language Models.&quot; <i>Journal of Systems and Software</i>, Volume 229, November 2025.'
---

{% include base_path %}

**Junda Zhao**, Yuliang Song, Eldan Cohen. Journal of Systems and Software, 2025. Presented in the Journal-First track of ASE 2025, Seoul, South Korea.

Pre-trained language models of code generate a single summary for a code snippet, although many valid summaries usually exist. Variational Prefix Tuning (VPT) integrates a conditional variational autoencoder (CVAE) framework into existing pre-trained transformer models as a modular component. Sampled latent codes are injected as continuous prefixes during decoding, so that the model can produce multiple diverse yet accurate summaries without costly retraining of the backbone. A bi-criteria reranking method then selects the set of summaries that best balances diversity and accuracy.

* [Paper (open access)](https://doi.org/10.1016/j.jss.2025.112493)
* [Code](https://github.com/drixs2050/VPT)
* [Slides]({{ base_path }}/files/zhao-ase2025-vpt-slides.pdf) and [poster]({{ base_path }}/files/zhao-ase2025-vpt-poster.pdf) from ASE 2025
