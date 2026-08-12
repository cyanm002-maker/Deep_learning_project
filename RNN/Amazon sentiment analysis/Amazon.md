# Amazon Product Review Sentiment Analysis

This project uses a Recurrent Neural Network (RNN) model to analyze Amazon product reviews and predict the review sentiment as a star rating from 1 to 5.

## Overview

- Dataset: `Amazon-Product-Review-Sentiment-Analysis-using-RNN-Dataset.csv`
- Goal: Convert raw review text into a sentiment prediction and rating classification.
- Approach: Text preprocessing, tokenization, padding, one-hot encoding, and RNN-based classification.

## Key Steps

1. Load and inspect the review dataset.
2. Clean review text by removing HTML, punctuation, and stopwords.
3. Tokenize and pad review text sequences to a consistent length.
4. Convert sentiment labels into one-hot encoded vectors.
5. Split data into training and testing sets.
6. Build and train a sequential RNN model with embedding and recurrent layers.
7. Evaluate the trained model on the test set and measure accuracy.

## Model Details

- Uses `tensorflow.keras` with `Embedding`, `SimpleRNN`, and `Dense` layers.
- Trains with `categorical_crossentropy` loss and `adam` optimizer.
- Predicts review sentiment as one of five star rating categories.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- tensorflow
- scikit-learn

## Notes

- The notebook includes model training, validation, and evaluation.
- A prediction helper function converts new review text into a predicted rating.
