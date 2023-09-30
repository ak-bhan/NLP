# Sentiment Analysis on Tweets

## Overview

This project performs sentiment analysis on tweets using a logistic regression model. It includes data preparation, data preprocessing, data splitting, feature extraction, model training, prediction, testing, error analysis, and personalized tweet prediction.

## Table of Contents

- [Data Preparation](#data-preparation)
- [Data Preprocessing](#data-preprocessing)
- [Data Splitting](#data-splitting)
- [Feature Extraction](#feature-extraction)
- [Logistic Regression Model](#logistic-regression-model)
- [Prediction and Testing](#prediction-and-testing)
- [Error Analysis](#error-analysis)
- [Personalized Tweet Prediction](#personalized-tweet-prediction)

## Data Preparation

- Downloaded the Twitter dataset from the NLTK corpus, including positive and negative tweets.
- Printed the number of positive and negative tweets in the dataset.

## Data Preprocessing

- Cleaned tweets by removing retweet text, hyperlinks, and hashtags.
- Tokenized cleaned tweets using TweetTokenizer.
- Removed stopwords and punctuation from tokenized tweets.
- Stemmed the words in the tweets to reduce them to their base form.

## Data Splitting

- Split the dataset into training and testing sets, both for positive and negative tweets.

## Feature Extraction

- Extracted features from the tweets using a frequency dictionary (word frequencies in positive and negative tweets).

## Logistic Regression Model

- Implemented gradient descent to train a logistic regression model using the extracted features and labels.
- Printed the cost after training and the resulting weights.

## Prediction and Testing

- Implemented a function to predict the sentiment (positive/negative) of a given tweet using the trained model.
- Tested the model's accuracy on the testing dataset.

## Error Analysis

- Performed error analysis by printing tweets that were misclassified along with their predicted and actual labels.

## Personalized Tweet Prediction

- Provided a personalized tweet, processed it, predicted its sentiment, and printed the result.
