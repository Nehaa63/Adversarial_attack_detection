Adversarial Attack Detection in Large Language Models

Phase 1

Overview

This project explores machine learning-based detection of adversarial prompts, including prompt injection attempts targeting Large Language Models (LLMs). Phase 1 implements a baseline classifier to distinguish benign and adversarial prompts.

Objectives

- Prepare a labelled prompt dataset.
- Extract text features using TF-IDF.
- Train a Logistic Regression classifier.
- Evaluate performance using classification metrics and a confusion matrix.

Dataset

Source: "Hugging Face – Prompt Injections" (https://huggingface.co/datasets/wambosec/prompt-injections)

The dataset contains labelled prompts for benign and adversarial classification.

Methodology

1. Data loading and preprocessing.
2. TF-IDF feature extraction using unigrams and bigrams.
3. Stratified train-test split (80:20).
4. Logistic Regression model training using Scikit-learn.
5. Evaluation using accuracy, precision, recall, F1-score and a confusion matrix.

Technologies

Python · Google Colab · Pandas · Hugging Face Datasets · Scikit-learn · Matplotlib



Current Progress

- Dataset preprocessing completed.
- Baseline model trained and evaluated.
- Classification report and confusion matrix generated.
- Project files uploaded to GitHub.

Team

- Neha K R — 148
- Pavithra E B — 152
- Sneha Rose C J — 173
- Sreelakshmi C S — 179

Project Guide: Ms. Prajitha M. V.
Institution: Vidya Academy of Science and Technology

Future Work

Evaluate additional datasets, compare advanced detection approaches, and investigate robustness against unseen adversarial prompts.

Status: Phase 1 — Baseline implementation and evaluation.
