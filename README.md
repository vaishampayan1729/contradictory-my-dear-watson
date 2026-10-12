# Multilingual Natural Language Inference

A pedagogical machine learning project based on Kaggle's **Contradictory, My Dear Watson** competition.

## Overview

Natural Language Inference (NLI) is the task of determining the relationship between a premise and a hypothesis. Given two sentences, a model predicts whether the hypothesis is entailed by the premise, contradicts it, or is neutral with respect to it.

This project explores classical NLP methods, neural sequence models, attention, and multilingual Transformer models through a series of reproducible experiments.

## Objectives

- Understand the theory behind Natural Language Inference.
- Explore and analyze a multilingual sentence-pair dataset.
- Establish classical machine learning baselines.
- Study word embeddings and neural sequence models.
- Understand attention and the Transformer architecture.
- Fine-tune pretrained multilingual language models.
- Compare models using appropriate evaluation metrics.
- Analyze prediction errors and prepare a Kaggle submission.

## Methodology

The project follows a progressive learning approach:

1. Problem formulation and dataset exploration
2. Classical NLP baselines
3. Neural NLP models
4. Attention and Transformers
5. Multilingual pretrained language models
6. Experiments, evaluation, and error analysis
7. Final Kaggle submission

Each stage will include theoretical explanations, implementations, experiments, and observations.

## Repository Structure

```text
contradictory-my-dear-watson/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
├── notebooks/
├── src/
├── models/
└── reports/
    └── figures/
```

## Technology Stack

- Python
- PyTorch
- pandas and NumPy
- scikit-learn
- Hugging Face Transformers
- Matplotlib and Seaborn

Dependencies will be introduced as the project progresses.

## Evaluation

Models will be evaluated using classification metrics, including accuracy, precision, recall, and F1-score, as appropriate. Performance will be compared against simple baselines.

## Competition

[Kaggle — Contradictory, My Dear Watson](https://www.kaggle.com/competitions/contradictory-my-dear-watson/)

## Status

**In progress:** repository setup and foundational exploration.