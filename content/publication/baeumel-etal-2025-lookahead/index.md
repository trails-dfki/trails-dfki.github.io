---
title: 'The Lookahead Limitation: Why Multi-Operand Addition is Hard for LLMs'
authors:
- Tanja Baeumel
- Josef Van Genabith
- Simon Ostermann
date: '2025-11-01'
publishDate: '2025-11-01T13:10:18.998131Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 8th BlackboxNLP Workshop: Analyzing and Interpreting Neural Networks for NLP*'
abstract: "Autoregressive large language models (LLMs) exhibit impressive performance across various tasks but struggle with simple arithmetic, such as additions of two or more operands. We show that this struggle arises from LLMs' use of a simple one-digit lookahead heuristic, which forms an upper bound for LLM performance and accounts for characteristic error patterns in two-operand addition and failure in multi-operand addition, where the carry-over logic is more complex. Our probing experiments and digit-wise accuracy evaluation show that the evaluated LLMs fail precisely where a one-digit lookahead is insufficient to account for cascading carries. We analyze the impact of tokenization strategies on arithmetic performance and show that all investigated models, regardless of tokenization and size, are inherently limited in the addition of multiple operands due to their reliance on a one-digit lookahead heuristic. Our findings reveal limitations that prevent LLMs from generalizing to more complex numerical reasoning."
url_code: 
url_pdf: https://aclanthology.org/2025.blackboxnlp-1.15/ 
links:
- name: URL
  url: https://aclanthology.org/2025.blackboxnlp-1.15/
---
