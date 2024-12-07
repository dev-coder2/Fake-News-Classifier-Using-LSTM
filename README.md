# Fake News Classification with LSTM

This project uses **LSTM** for classifying news articles as real or fake. It involves **tokenization**, **stemming**, and **one-hot encoding** of text data, followed by an **embedding layer** to convert the one-hot vectors into dense word representations. The model is trained with an **LSTM layer** to achieve high accuracy.

## Project Overview

The goal of this project is to build a model capable of distinguishing fake news articles from real ones. The model leverages **tokenization**, **stemming**, and **LSTM** to process and classify text data.

## Dataset

- **Dataset**: The dataset used for this project is from the Kaggle competition, "Fake News Detection."
- **Description**: The dataset consists of news articles with labels indicating whether they are real or fake.

## Key Techniques

1. **Tokenization**: Breaking the text data into individual words.
2. **Stemming**: Reducing words to their root form (e.g., "running" becomes "run").
3. **One-Hot Encoding**: Converting text data into binary vectors for each word.
4. **Embedding Layer**: Converting one-hot encoded vectors into dense word embeddings.
5. **LSTM**: Using a Long Short-Term Memory model to capture long-term dependencies in text.

