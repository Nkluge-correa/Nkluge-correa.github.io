---
title: "Raising Bars, Not Parameters: LilMoo Compact Language Model for Hindi"
collection: publications
category: manuscripts
permalink: /publication/2026-03-03-lilmoo-compact-language-model-for-hindi
excerpt: 'This study introduces LilMoo, a 0.6-billion-parameter Hindi language model trained entirely from scratch to address the gap in NLP resources for low-resource languages. We construct a high-quality Hindi corpus (GigaLekh) filtered through both heuristic and learned methods, complemented by bilingual augmentation with curated English data. LilMoo consistently outperforms comparably sized multilingual baselines, demonstrating that well-designed language-specific pretraining can rival large multilingual models at the sub-billion-parameter range.'
date: 2026-03-03
venue: 'ArXiV'
paperurl: "https://arxiv.org/abs/2603.03508"
---

**Abstract** 

The dominance of large multilingual foundation models has widened linguistic inequalities in Natural Language Processing (NLP), often leaving low-resource languages underrepresented. This paper introduces LilMoo, a 0.6-billion-parameter Hindi language model trained entirely from scratch to address this gap. Unlike prior Hindi models that rely on continual pretraining from opaque multilingual foundations, LilMoo is developed through a fully transparent and reproducible pipeline optimized for limited compute environments. We construct a high-quality Hindi corpus (GigaLekh) filtered through both heuristic and learned (LLM-as-a-judge) methods, complemented by bilingual augmentation with curated English data. Using this dataset, we explore various training recipes for small-scale language models. Across comprehensive evaluation suites, LilMoo consistently outperforms comparably sized multilingual baselines such as Qwen2.5-0.5B and Qwen3-0.6B, demonstrating that well-designed language-specific pretraining can rival large multilingual models at the sub-billion-parameter range.

**BibTeX**

```bibtex
@misc{shiza2026lilmoo,
      title={{Raising Bars, Not Parameters: LilMoo Compact Language Model for Hindi}}, 
      author={Shiza Fatimah and Aniket Sen and Sophia Falk and Florian Mai and Lucie Flek and Nicholas Kluge Corr{\^e}a},
      year={2026},
      eprint={2603.03508},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2603.03508}, 
}
```
