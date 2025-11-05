---
title: 'Saarland-Groningen at NADI 2025 Shared Task: Effective Dialectal Arabic Speech Processing under Data Constraints'
authors: 
- Badr M. Abdullah
- Yusser Al Ghussin
- Zena Al-Khalili
- Ömer Tarik Özyilmaz
- Matias Valdenegro-Toro
- Simon Ostermann
- Dietrich Klakow
date: '2025-11-05'
publication_types:
- paper-conference
publication: '*Proceedings of The Third Arabic Natural Language Processing Conference: Shared Tasks*'
publication_short: ArabicNLP 2025
abstract: "We present our systems for the NADI 2025 shared task on multidialectal Arabic speech processing, participating in both spoken dialect identification (ADI) and automatic speech recognition (ASR) subtasks. Working under data constraints by using only the provided shared task resources for dialect adaptation, we explore effective model adaptation strategies for dialectal Arabic speech. For ADI, we fine-tune w2v-BERT 2.0 and employ voice conversion as data augmentation, improving accuracy from 68.71% to 76.40% on a blind cross-domain test set. For ASR, we develop two complementary approaches: (1) a CTC-based model pre-trained on public Arabic speech data, and (2) Whisper-based models using two-stage fine-tuning. Our experiments show that while dialect-centric CTC models exhibit better zero-shot dialectal performance (58.89 vs 93.90 WER), Whisper achieves better performance after dialect-specific adaptation, which reduces WER from 93.89 to 39.78 WER. We also demonstrate that using character error rate (CER) as a validation criterion provides practical benefits with minimal performance trade-offs. Despite using no external resources for dialect adaptation beyond the shared task data, our systems ranked second in ADI and third in ASR, demonstrating that careful adaptation strategies can overcome data constraints in dialectal speech processing."
url_pdf: https://aclanthology.org/2025.arabicnlp-sharedtasks.102.pdf
links:
- name: URL
  url: https://aclanthology.org/2025.arabicnlp-sharedtasks.102
---
