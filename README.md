# Natural Language Processing: Sentiment Analysis of Restaurant Reviews

This project demonstrates the use of Natural Language Processing (NLP) to perform sentiment analysis on a dataset of restaurant reviews. It includes text preprocessing, feature extraction using the Bag of Words model, and classification using a Naive Bayes model.

## Overview

The goal is to predict whether a given restaurant review is **positive** or **negative** based on its content.

## Dataset

- **File**: `Restaurant_Reviews.tsv`
- **Format**: Tab-separated text file with two columns: `Review` and `Liked` (1 for positive, 0 for negative)

## Features

- Text preprocessing using regular expressions, stemming, and stopword removal (with “not” retained for sentiment relevance)
- Bag of Words vectorization
- Naive Bayes classifier for binary sentiment classification
- Evaluation via confusion matrix and accuracy score

## Requirements

Install the following Python packages:

```bash
pip install numpy pandas matplotlib nltk scikit-learn
