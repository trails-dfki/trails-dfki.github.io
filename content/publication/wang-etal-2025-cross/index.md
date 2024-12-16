---
title: 'Cross-Refine: Improving Natural Language Explanation Generation by Learning in Tandem'
authors:
- Qianli Wang
- Tatiana Anikina
- Nils Feldhus
- Simon Ostermann
- Sebastian Möller
- Vera Schmitt
date: '2024-12-13'
publishDate: '2024-12-13T13:10:18.998131Z'
publication_types:
- paper-conference
publication: '*The 31st International Conference on Computational Linguistics 2025*'
abstract: "Natural language explanations (NLEs) are vital for elucidating the reasoning behind large language model (LLM) decisions. Many techniques have been developed to generate NLEs using LLMs. However, like humans, LLMs might not always produce optimal NLEs on first attempt. Inspired by human learning processes, we introduce CROSS-REFINE, which employs role modeling by deploying two LLMs as generator and critic, respectively. The generator outputs a first NLE and then refines this initial explanation using feedback and suggestions provided by the critic. CROSS-REFINE does not require any supervised training data or additional training. We validate CROSS-REFINE across three NLP tasks using three state-of-the-art open-source LLMs through automatic and human evaluation. We select SELF-REFINE (Madaan et al., 2023) as the baseline, which only utilizes self-feedback to refine the explanations. Our findings from automatic evaluation and a user study indicate that CROSS-REFINE outperforms SELF-REFINE. Meanwhile, CROSS-REFINE can perform effectively with less powerful LLMs, whereas SELF-REFINE only yields strong results with ChatGPT. Additionally, we conduct an ablation study to assess the importance of feedback and suggestions. Both of them play an important role in refining explanations. We further evaluate CROSS-REFINE on a bilingual dataset in English and German."
url_code: https://github.com/qiaw99/Cross-Refine
url_pdf: https://arxiv.org/abs/2409.07123 
links:
- name: URL
  url: https://arxiv.org/abs/2409.07123
---
