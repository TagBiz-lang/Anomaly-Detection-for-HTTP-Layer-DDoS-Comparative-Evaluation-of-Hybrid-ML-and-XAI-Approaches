### Paper Overview

This repository accompanies the paper *SoK: Hybrid Machine Learning and Explainable AI
for HTTP/Application-Layer DDoS Detection: A
Systematization*

and 
Empirical Validation of Hybrid ML/XAI Approaches
for HTTP DDoS Detection: Benchmarking and the
TRUST-AD System (https://www.overleaf.com/project/691d0cdd14d9011193230090)

We review 210 studies in detaiil, and reproduce 10 state-of-the-art, benchmarking on **CICIDS2017** and a **100k-row synthetic HTTP-DDoS dataset** included here. 
Hybrid tree/AE models (e.g., XAI-IDS, RF+Autoencoder) lead performance (F1 ≈ 0.997–0.999), while correlation-aware and CNN-LSTM models highlight speed/interpretability trade-offs.
The repo provides preprocessing, training, and **XAI** analyses (SHAP/LIME), and introduces **TRUST-AD**, a four-tier blueprint for accurate, transparent, real-time defenses.
