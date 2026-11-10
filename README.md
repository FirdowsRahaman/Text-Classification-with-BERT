# ⚡ Text Classification with BERT

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Framework: PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C.svg?logo=pytorch&logoColor=white)](#)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-FFD21E.svg)](#)

Fine-tuning BERT (`bert-base-uncased`) and Hugging Face Transformers for end-to-end text and intent classification with PyTorch.

## 📌 Overview
This repository contains an end-to-end natural language processing (NLP) pipeline demonstrating how to fine-tune pre-trained bidirectional transformer encoders (BERT) on custom text corpora. It includes dataset preprocessing, tokenization with attention masks, training loops with AdamW and learning rate schedulers, and real-time inference routines.

## 🛠️ Tech Stack & Dependencies
- **Model:** `bert-base-uncased` (Hugging Face Transformers)
- **Deep Learning Framework:** PyTorch, TorchText
- **Data & Evaluation:** Scikit-Learn, Pandas, NumPy, Matplotlib

## 📂 Repository Contents
- `Text Classification with BERT.ipynb`: Full training notebook covering tokenization, loss optimization, cross-entropy calculation, and validation sweeps.
- `BERT Prediction.ipynb`: Interactive inference notebook for testing custom text inputs and visualizing softmax class confidence scores.

## 🚀 Quickstart
```bash
git clone https://github.com/FirdowsRahaman/Text-Classification-with-BERT.git
cd Text-Classification-with-BERT
pip install torch transformers scikit-learn pandas
jupyter notebook
```

## 📊 Evaluation & Results
- **Tokenizer:** BERT WordPiece Tokenizer with max sequence length padding and truncation.
- **Optimizer:** AdamW with linear warmup schedule and weight decay.
- **Evaluation:** Precision, Recall, F1-Score, and multi-class Confusion Matrix analysis.

## 📄 License
This project is licensed under the MIT License.
