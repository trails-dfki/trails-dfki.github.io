---
title: 'CLaS-Bench: A Cross-Lingual Alignment and Steering Benchmark'
authors:
- Daniil Gurgurov
- Yusser Al Ghussin
- Tanja Baeumel
- Cheng-Ting Chou
- Patrick Schramowski
- Marius Mosbach
- Josef van Genabith
- Simon Ostermann
date: '2026-01-13'
publication_types:
- paper-conference
publication: 'Findings of the Association for Computational Linguistics: ACL 2026'
publication_short: ACL 2026
abstract: 'Understanding and controlling the behavior of large language models (LLMs) is an increasingly important topic in multilingual NLP. Beyond prompting or fine-tuning, , i.e.,~manipulating internal representations during inference, has emerged as a more efficient and interpretable technique for adapting models to a target language. Yet, no dedicated benchmarks or evaluation protocols exist to quantify the effectiveness of steering techniques. We introduce CLaS-Bench, a lightweight parallel-question benchmark for evaluating language-forcing behavior in LLMs across 32 languages, enabling systematic evaluation of multilingual steering methods. We evaluate a broad array of steering techniques, including residual-stream DiffMean interventions, probe-derived directions, language-specific neurons, PCA/LDA vectors, Sparse Autoencoders, and prompting baselines. Steering performance is measured along two axes: language control and semantic relevance, combined into a single harmonic-mean steering score. We find that across languages simple residual-based DiffMean method consistently outperforms all other methods. Moreover, a layer-wise analysis reveals that language-specific structure emerges predominantly in later layers and steering directions cluster based on language family. CLaS-Bench is the first standardized benchmark for multilingual steering, enabling both rigorous scientific analysis of language representations and practical evaluation of steering as a low-cost adaptation alternative.'
url_pdf: https://arxiv.org/pdf/2601.08331
links:
- name: URL
  url: https://arxiv.org/pdf/2601.08331
---
