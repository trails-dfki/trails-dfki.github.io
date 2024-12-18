---
title: 'Adapting Multilingual LLMs to Low-Resource Languages with Knowledge Graphs via Adapters'
authors:
- Daniil Gurgurov
- Mareike Hartmann
- Simon Ostermann
publication_types:
- paper-conference
publication: '*Proceedings of the 1st Workshop on Knowledge Graphs and Large Language Models (KaLLM 2024)*'
abstract: "This paper explores the integration of graph knowledge from linguistic ontologies into multilingual Large Language Models (LLMs) using adapters to improve performance for low-resource languages (LRLs) in sentiment analysis (SA) and named entity recognition (NER). Building upon successful parameter-efficient fine-tuning techniques, such as K-ADAPTER and MAD-X, we propose a similar approach for incorporating knowledge from multilingual graphs, connecting concepts in various languages with each other through linguistic relationships, into multilingual LLMs for LRLs. Specifically, we focus on eight LRLs {---} Maltese, Bulgarian, Indonesian, Nepali, Javanese, Uyghur, Tibetan, and Sinhala {---} and employ language-specific adapters fine-tuned on data extracted from the language-specific section of ConceptNet, aiming to enable knowledge transfer across the languages covered by the knowledge graph. We compare various fine-tuning objectives, including standard Masked Language Modeling (MLM), MLM with full-word masking, and MLM with targeted masking, to analyze their effectiveness in learning and integrating the extracted graph data. Through empirical evaluation on language-specific tasks, we assess how structured graph knowledge affects the performance of multilingual LLMs for LRLs in SA and NER, providing insights into the potential benefits of adapting language models for low-resource scenarios."
url_pdf: https://aclanthology.org/2024.kallm-1.7
links:
- name: URL
  url: https://aclanthology.org/2024.kallm-1.7
---
