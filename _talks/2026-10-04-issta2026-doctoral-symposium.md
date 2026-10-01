---
title: "Accurate Specification Recovery for Effective Test Generation"
collection: talks
type: "Doctoral Symposium talk"
talk_type: "Doctoral Symposium talk"
symposium: true
permalink: /talks/2026-10-04-issta2026-doctoral-symposium
venue: "SPLASH/ISSTA 2026"
date: 2026-10-04
location: "Oakland, California, USA"
---

{% include base_path %}

Talk at the SPLASH/ISSTA 2026 Doctoral Symposium, Sunday, October 4, 2026.

LLM-based unit-test generation has largely been studied under the assumption that the code under test is correct, using coverage or test-correctness metrics that do not directly measure defect detection. When the code under test is buggy, models can be guided toward assertions that encode the faulty behavior, producing tests that confirm rather than reveal defects. Our recent work quantified this misguidance effect and showed that a specification-based approach, which first recovers a behavioral specification of the focal method from its buggy implementation and then generates tests from that specification, can substantially mitigate it. The recovery step itself, however, remains simple, and its specifications are fallible. My dissertation therefore aims to make specification recovery from imperfect code accurate, evidence-driven, and uncertainty-aware, so that it consistently yields effective bug-finding tests.

* [Doctoral Symposium paper]({{ base_path }}/files/zhao-issta2026-doctoral-symposium-paper.pdf)
