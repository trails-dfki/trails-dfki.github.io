---
title: Symmetric Dot-Product Attention for Efficient Training of BERT Language Models
authors:
- Martin Courtois
- Malte Ostendorff
- Leonhard Hennig
- Georg Rehm
date: '2024-01-01'
publishDate: '2024-08-14T12:28:11.319812Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: ACL 2024*'
publication_short: ACL Findings 2024
url_pdf: https://aclanthology.org/2024.findings-acl.476.pdf
url_code: https://github.com/mcrts/ACL2024-SymmetricAttentionBert
abstract: Initially introduced as a machine translation model, the Transformer architecture has now become the foundation for modern deep learning architecture, with applications in a wide range of fields, from computer vision to natural language processing. Nowadays, to tackle increasingly more complex tasks, Transformer-based models are stretched to enormous sizes, requiring increasingly larger training datasets, and unsustainable amount of compute resources. The ubiquitous nature of the Transformer and its core component, the attention mechanism, are thus prime targets for efficiency research.In this work, we propose an alternative compatibility function for the self-attention mechanism introduced by the Transformer architecture. This compatibility function exploits an overlap in the learned representation of the traditional scaled dot-product attention, leading to a symmetric with pairwise coefficient dot-product attention. When applied to the pre-training of BERT-like models, this new symmetric attention mechanism reaches a score of 79.36 on the GLUE benchmark against 78.74 for the traditional implementation, leads to a reduction of 6% in the number of trainable parameters, and reduces the number of training steps required before convergence by half.
---
