---
title: "SIREN: Spatially-Informed Reconstruction of Binaural Audio with Vision"
collection: publications
article_url: "https://arxiv.org/abs/2603.29820"
authors: "Mingyeong Song<sup>*</sup>, <strong>Seoyeon Ko</strong><sup>*</sup>, Junhyug Noh"
author_note: "<sup>*</sup> Equal contribution."
venue: "International Conference on Acoustics, Speech, and Signal Processing (<strong>ICASSP</strong>)"
year: 2026
thumbnail: "/images/publications/SIREN.png"
order: 2
    
summary: >-
  SIREN reconstructs binaural audio from monaural sound and visual context by
  directly predicting the left and right channels. Its ViT-based encoder combines
  dual-head self-attention with a softly annealed spatial prior to capture shared
  scene representations and spatially grounded left/right cues. A two-stage,
  confidence-weighted waveform fusion strategy further suppresses crosstalk
  across multiple crops and overlapping windows using mono reconstruction
  confidence and interaural phase consistency. The framework improves
  time-frequency and phase-sensitive reconstruction quality on FAIR-Play and
  MUSIC-Stereo without requiring task-specific spatial annotations
---
