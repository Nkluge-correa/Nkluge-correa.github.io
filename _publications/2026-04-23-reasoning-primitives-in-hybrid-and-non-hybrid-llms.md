---
title: "Reasoning Primitives in Hybrid and Non-Hybrid LLMs"
collection: publications
category: manuscripts
permalink: /publication/2026-04-23-reasoning-primitives-in-hybrid-and-non-hybrid-llms
excerpt: 'This paper explores reasoning primitives in hybrid and non-hybrid large language models, focusing on recall and state-tracking capabilities. We evaluate matched Olmo3 transformer and hybrid models on tasks that require both primitives, finding that reasoning augmentation extends the effective operating range of models. The hybrid model shows greater robustness to increasing sequential dependence, while the transformer model degrades sharply beyond a certain difficulty threshold.'
date: 2026-04-23
venue: 'ArXiV'
paperurl: "https://arxiv.org/abs/2604.21454"
---

**Abstract** 

Reasoning in large language models is often treated as a monolithic capability, but its observed gains may arise from more basic operations. We study reasoning through two such primitives, recall and state-tracking, and ask whether hybrid architectures that combine attention-based retrieval with recurrent state updates are better suited than attention-only models for tasks that jointly require both. Using matched Olmo3 transformer and hybrid models in instruction-tuned and reasoning-augmented variants, we evaluate these models on a set of controlled tasks involving a mixture of state-tracking and recall primitives, state-based recall. Across tasks, we notice that reasoning augmentation provides the largest overall improvement, substantially extending the range of difficulty over which models remain effective. We also notice that in certain tasks, the hybrid reasoning model remains substantially more robust as sequential dependence increases. In contrast, the transformer reasoning model degrades sharply in performance as task difficulty increases beyond a given threshold. These results suggest that reasoning tokens and architectural inductive biases contribute at different levels of the computational process: explicit reasoning can expand a model's effective operating range, but its benefit depends on how well the underlying architecture supports persistent state propagation. Given the small size of our case study, which involves a limited set of models and tasks, we present these findings as suggestive rather than conclusive and leave broader validation across model families, scales, and task variations to future work.

**BibTeX**

```bibtex
@misc{rawat2026reasoningprimitiveshybridnonhybrid,
      title={Reasoning Primitives in Hybrid and Non-Hybrid LLMs}, 
      author={Shivam Rawat and Lucie Flek and Florian Mai and Nicholas Kluge Corrêa},
      year={2026},
      eprint={2604.21454},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2604.21454}, 
}
```
