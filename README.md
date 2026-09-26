# IMDb Movie Review Sentiment Classification using RNN, LSTM, Bi-LSTM & GRU

A deep learning NLP project that performs binary sentiment classification on the IMDb Movie Reviews dataset using four recurrent neural network architectures.

## Overview

This project compares the performance of:

- Simple RNN
- LSTM
- Bidirectional LSTM
- GRU

The models are trained on the IMDb dataset and evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC, PR-AUC, and Confusion Matrix. The best-performing GRU model is deployed using Gradio for real-time sentiment prediction.

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Gradio

## Dataset

- IMDb Movie Reviews Dataset (TensorFlow Keras)
- 25,000 training reviews
- 25,000 testing reviews
- Binary sentiment classification

## Results

| Model | Accuracy | ROC-AUC |
|--------|----------|---------|
| RNN | 74.00% | 0.7848 |
| LSTM | 78.83% | 0.8622 |
| Bi-LSTM | 79.43% | 0.8721 |
| **GRU** | **80.18%** | **0.8809** |

## Repository Contents

- `Lab_Assignment_05_IMDb_Sentiment_Classification.ipynb` — Complete implementation from preprocessing to deployment.

---

Developed as part of **Machine Learning Projects with Python (CSE4192)** at **ITER, SOA University**.
