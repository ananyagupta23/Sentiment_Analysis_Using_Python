# Sentiment_Analysis_Using_Python
The dataset used in this is of customer reviews from Amazon Fine Product.

In this notebook we will be doing some sentiment analysis in python using two different techniques:

1)VADER (Valence Aware Dictionary and sEntiment Reasoner) - Bag of words approach
2)Roberta Pretrained Model from 🤗
3)Huggingface Pipeline

Step 0. Read in Data and NLTK Basics
  Quick EDA
  Basic NLTK
Step 1. VADER Seniment Scoring
  We will use NLTK's SentimentIntensityAnalyzer to get the neg/neu/pos scores of the text.
  This uses a "bag of words" approach:
    1)Stop words are removed
    2)each word is scored and combined to a total score.
Step 2. Plot VADER results
Step 3. Roberta Pretrained Model
    Use a model trained of a large corpus of data.
    Transformer model accounts for the words but also the context related to other words.
  Compare Scores between models
Step 4: Review Examples:
  Positive 1-Star and Negative 5-Star Reviews
Extra: The Transformers Pipeline
  Quick & easy way to run sentiment predictions
