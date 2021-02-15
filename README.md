# Sentiment-Analysis
This repository contains a notebook for building domain agnostic sentiment analysis model based on a bidirectional LSTM with provision to re-learn/fine-tune pre trained GloVe Embeddings. The downloaded pre-trained GloVe embeddings may be missing for a number of words in our vocabulary, and re-training the embedding generation process is helpful in representing words in our vocabulary more accurately numerically.
The dataset used is an amalgamation of three types of unstructured labeled text data-
  - IMDB reviews dataset
  - Amazon product reviews dataset
  - Tweets dataset
  
The model built reaches a training accuracy of 98%.
