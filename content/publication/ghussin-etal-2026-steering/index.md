---
title: 'Dfki-mlt at semeval-2026 task 7: Steering multilingual models towards cultural knowledge'
authors:
- Yusser Al Ghussin
- Daniil Gurgurov
- Yasser Hamidullah
- Josef van Genabith
- Cristina España-Bonet
- Simon Ostermann
date: '2026-05-21'
publication_types:
- paper-conference
publication: 'Proceedings of the 20th International Workshop on Semantic Evaluation (SemEval-2026)'
publication_short: SemEval 2026
abstract: 'Large language models (LLMs) are increasingly used across diverse linguistic and cultural contexts, yet their cultural knowledge remains uneven across regions and languages. We present the DFKI-MLT system for SemEval-2026 Task 7 on cultural awareness, where we apply activation steering to multilingual LLMs using language vectors extracted from parallel FLORES data. Our method performs inference-time adaptation by adding language-specific steering vectors to the residual stream at a selected transformer layer, without any parameter updates. We participated in both the short-answer (SAQ) and multiple-choice (MCQ) tracks; however, only our MCQ submission received an official score. In the official MCQ track, we achieved 86.96% accuracy, ranking 7th out of 17 teams. To better understand system behavior, we conduct post-hoc analyses on the shared-task MCQ and SAQ settings. These analyses show that activation steering yields modest and heterogeneous improvements on cultural reasoning: gains are strongly layer-sensitive, vary substantially across language-region pairs, with some configurations even degrading performance, and interact with prompt formulation, comparing generic and culturally conditioned prompts. Our findings suggest that prompt design and activation steering should be jointly optimized for culturally aware multilingual inference.'
url_pdf: https://arxiv.org/pdf/2605.23069
links:
- name: URL
  url: https://arxiv.org/pdf/2605.23069
---
