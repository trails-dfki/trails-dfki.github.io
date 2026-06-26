---
title: 'Grounding or Guessing? Visual Signals for Detecting Hallucinations in Sign Language Translation'
authors:
- Yasser HAMIDULLAH
- Koel Dutta Chowdhury
- Yusser Al Ghussin
- Shakib Yazdani
- Cennet Oguz
- Josef van Genabith
- Cristina España-Bonet
date: '2026-01-26'
publication_types:
- paper-conference
publication: 'The Fourteenth International Conference on Learning Representations (ICLR 2026)'
publication_short: ICLR 2026
abstract: 'Hallucination, where models generate fluent text unsupported by visual evidence, remains a major flaw in vision–language models and is particularly critical in sign language translation (SLT). In SLT, meaning depends on precise grounding in video, and gloss-free models are especially vulnerable because they map continuous signer movements directly into natural language without intermediate gloss supervision that serves as alignment. We argue that hallucinations arise when models rely on language priors rather than visual input. To capture this, we propose a token-level reliability measure that quantifies how much the decoder uses visual information. Our method combines feature-based sensitivity, which measures internal changes when video is masked, with counterfactual signals, which capture probability differences between clean and altered video inputs. These signals are aggregated into a sentence-level reliability score, providing a compact and interpretable measure of visual grounding. We evaluate the proposed measure on two SLT benchmarks (PHOENIX-2014T and CSL-Daily) with both gloss-based and gloss-free models. Our results show that reliability predicts hallucination rates, generalizes across datasets and architectures, and decreases under visual degradations. Beyond these quantitative trends, we also find that reliability distinguishes grounded tokens from guessed ones, allowing risk estimation without references; when combined with text-based signals (confidence, perplexity, or entropy), it further improves hallucination risk estimation. Qualitative analysis highlights why gloss-free models are more susceptible to hallucinations. Taken together, our findings establish reliability as a practical and reusable tool for diagnosing hallucinations in SLT, and lay the groundwork for more robust hallucination detection in multimodal generation.'
url_pdf: https://openreview.net/pdf?id=bLFW2T3UHq
links:
- name: URL
  url: https://openreview.net/pdf?id=bLFW2T3UHq
---
