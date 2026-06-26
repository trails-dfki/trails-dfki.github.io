---
title: 'Multilingual steering by design: Multilingual sparse autoencoders and principled layer selection'
authors:
- Yusser Al Ghussin
- Daniil Gurgurov
- Tanja Baeumel
- Josef van Genabith
- Patrick Schramowski
- Simon Ostermann
date: '2026-05-21'
publication_types:
- paper-conference
publication: 'Proceedings of the 6th Workshop on Trustworthy NLP (TrustNLP 2026)'
publication_short: TrustNLP 2026
abstract: 'Sparse autoencoders (SAEs) enable feature-level mechanistic interpretability and activation steering in large language models (LLMs), but SAE-based language control remains unreliable in multilingual settings: most SAEs are trained on English-only data, and steering layers are chosen heuristically. We address these limitations by advancing a principled, mechanistic account of multilingual language steering with SAEs. First, we show that training SAEs on multilingual data consistently strengthens cross-lingual representations and yields more reliable, quality-preserving language control across layers and model families. Second, we introduce an \emph{a priori} steering layer-selection rule based on the intersection of multilingual alignment and language separability, which predicts effective intervention depths without exhaustive layerwise search. We evaluate our approach on LLaMA-3.1-8B and Gemma-2-9B across machine translation and cross-lingual summarization (CrossSumm), using SpBLEU, ROUGE-L, COMET, and LaSE. Our results show that multilingual SAEs combined with intersection-selected layers stabilize the trade-off between language identification accuracy and generation quality, providing a principled, predictive, representation-level account of multilingual SAE steering.'
url_pdf: https://arxiv.org/pdf/2605.23036
links:
- name: URL
  url: https://arxiv.org/pdf/2605.23036
---
