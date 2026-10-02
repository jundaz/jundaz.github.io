---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Seeking a postdoctoral position starting in late 2027. [CV (PDF)]({{ base_path }}/files/jundazhao_CV.pdf) · junda.zhao (at) mail.utoronto.ca
{: .notice--success}

Education
======
* PhD candidate in Mechanical and Industrial Engineering, University of Toronto, 2022 to present
  * Passed the doctoral qualifying examination; expected completion in 2027
  * Dissertation (in progress): *Accurate Specification Recovery for Effective Test Generation*
  * Advisor: Prof. Eldan Cohen, Optimization and Machine Learning (OptiMaL) Lab
  * Close collaboration with Prof. Shurui Zhou (Electrical & Computer Engineering)
* Honours Bachelor of Science in Computer Science, University of Toronto, 2021

Awards
======
* ACM SIGSOFT Distinguished Paper Award, ISSTA 2026, for *Do Coverage and Mutation Scores of LLM-Generated Test Suites Correlate with Their Effectiveness? (Replicability Study)*
* Ontario Graduate Scholarship (OGS), 2024 to 2025

Publications
======
  <ul>{% for post in site.publications reversed %}{% unless post.symposium %}
    {% include archive-single-cv.html %}
  {% endunless %}{% endfor %}
  {% for post in site.publications reversed %}{% if post.symposium %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

Research experience
======
* 2022 to present: PhD candidate, OptiMaL Lab, University of Toronto
  * Reliable testing and verification for AI coding agents, with a focus on LLM-based unit test generation
  * Specification-based testing: recovering the intended behavior of code that may be buggy, and generating tests from it
  * Evaluation of LLM-generated tests and of the metrics used to judge them
  * Code summarization with pre-trained language models of code
  * Public replication packages for published work
* 2021 to 2022: Research Assistant, Dynamic Graphics Project (DGP) Lab, University of Toronto
  * Geometric stylization and feature-grid based texture synthesis and transfer
* Undergraduate projects with Prof. Alec Jacobson (geometry processing) and Prof. David Levin (physics-based animation)

Talks and posters
======
  <ul>{% for post in site.talks reversed %}{% unless post.symposium %}
    {% include archive-single-talk-cv.html %}
  {% endunless %}{% endfor %}
  {% for post in site.talks reversed %}{% if post.symposium %}
    {% include archive-single-talk-cv.html %}
  {% endif %}{% endfor %}</ul>

Teaching
======
* Teaching Assistant, MIE1517: Introduction to Deep Learning (graduate course), University of Toronto, Winter 2024, and Fall and Winter terms since Fall 2024
* Teaching Assistant, MIE370: Introduction to Machine Learning (undergraduate course), University of Toronto, Fall 2025
* Teaching Assistant, MIE350: Design and Analysis of Information Systems (undergraduate course), University of Toronto, Fall 2022

Skills
======
* Software testing and analysis: LLM-based test generation and evaluation on Defects4J; coverage and mutation analysis with JaCoCo, PIT, and CodeCover
* Machine learning: PyTorch, NumPy, OpenCV, large language models, deep generative models, statistical analysis and modeling
* Programming: Python, C++ (Eigen, libigl), MATLAB; Java for test generation and evaluation (JUnit, Defects4J)
* Languages: fluent in English and Mandarin

Professional experience
======
* 2019 to 2020: Junior Identity and Access Management Analyst, Information Technology Services, University of Toronto
  * Built and maintained a database system for tracking, parsing, and analyzing network access and activity information for students, faculty, and staff
