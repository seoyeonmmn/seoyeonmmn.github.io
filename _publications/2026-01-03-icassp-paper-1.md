---
title: "SIREN: Spatially-Informed Reconstruction of Binaural Audio with Vision"
collection: publications
authors: "Mingyeong Song<sup>*</sup>, <strong>Seoyeon Ko</strong><sup>†</sup>, Junhyug Noh"
author_note: "<sup>*</sup> Equal contribution."
venue: "International Conference on Acoustics, Speech, and Signal Processing (<strong>ICASSP</strong>)"
year: 2026
order: 2
links:
  - name: article
    url: "https://arxiv.org/abs/2603.29820"
    
summary: >-
  We propose SIREN, a visually guided mono-to-binaural audio reconstruction
  framework that directly predicts left and right channels from monaural audio
  and visual context. A ViT-based encoder uses dual-head self-attention to learn
  shared scene representations and spatially grounded left/right cues, while a
  soft annealed spatial prior supports stable localization during training.
  A two-stage confidence-weighted waveform fusion further reduces crosstalk
  across multiple crops and overlapping windows using mono reconstruction
  confidence and interaural phase consistency. SIREN consistently improves
  time-frequency and phase-sensitive reconstruction quality on FAIR-Play and
  MUSIC-Stereo without requiring task-specific spatial annotations.
---
