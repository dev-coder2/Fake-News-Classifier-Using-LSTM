# Fake News Classification using One-Hot Embedding and LSTM

This project implements a **fake news classification** model using **One-Hot Embedding** and **Long Short-Term Memory (LSTM)**. The model classifies news articles as real or fake based on their content. We preprocess the data by tokenizing the text and applying stemming techniques.

## Project Overview

The objective of this project is to create a robust model that can accurately predict whether a news article is real or fake. We use various techniques including **one-hot embedding**, **LSTM**, **tokenization**, and **stemming**. 

## Dataset

- **Dataset**: The dataset used for this project comes from the Kaggle competition "Fake News Detection."
- **Description**: The dataset contains a collection of news articles with labels indicating whether the article is real or fake.

## Key Techniques

1. **One-Hot Encoding**: The text data is transformed into one-hot encoded vectors to represent each word uniquely.
2. **Tokenization**: The text is split into words and preprocessed for model input.
3. **Stemming**: Words are reduced to their root form, e.g., "running" becomes "run."
4. **LSTM**: We use LSTM (Long Short-Term Memory) layers for sequence processing and to capture dependencies over time in the text data.


