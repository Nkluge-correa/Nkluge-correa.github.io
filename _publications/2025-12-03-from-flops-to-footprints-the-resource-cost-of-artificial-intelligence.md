---
title: "From FLOPs to Footprints: The Resource Cost of Artificial Intelligence"
collection: publications
category: manuscripts
permalink: /publication/2025-12-03-from-flops-to-footprints-the-resource-cost-of-artificial-intelligence
excerpt: 'This study quantifies the material footprint of AI training by linking computational workloads to the elemental composition of modern GPUs. By showing how model scale drives heavy‑metal extraction and hardware turnover, it demonstrates that AI progress carries substantial material costs and argues for integrating resource efficiency into future discussions of AI scalability.'
date: 2025-12-03
venue: 'ArXiV'
paperurl: 'https://arxiv.org/abs/2512.04142'
---

**Abstract** 

As computational demands continue to rise, assessing the environmental footprint of AI requires moving beyond energy and water consumption to include the material demands of specialized hardware. This study quantifies the material footprint of AI training by linking computational workloads to physical hardware needs. The elemental composition of the Nvidia A100 SXM 40 GB graphics processing unit (GPU) was analyzed using inductively coupled plasma optical emission spectroscopy, which identified 32 elements. The results show that AI hardware consists of about 90% heavy metals and only trace amounts of precious metals. The elements copper, iron, tin, silicon, and nickel dominate the composition of the GPU by mass. In a multi-step methodology, we integrate these measurements with computational throughput per GPU across varying lifespans, accounting for the computational requirements of training specific AI models across different training-efficiency regimes. Scenario-based analyses reveal that, depending on Model FLOPs Utilization (MFU) and hardware lifespan, training GPT-4 requires between 1,174 and 8,800 A100 GPUs, corresponding to the extraction and eventual disposal of up to 7 tons of toxic elements. Combined software and hardware optimization strategies can reduce material demands: increasing MFU from 20% to 60% lowers GPU requirements by 67%, while extending lifespan from 1 to 3 years yields comparable savings; implementing both measures together reduces GPU needs by up to 93%. Our findings highlight that incremental performance gains, such as those observed between GPT-3.5 and GPT-4, come at disproportionately high material costs. The study underscores the need to incorporate material resource considerations into discussions of AI scalability, emphasizing that future progress in AI must align with principles of resource efficiency and environmental responsibility.

**BibTeX**

```bibtex
@article{falk2025flops,
  title={From FLOPs to Footprints: The Resource Cost of Artificial Intelligence},
  author={Falk, Sophia and Corr{\^e}a, Nicholas Kluge and Luccioni, Sasha and Biber-Freudenberger, Lisa and van Wynsberghe, Aimee},
  journal={arXiv preprint arXiv:2512.04142},
  year={2025}
}
```
