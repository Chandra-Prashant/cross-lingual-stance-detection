# Cross-Lingual Stance Detection

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Transformers-blue)](https://huggingface.co/)

A deep learning framework for **cross-lingual stance detection**—predicting an author's stance (e.g., *Favor*, *Against*, or *Neutral*) toward a specific topic or target in a target language using models trained on resource-rich source languages.

---

## 📌 Features

- **Multilingual Transformer Backbones:** Built-in integration with models like `mBERT`, `XLM-RoBERTa`, and `InfoXLM`.
- **Zero-Shot & Few-Shot Transfer:** Train stance classification models in one language (e.g., English) and evaluate on zero-shot target languages.
- **Data Preprocessing & Alignment:** Pipelines for handling cross-lingual textual data, target-text pairs, and sentiment/stance features.
- **Evaluation Suite:** Computes Macro-F1, Target-Specific Accuracy, and Confusion Matrices across different languages.

---

## 📂 Project Structure

```text
cross-lingual-stance-detection/
├── data/              # Datasets and cross-lingual stance annotations
├── models/            # Cross-lingual stance detection model definitions
├── utils/             # Preprocessing, tokenization, and metric evaluation
├── train.py           # Model training & fine-tuning script
├── evaluate.py        # Cross-lingual evaluation script
└── requirements.txt   # Dependencies
