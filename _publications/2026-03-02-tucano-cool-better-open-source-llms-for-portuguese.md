---
title: "Tucano 2 Cool: Better Open Source LLMs for Portuguese"
collection: publications
category: manuscripts
permalink: /publication/2026-03-03-tucano-cool-better-open-source-llms-for-portuguese
excerpt: 'This study introduces Tucano 2, a suite of open-source large language models (LLMs) with 0.5-3.7 billion parameters, designed to fill gaps in Portuguese LLM development. We extend our dataset, GigaVerbo-v2, and introduce new synthetic and post-training datasets to enhance training across various domains. Through extensive ablation studies, we develop pretraining and continual pretraining recipes that achieve state-of-the-art performance on Portuguese-language benchmarks.'
date: 2026-03-03
venue: 'ArXiV'
paperurl: "https://arxiv.org/abs/2603.03543"
---

**Abstract** 

We present Tucano 2, a fully open suite of large language models (LLMs) with 0.5-3.7 billion parameters, designed to address certain gaps in open-source development for Portuguese LLMs. Following our previous works, we now extend our dataset, GigaVerbo-v2, to a new degree of quality and scale, while also introducing a new synthetic dataset, GigaVerbo-v2 Synth, aimed at filling missing gaps in GigaVerbo-v2, and two post-training datasets, GigaVerbo-v2 SFT and GigaVerbo-v2 Preferences, that allow Portuguese LLMs to be trained in domains like retrieval augmented generation, coding, tool use, chain-of-thought reasoning, and many other domains of interest. Through extensive ablation studies, we design both pretraining and continual pretraining recipes for the Tucano 2 suite (Base, Instruct, and Think), which achieve state-of-the-art performance on several Portuguese-language modeling benchmarks. We also extend and refine the evaluation harness introduced in our earlier work, yielding a comprehensive evaluation suite that provides strong signals across different pretraining, continual pretraining, and post-training regimes. All artifacts associated with Tucano 2 are openly released, including training recipes, logs, and source code, ensuring that our work is reproducible, accessible, and extendable by the broader Portuguese NLP community.

**BibTeX**

```bibtex
@misc{correa2026tucano2cool,
      title={{Tucano 2 Cool: Better Open Source LLMs for Portuguese}}, 
      author={Nicholas Kluge Corr{\^e}a and Aniket Sen and Shiza Fatimah and Sophia Falk and Lennard Landgraf and Julia Kastner and Lucie Flek},
      year={2026},
      eprint={2603.03543},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2603.03543}, 
}
```
