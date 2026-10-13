---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links">
  <a href="https://github.com/Nkluge-correa/Nkluge-correa.github.io/blob/main/_pages/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>

Professional Summary
======
* Author of the book **"[Normative Ethics, Artificial Intelligence, and Value Alignment: From Normative Theory to Engineering Practices](https://link.springer.com/book/10.1007/978-3-032-22150-6)"** (Springer Nature, 2026).
* Accomplished researcher and machine learning engineer with over 10 years of expertise in academia, driving advancements in Applied Ethics and Machine Learning, particularly in the realm of AI Ethics and Low-Resource Languages/NLP.
* Expertise in developing innovative frameworks for trustworthy AI, fostering interdisciplinary collaborations, and mentoring emerging scholars.
* Pioneer in the development of foundation models for low-resource languages.
* Passionate about building open-source projects.
* Prepared to lead in a research and development environment.

Technical Profile
======
During my work, I built a [full stack](https://github.com/Polygl0t/llm-foundry) that powers the development of open language models — from data and tokenizers, through pretraining and alignment, to evaluation — on large HPC systems. During this time, I gained extensive experience in foundation-model training, data management, evaluation, HPC orchestration, and responsible AI tooling.

* **Foundation-model training.** I am familiar with distributed pretraining using a wide range of parallelism and optimization techniques, such as DDP, FSDP2, tensor, sequence and expert (MoE) parallelism, FP8 mixed precision, Flash Attention (up to FA4 on Hopper/Blackwell) and Liger Kernel. I am also familiar with training hybrid attention/state-space architectures. In terms of post-training, I have experience with SFT, DPO, GRPO with verifier-based rewards, and reward-model training.
* **Data, tokenization and synthetic data generation.** I have experience with multi-node corpus pipelines using DataTrove for data preprocessing, tokenization, and quality assurance. I have also worked on the generation of large-scale synthetic corpora, Constitutional AI-style pipelines, and agentic reasoning-trace generation with a stack built on vLLM, DataTrove and smolagents.
* **Evaluation.** I maintain an evaluation stack built on the LM Evaluation Harness, and I am quite familiar with designing, implementing, and running comprehensive evaluation pipelines for language models.
* **HPC and engineering.** I am comfortable working with HPC clusters, specifically clusters managed via SLURM (e.g., JSC JUPITER Booster), and with containerised HTCondor.
* **Core stack:** Python, Bash, SLURM, HTCondor, Git, PyTorch, Hugging Face (Transformers, Tokenizers, Datasets, PEFT, TRL, smolagents), vLLM, SGLang, mergekit, SentencePiece.

Selected Open-Source Projects
======
My open-source work follows the same arc as my research: building open language models for underserved languages, evaluating them rigorously, and developing the ethics and safety tooling that surrounds them. Models and datasets are published on the [Polyglot Hugging Face organisation](https://huggingface.co/Polygl0t) and on my [personal Hugging Face account](https://huggingface.co/nicholasKluge).

**Open models and training infrastructure**

* **[LLM Foundry (Polygl0t)](https://github.com/Polygl0t/llm-foundry)** — Cluster-ready codebase for training and evaluating LLMs, covering data processing, tokenization, pretraining, alignment (SFT/DPO/GRPO), synthetic-data generation and evaluation.
* **[Language Model Evaluation Harness (Polygl0t fork)](https://github.com/Polygl0t/lm-evaluation-harness)** — Evaluation backbone for our models, synced with EleutherAI's harness, along with all the evaluations we have implemented over the years (see branches).
* **[Tucano](https://github.com/Nkluge-correa/Tucano)** and **[TeenyTinyLlama](https://github.com/Nkluge-correa/TeenyTinyLlama)** — Natively pre-trained open Portuguese language models, from tiny to larger scale.

**AI ethics, safety and alignment**

* **[Ethical Problem Solving (EPS)](https://github.com/Nkluge-correa/ethical-problem-solving)** — Framework for developing safe and ethical AI, the outcome of my work at RAIES.
* **[Worldwide AI Ethics (WAIE)](https://github.com/Nkluge-correa/worldwide_AI-ethics)** — Systematic literature review and interactive dashboard of global AI-ethics research.
* **[TeenyTinyCastle](https://github.com/Nkluge-correa/TeenyTinyCastle)** — Educational tools for AI ethics and safety research.

Employment History
======
* **Feb 2026 — present:** Postdoc Researcher at the [Bonn-Aachen International Center for Information Technology (b-it)](https://www.b-it-center.de/) / [CAISA Lab](https://caisa-lab.github.io/), University of Bonn
  * I work as the principal investigator of the Polyglot project, a TRA6-funded initiative developing open-source foundation models and related resources for low-resource languages. I also advise and mentor bachelor's, master's, and PhD students.
  * At the b-it / CAISA Lab, my main areas of research are LLMs (focus on low-resource languages) and alignment. I also work in applied ethics and experimental philosophy.

* **Feb 2024 — Jan 2026:** Postdoc Researcher at the [Center for Science and Thought](https://www.cst.uni-bonn.de/en), University of Bonn
  * At the Center for Science and Thought, I worked on the "Zertifizierte KI" project, one of the KI.NRW flagship projects financed by the Ministry of Economic Affairs, Innovation, Digitalization, and Energy of the State of North Rhine-Westphalia, which seeks to develop certification methods for trustworthy artificial intelligence (AI).

* **Oct 2023 — May 2024**: Research Scholar at University of Bonn
  * I was a PhD research scholar at the University of Bonn. There, I have developed (1) a series of [language models and datasets](https://huggingface.co/collections/nicholasKluge/aira) designed to align large language models, and (2) a series of [open-access educational lectures](https://github.com/Nkluge-correa/TeenyTinyCastle) on how to create ethical and safe ML systems.

* **Jun 2022 — May 2024**: Project Lead at RAIES, Porto Alegre
  * Here, I helped coordinate and develop several research efforts on a multi-stakeholder research network called RAIES ([Network for Ethical and Safe Artificial Intelligence](https://raies.org/)). Primarily, I led:
    * Development of algorithmic impact assessment tools.
    * Development of value-sensitive design tools.
    * Mentoring undergraduate and graduate students in their research.
    * Collaboration with researchers from other universities and institutes to create successful interdisciplinary projects.
  * All this research culminated in a framework called Ethical Problem Solving, as well as the [Responsible AI platform (RAIP)](https://raip-dev.ssolutions.cloud/).

* **Mar 2021 — Apr 2024**: President at AIRES at PUCRS
  * I founded a non-profit organization called AIRES ([AI Robotics Ethics Society](https://www.airespucrs.org/)) at PUCRS, which remains actively engaged in research and policy-making to this day. Here, I helped in:
    * Developing policy research to help shape the governance of AI technologies (examples can be found [here](https://www.airespucrs.org/en/nota-tecnica-frt) and [here](https://www.airespucrs.org/en/nota-tecnica-aires)).
    * Developing [foundational research](https://nkluge-correa.github.io/worldwide_AI-ethics/) in the field of AI Ethics.

* **Mar 2020 — Oct 2022**: Research Scholar at PUCRS
  * I was a research scholar at the Pontifical Catholic University of Rio Grande do Sul (PUCRS, Brazil). During this time, I helped found two organizations: the [AI Robotics Ethics Society at PUCRS](https://airespucrs.org/en/) and the [Network for Ethical and Safe Artificial Intelligence](https://raies.org/?lang=en).

* **Mar 2010 — Dec 2014**: Research Assistant at PUCRS
  * During my bachelor's in Health Sciences, I assisted in studies related to the biomechanics of exercises in microgravity and the effects of zero gravity on human physiology. This work led to co-authorship on [several peer-reviewed publications](https://www.researchgate.net/profile/Nicholas-Correa-2).

Education
======
* Ph.D (Summa cum laude) in Philosophy (Ethics of Artificial Intelligence), University of Bonn — Oct 2022 – May 2024
* Ph.D (Summa cum laude) in Philosophy (Ethics of Artificial Intelligence), Pontifical Catholic University of Rio Grande do Sul — Dec 2019 – May 2024
* M.Sc. in Electrical Engineering (Applied Machine Learning and Digital Signal Processing), Pontifical Catholic University of Rio Grande do Sul — Aug 2015 – Aug 2017
* B.S. in Health Sciences (Applied Biomechanics and Human Physiology), Pontifical Catholic University of Rio Grande do Sul — Mar 2010 – Dec 2014
  
Third-Party Funding
======
* I have secured third-party support from funding bodies in Brazil and Germany, including DAAD, CNPq, FAPERGS, and TRA 6 Sustainable Futures. Most notably:
  * All my graduate studies (MSc and Doctorate) were financed via the award of study grants by agencies like DAAD and CNPq.
  * During my stay at PUCRS, I founded the AI Robotics Ethics Society, a successful non-profit think tank that later gave rise to RAIES (Network for Safe and Ethical AI). The Network was established with a grant of approximately 3 million Reais (~500,000 Euros), awarded to AIRES and the Pontifical Catholic University of Rio Grande do Sul, based on a project proposal I authored during my PhD.
  * During my stay at the University of Bonn, I co-initiated the Polyglot Project with Dr. Aniket Sen—a [TRA6-funded](https://www.uni-bonn.de/en/research-and-teaching/research-profile/transdisciplinary-research-areas/tra-6-sustainable-futures/neu) initiative designed to promote openness and diversity in modern NLP by developing foundation models and related resources for low-resource languages.
  * In May 2026, my research group (Polyglot) applied for compute time and received 4.6 million core-hours at the Jülich Supercomputing Centre (JSC).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Languages
======
* English: Fluent
* Portuguese: Native
* Spanish: Fluent
* German: Basic

Awards
======
* 1st Place "[Marvin's 1 Year Most Interesting Results Competition](https://www.cst.uni-bonn.de/en/en_news/tucano-projekt-gewinnt-1-platz-in-der-most-interesting-results-competition)".
* Honorable Mention for the work performed in *"Dynamic Normativity: Necessary and Sufficient Conditions for Value Alignment"*, [Capes Doctoral Thesis Award 2025](https://www.gov.br/capes/pt-br/assuntos/premios/premio-capes-de-tese/premio-capes-de-tese-documentos-relacionados).

References
======
References available upon request.
  
