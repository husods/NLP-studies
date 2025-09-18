# Explainable & Multi-Model Sentiment Analysis for Azerbaijani

A multi-model sentiment analysis system for **Azerbaijani**, a low-resource language, classifying comments as **positive** or **negative** with **explainable AI (XAI)** support.

> **Note:** Trained model weights and full datasets are **not included** due to large file sizes. This repository contains only **source code for the models, algorithms, and a Flask web app**.

---

## Features

- **Multi-Model:** TF-IDF + Logistic Regression, LaBSE + BiGRU, XLM-RoBERTa  
- **Explainable AI:** SHAP visualizations for Logistic Regression predictions  
- **High Performance:** XLM-RoBERTa achieves 85% accuracy, 0.84 macro F1-score  
- **Dataset:** 55,000+ reviews used in the project (not included)  
- **Web Interface:** Flask app provides a user-friendly interface that allows users to input text and see **real-time predictions from all three models simultaneously**, with SHAP-based explanations for Logistic Regression

---

## How to Use

Since the model weights and datasets are **not included**, you can:

1. Explore the **implementation of models and algorithms** in the code  
2. Adapt the pipeline to your **own datasets**  
3. Examine the **Flask app structure** and extend it for your use case

---

## Contact

Open an issue or contact the repo owner for questions or contributions.
