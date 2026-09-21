# Sentiment Analysis with Advanced NLP

## Overview

This project implements an end-to-end deep learning sentiment analysis system using the IMDB Movie Review dataset.

The objective is to classify movie reviews as positive or negative and compare multiple neural network architectures.

## Models Implemented

1. Bidirectional LSTM
2. GRU with Attention
3. 1D Text CNN
4. Hybrid CNN-LSTM
5. Ensemble of the top-performing models

## Dataset

IMDB Movie Review Dataset

- Negative = 0
- Positive = 1

## Dataset Split

- Training = 70%
- Validation = 15%
- Testing = 15%

## NLP Preprocessing

- Lowercase conversion
- HTML removal
- URL removal
- Special-character removal
- Word-level tokenization
- Character-level tokenization
- Stopword analysis
- Vocabulary creation
- Sequence padding and truncation

## Embeddings

- Custom Word2Vec
- Optional pretrained GloVe

Large external GloVe files are excluded from the final ZIP.

## Training

- Adam optimizer
- Binary cross-entropy loss
- Class weighting
- Dropout regularization
- L2 regularization
- Early stopping
- Learning-rate reduction
- Validation F1 model selection

## Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Advanced Features

- Top-three model ensemble
- Error analysis
- Confidence analysis
- Word importance visualization
- Real-time sentiment prediction

## Output Directory

C:\Users\sagni\Downloads\Sentiment Analysis with Advanced NLP

## Storage

The final project is automatically compressed into a ZIP archive.

If the ZIP becomes too large, non-best model weights are removed automatically to keep the submission below 50 MB.