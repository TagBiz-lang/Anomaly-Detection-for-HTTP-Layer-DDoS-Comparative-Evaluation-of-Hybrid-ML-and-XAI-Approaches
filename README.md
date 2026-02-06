### Paper Overview

This repository accompanies the papers "SoK: Hybrid Machine Learning and Explainable AI for HTTP/Application-Layer DDoS Detection
and 
The paper
"Empirical Evaluation and Benchmarking of Hybrid ML/XAI Models
for HTTP-layer DDoS Detection"

We studied over 2000 papers and review 210 studies in detail, and reproduce 10 state-of-the-art, benchmarking on **CICIDS2017** and a **100k-row synthetic HTTP-DDoS dataset** included here. 
Hybrid tree/AE models (e.g., XAI-IDS, RF+Autoencoder) lead performance (F1 ≈ 0.997–0.999), while correlation-aware and CNN-LSTM models highlight speed/interpretability trade-offs.
The repo provides preprocessing, training, and **XAI** analyses (SHAP/LIME), and introduces **TRUST-AD**, a four-tier blueprint for accurate, transparent, real-time defenses.
