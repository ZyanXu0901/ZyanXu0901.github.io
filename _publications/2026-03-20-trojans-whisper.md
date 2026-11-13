---
title: "Trojan's Whisper: Stealthy Manipulation of OpenClaw through Injected Bootstrapped Guidance"
collection: publications
category: preprints
permalink: /publication/2026-03-20-trojans-whisper
excerpt: 'This work identifies guidance injection in OpenClaw: adversarial narratives embedded in bootstrap guidance files can steer autonomous agents toward harmful actions. Evaluation with ORE-Bench examines attack effectiveness across six LLM backends and limitations of existing skill scanners.'
date: 2026-03-20
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/pdf/2603.19974'
citation: 'Fazhong Liu, Zhuoyan Chen, Tu Lan, Haozhen Tan, Zhenyu Xu, Xiang Li, Guoxing Chen, Yan Meng, and Haojin Zhu. "Trojan''s Whisper: Stealthy Manipulation of OpenClaw through Injected Bootstrapped Guidance." arXiv:2603.19974, 2026. doi: 10.48550/arXiv.2603.19974.'
---

Fazhong Liu, Zhuoyan Chen, Tu Lan, Haozhen Tan, **Zhenyu Xu**, Xiang Li, Guoxing Chen, Yan Meng, and Haojin Zhu.

This paper studies **guidance injection**, an attack surface in OpenClaw's extensible skill ecosystem. Adversarial narratives embedded in bootstrap guidance files frame harmful actions as routine practices and influence subsequent agent behavior.

Using ORE-Bench, the study evaluates 26 malicious skills across 13 attack categories, 52 natural user prompts, and six LLM backends. Reported attack success rates range from 16.0% to 64.2%, while 94% of the malicious skills evade the evaluated static and LLM-based scanners. The findings motivate capability isolation, runtime policy enforcement, and transparent guidance provenance.

[arXiv abstract](https://arxiv.org/abs/2603.19974) | [PDF](https://arxiv.org/pdf/2603.19974) | [DOI](https://doi.org/10.48550/arXiv.2603.19974)
