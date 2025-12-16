---
title: "Tucano: a series of decoder-transformers natively pre-trained in Portuguese"
excerpt: "To stimulate the future of open development of neural text generation in Portuguese, we present both GigaVerbo, a concatenation of deduplicated Portuguese text corpora amounting to 200 billion tokens, and Tucano, a series of decoder-transformers natively pre-trained in Portuguese.<br><br><img src='https://raw.githubusercontent.com/Nkluge-correa/Tucano/main/img/logo.png' width='400'>"
collection: portfolio
---

<p>
<a href="https://doi.org/10.1016/j.patter.2025.101325" target="_blank">
    <img src="https://img.shields.io/badge/Patterns-10.1016/j.patter.2025.101325-blue" alt="Patterns">
</a><br>
<a href="https://arxiv.org/abs/2411.07854" target="_blank">
    <img src="https://img.shields.io/badge/arXiv-2411.07854-009C3B.svg" alt="arXiv">
</a>
<a href="https://huggingface.co/TucanoBR" target="_blank">
    <img src="https://img.shields.io/badge/HF%20Models-Tucano-FFDF00.svg" alt="HF Link">
</a>
<a href="https://github.com/Nkluge-correa/Tucano/blob/main/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/License-Apache-002776.svg" alt="License: Apache 2.0">
</a>
<a href="https://doi.org/10.5281/zenodo.15471165">
  <img src="https://zenodo.org/badge/885940738.svg" alt="DOI">
</a>
</p>

To stimulate the future of open development of neural text generation in Portuguese, we present both **GigaVerbo**, a concatenation of deduplicated Portuguese text corpora amounting to 200 billion tokens, and **Tucano**, a series of decoder-transformers natively pre-trained in Portuguese. All byproducts of our study, including the source code used for training and evaluation, are openly released on GitHub and Hugging Face.

## News 🚀

**📣 Tucanos are fun, but we also want to help build tools for other languages! New releases of the Tucano project, as well as new resources for other low-resource languages, will soon be available in our new organization: [Polyglot](https://huggingface.co/Polygl0t)! Polyglot is a research project from the [University of Bonn](https://www.uni-bonn.de/en), where we seek to aid in the development of foundation models for low-resource languages. So, if you like Tucanos, go follow Polyglot to stay updated with our new releases.**


- [24/07/2025] Peer-reviewed article "[Tucano: Advancing Neural Text Generation for Portuguese](https://doi.org/10.1016/j.patter.2025.101325)" is published in Patterns, with all models and datasets released on [Hugging Face](https://huggingface.co/TucanoBR).
- [13/01/2025] We release ViTucano, a pair of vision assistants natively pretrained in Portuguese ([ViTucano-1b5-v1](https://huggingface.co/TucanoBR/ViTucano-1b5-v1), [ViTucano-2b8-v1](https://huggingface.co/TucanoBR/ViTucano-2b8-v1)).
- [13/01/2025] We release the datasets used to pretrain and fine-tune the ViTucano models: [ViTucano-Pretrain](https://huggingface.co/datasets/TucanoBR/ViTucano-Pretrain) and [ViTucano-SFT](https://huggingface.co/datasets/TucanoBR/ViTucano-SFT).
- [29/11/2024] Tucano is mentioned on Deutsche Welle: "[Cientistas criam maior banco de dados em português para IA](https://www.dw.com/pt-br/pesquisadores-da-alemanha-criam-maior-banco-de-dados-p%C3%BAblico-em-portugu%C3%AAs-para-ia/a-70917082)".
- [27/11/2024] Tucano video presentation at the C4AI (USP) [available on [YouTube](https://www.youtube.com/watch?v=BscOHn54ld8)].
- [12/11/2024] "[Tucano: Advancing Neural Text Generation for Portuguese](https://arxiv.org/abs/2411.07854)" is published as a preprint on ArXiv, with all models and datasets released on [Hugging Face](https://huggingface.co/TucanoBR).

## Community Contributions 🤝

- Demo on how to run inference on ViTucano 👉 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/110_Gtjgu4pldRQP864_Y-rSm2VhyW7Li)

- Demo on how to run inference on Tucano 👉 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Qf2DsFOFDA7RKkamI-tH3OregtOlZ8Cz)

- Demo on how to create a simple Chat UI for Tucano using Gradio 🚀 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fEW10CXksMfMv1veLr22OESwDs6e-W1b)

- [Tucano OpenVINO](https://huggingface.co/cabelo/Tucano-2b4-Instruct-fp16-ov) is a ported version of Tucano-2b4-Instruct optimized for Intel openVINO inference technology.
