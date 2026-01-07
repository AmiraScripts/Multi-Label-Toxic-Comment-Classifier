# Multi-Label Toxic Comment Classification

This repository contains a **Google Colab notebook** that builds and evaluates a machine learning model for detecting toxic comments with **multiple labels per comment**.

## Notebook
- `toxic_multilabel.ipynb` → includes preprocessing, TF-IDF vectorization, model training (One-vs-Rest Logistic Regression), threshold tuning, evaluation, and confusion matrix.

## How to run
1. Open the notebook in GitHub, or click **“Open in Colab”**
2. Upload the dataset file when the notebook asks for it
3. Run all cells from top → bottom

## Libraries used
Pandas, NumPy, Scikit-learn, imbalanced-learn, Matplotlib

## Task
Multi-label text classification for toxicity detection:
`toxic`, `severe_toxic`, `obscene`, `threat`, `insult`, `identity_hate`

## Results
Mean ROC-AUC ≈ **0.97** and micro-F1 ≈ **0.73**

---
Feel free to reuse or extend this project for content moderation research.

