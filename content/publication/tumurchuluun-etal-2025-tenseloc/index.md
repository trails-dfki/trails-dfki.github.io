---
title: 'TenseLoC: Tense Localization and Control in a Multilingual LLM'
authors:
- Ariun-Erdene Tumurchuluun
- Yusser Al Ghussin
- David Marecek
- Josef van Genabith
- Koel Dutta Chowdhury 
date: '2025-11-14'
publication_types:
- paper-conference
publication: '*Proceedings of the 5th Workshop on Multilingual Representation Learning (MRL 2025)*'
publication_short: MRL 2025
abstract: 'Multilingual language models excel across languages, yet how they internally encode grammatical tense remains largely unclear. We investigate how decoder-only transformers represent, transfer, and control tense across eight typologically diverse languages: English, German, French, Italian, Portuguese, Hindi, Spanish, and Thai. We construct a synthetic tense-annotated dataset and combine probing, causal analysis, feature disentanglement, and model steering to LLaMA-3.1 8B. We show that tense emerges as a distinct signal from early layers and transfers most strongly within the same language family. Causal tracing reveals that attention outputs around layer 16 consistently carry cross-lingually transferable tense information. Leveraging sparse autoencoders in this subspace, we isolate and steer English tense-related features, improving target-tense prediction accuracy by up to 11%% in a downstream cloze task.'
url_pdf: https://aclanthology.org/2025.mrl-main.17.pdf
links:
- name: URL
  url: https://aclanthology.org/2025.mrl-main.17/
---
