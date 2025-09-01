### Paper Overview

This repository accompanies the paper *SoK: Anomaly Detection for HTTP-Layer DDoS — Comparative Evaluation of Hybrid ML and Explainable AI Approaches* submitted to USENIX 2026 cycle 1
We review ~45 studies and reproduce 10 state-of-the-art detectors, benchmarking on **CICIDS2017** and a **100k-row synthetic HTTP-DDoS dataset** included here. 
Hybrid tree/AE models (e.g., XAI-IDS, RF+Autoencoder) lead performance (F1 ≈ 0.997–0.999), while correlation-aware and CNN-LSTM models highlight speed/interpretability trade-offs.
The repo provides preprocessing, training, and **XAI** analyses (SHAP/LIME), and introduces **TRUST-AD**, a four-tier blueprint for accurate, transparent, real-time defenses.
