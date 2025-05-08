# Sentiment-Analysis-LSTM

This repository contains a sentiment analysis pipeline built using a Long Short-Term Memory (LSTM) model to classify IMDb movie reviews as positive or negative. The IMDb dataset is a well-known benchmark for binary sentiment classification and contains 50,000 highly polarized movie reviews.

Overview
Sentiment analysis is a core task in Natural Language Processing (NLP) that involves identifying the emotional tone behind a body of text. This project leverages an LSTM-based neural network to capture the sequential dependencies in text data and accurately classify movie reviews.

Dataset
The IMDb dataset used in this project:

50,000 movie reviews

Evenly split between positive and negative sentiments

Pre-divided into 25,000 training and 25,000 testing samples

No neutral reviews

The dataset is available directly through Keras or can be downloaded manually.

Model Architecture
Input: Tokenized and padded review sequences

Embedding Layer: Converts word indices to dense vectors (pretrained or learned)

LSTM Layer: Captures long-term dependencies in review text

Dropout: Helps prevent overfitting

Dense Output Layer: Uses sigmoid activation for binary classification


