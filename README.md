# Toxic Online-Comments Classification

This script runs using Python 3.

## Overview

Challenge from Kaggle with Toxic Comment Classification Dataset

```php
Identify and classify toxic online comments
```

## Dataset

Pre-trained word vectors from Common Crawl: 840B tokens, 2.2M vocab, cased, 300d vectors, 2.03 GB.

```php
Pre-trained GloVe vectors (Global Vectors for Word Representation) from Stanford. 
```

## Data Pre-Processing

- Remove stopwords and punctuation: NLTK (Natural Language Toolkit)
- Make everything lowercase
- Shuffle data and split train and validation dataset

## Build model

- Word Embedding
- RNN
- 3-D Tensor into LSTM layer

## Train model

- Go through 2 epoches (not to overfit)

## Evaluate model

- Calculate training and validation loss

- Calculate training and validation accuracy

## Accuracy: 97.79%

## References

- Dataset from Kaggle: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
- https://nlp.stanford.edu/projects/glove/
- https://en.wikipedia.org/wiki/Long_short-term_memory
- https://towardsdatascience.com/classify-toxic-online-comments-with-lstm-and-glove-e455a58da9c7
