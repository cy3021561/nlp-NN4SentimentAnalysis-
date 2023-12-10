# NLP Project: Neural Network Analysis with Amazon Reviews

## Overview

This project focuses on implementing and analyzing various neural network architectures for natural language processing tasks, using a dataset of Amazon reviews.

## Tasks

### 1. Dataset Generation

- Generate a balanced dataset of 100,000 Amazon reviews.
- Use an 80%/20% training/testing split.

### 2. Word Embedding

#### (a) Pretrained Word2Vec Model

- Experiment with the "word2vec-google-news-300" model.
- Explore semantic similarities with examples.

#### (b) Custom Word2Vec Model

- Train a Word2Vec model on the dataset.
- Compare with the pretrained model and discuss the findings.

### 3. Simple Models

- Train a perceptron and an SVM using pre-trained Word2Vec features.
- Report and compare accuracy using both Word2Vec and TF-IDF features.

### 4. Feedforward Neural Networks

#### (a) MLP with Average Word2Vec

- Train a multilayer perceptron with two hidden layers using average Word2Vec vectors.
- Report accuracy on the testing split.

#### (b) MLP with Concatenated Word2Vec

- Use concatenated Word2Vec vectors of the first 10 words of each review.
- Compare accuracy with simple models.

### 5. Recurrent Neural Networks

#### (a) Simple RNN

- Train a simple RNN, limiting review length.
- Report accuracy on the testing split.

#### (b) GRU Cell

- Use a gated recurrent unit (GRU) cell and repeat the above.

#### (c) LSTM Cell

- Train using an LSTM unit cell.
- Compare accuracy across GRU, LSTM, and simple RNN models.

## Evaluation Metrics

Accuracy values to be reported for:

- 2 cases using Perceptron and SVM.
- 2 cases using Feedforward Neural Networks.
- 3 cases using Recurrent Neural Networks.
