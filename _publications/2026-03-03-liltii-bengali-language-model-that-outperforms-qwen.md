---
title: "LilTii: A 0.6B Bengali Language Model that Outperforms Qwen"
collection: publications
category: manuscripts
permalink: /publication/2026-03-03-liltii-bengali-language-model-that-outperforms-qwen
excerpt: 'This blog post introduces LilTii, a 0.6B-parameter Bengali language model trained from scratch to address the gap in NLP resources for low-resource languages. We compiled a high-quality Bengali corpus using heuristic and learned filtering, supplemented with curated English data for bilingual augmentation. LilTii consistently outperforms similarly sized multilingual models such as Qwen2.5-0.5B and Qwen3-0.6B across various Bengali benchmarks, demonstrating that well-designed language-specific pretraining can rival large multilingual models at the sub-billion-parameter range.'
date: 2026-03-03
venue: 'Hugging Face Blog'
paperurl: "https://huggingface.co/blog/Polygl0t/liltii"
---

**Abstract** 

Big multilingual foundation models pretty much run the show in NLP right now — but that dominance has also made language inequality worse. Low-resource languages often get the short end of the stick. In this work, we introduce LilTii, a 0.6B-parameter Bengali language model trained completely from scratch to help close that gap. Unlike earlier Bengali models that simply continue training from large, opaque multilingual models, LilTii is built through a fully transparent, reproducible pipeline. It's specifically designed to work well even in limited-compute environments. To make this happen, we compiled a high-quality Bengali corpus using both heuristic and learned filtering (LLM-as-a-judge). We supplemented it with carefully curated English data for bilingual augmentation. Using this dataset, we experiment with different training recipes for small-scale Bengali models. Across a wide range of Bengali benchmarks, LilTii consistently outperforms similarly sized multilingual models such as Qwen2.5-0.5B and Qwen3-0.6B. The takeaway? Maybe there is still room for pre-training in the small-scale/low-resource language scene.

**BibTeX**

```bibtex
@misc{fatimah2026liltii,
  title={{LilTii: A 0.6B Bengali Language Model that Outperforms Qwen}},
  author={Shiza Fatimah and Aniket Sen and Sophia Falk and Florian Mai and Lucie Flek and Nicholas Kluge Corr{\^e}a},
  year={2026},
  howpublished={\url{https://hf.co/blog/Polygl0t/liltii}}
}
```
