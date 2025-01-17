# IMDb Movie Reviews Sentiment Analysis with Bi-directional LSTM

## Overview
This project focuses on sentiment analysis of IMDb movie reviews using a Long Short-Term Memory (LSTM) neural network. The goal is to classify movie reviews as either positive or negative based on their content. The dataset used is the IMDb movie reviews dataset, which contains 25,000 reviews for training and 25,000 for testing, each labeled as positive or negative.

## Dataset
- **Source**: [IMDb Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment)
- **Description**: The dataset is divided into training and testing sets, each containing 12,500 positive and 12,500 negative reviews.

## Model Training
- **LSTM Architecture**: The model uses a bidirectional LSTM with the following parameters:
  - Embedding size: 64
  - Hidden size: 64
  - Number of layers: 2
- **Training**: The model is trained using the Adam optimizer with a learning rate of 5e-4 and binary cross-entropy loss.
  - Epochs: 100
  - Batch Size: 100
  - Evaluation Metrics: Precision, Recall, F1-Score, and AUC are used to evaluate the model's performance.
