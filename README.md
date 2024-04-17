Sequence-to-Sequence Model for Text Summarization

This repository contains code for implementing a sequence-to-sequence model for text summarization using TensorFlow and Keras. The model is trained on the Amazon Fine Food Reviews dataset to generate concise summaries for given reviews.

Introduction:

Text summarization is the process of distilling the most important information from a source text to create a condensed version, making it easier to comprehend. This project explores the implementation of a sequence-to-sequence model with attention mechanism for text summarization tasks.

Requirements
Make sure you have the following dependencies installed:

1.Python (>=3.6)

2.TensorFlow (>=2.0)

3.Keras (>=2.0)

4.Pandas

5.NumPy

6.NLTK


BeautifulSoup
Matplotlib# text-text-summarisation

Dataset:

The model is trained on the Amazon Fine Food Reviews dataset, which consists of reviews from Amazon users along with corresponding summaries.
Due to the size constraints, a subset of the dataset (100,000 samples) is used in this implementation.

Model Architecture:

The model architecture consists of an encoder-decoder framework with LSTM (Long Short-Term Memory) layers. 
Attention mechanism is incorporated to capture important information from the input sequence.

Results:
