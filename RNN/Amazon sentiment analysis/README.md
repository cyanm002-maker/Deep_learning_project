# Amazon Product Review Sentiment Analysis

This project trains a Recurrent Neural Network (RNN) to predict Amazon product review sentiment as a 1-to-5 star rating.

## Contents

- `Amazon-Product-Review-Sentiment-Analysis-using-RNN-Dataset.csv`
- `RNN_amazon_sentiment.ipynb`
- `Amazon.md`

## Project description

- Loads Amazon review data and inspects missing values.
- Cleans review text by removing HTML, punctuation, and stopwords.
- Tokenizes text, pads sequences to a fixed length, and one-hot encodes sentiment labels.
- Splits data into training and test sets.
- Builds a `Sequential` RNN model with embedding and recurrent layers.
- Trains the model and evaluates it using accuracy and classification metrics.

## Libraries used

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- tensorflow / keras
- scikit-learn

## Notes

- The notebook includes a helper function for predicting ratings from new text input.
- This repository file is intended to describe the project structure and workflow for this folder.
