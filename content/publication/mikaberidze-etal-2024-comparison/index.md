---
title: 'A Comparison of Different Tokenization Methods for the Georgian Language'
authors:
- Beso Mikaberidze
- Temo Saghinadze
- Guram Mikaberidze
- Raphael Kalandadze
- Konstantine Pkhakadze
- Josef van Genabith
- Simon Ostermann
- Lonneke van der Plas
- Philipp Müller
publication_types:
- paper-conference
publication: '*Proceedings of the 7th International Conference on Natural Language and Speech Processing (ICNLSP 2024)*'
abstract: "While the impact of tokenization on language modeling is well-researched in richly resourced languages, fewer studies on this topic exist for challenging low-resource languages. In this work, we present the first systematic evaluation of tokenization methods for Georgian, a low-resource language with high morphological complexity. We compare standard subword tokenizers, such as WordPiece, Byte Pair Encoding, SentencePiece with Unigram, and a recently proposed token-free approach. We also investigate the multilingual BERT tokenizer (mBERT), which includes Georgian. In addition to these different classes of tokenization algorithms we also evaluate the impact of different vocabulary sizes, a key parameter for subword tokenizers. We evaluate the performance of all tokenizers on masked language modeling and on four downstream tasks: part-of-speech tagging, named entity recognition, toxicity detection, and sentiment analysis. We observe that larger vocabulary sizes for subword tokenizers generally lead to better performance across most tasks, with a notable exception in the toxicity detection task, where finer subword granularity is more effective. For the remaining tasks, pre-training tokenizers on Georgian text consistently yield better results compared to mBERT. Additionally, the token-free method is consistently outperformed by all other tokenizers. Taken together, our comprehensive evaluation of tokenizers will be highly valuable in making informed tokenization choices in future language model developments for Georgian."
url_pdf: https://aclanthology.org/2024.icnlsp-1.22/
links:
- name: URL
  url: https://aclanthology.org/2024.icnlsp-1.22/
---
