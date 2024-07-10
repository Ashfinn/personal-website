---
title: "IMDB Sentiment Analysis App 🎬"
excerpt: "<br/><img src='/images/imdb.png'>"
collection: portfolio
---

**Check the Preview :** [Link to the App](https://imdb-sentiment-analyzer.streamlit.app/)

This app uses a machine learning model to analyze the sentiment. Enter a text and click "Analyze" to see if the sentiment is positive or negative.

## How It Works
1. **Preprocessing**: The input review is preprocessed to remove HTML tags, punctuation, and stopwords, and then stemmed.
2. **TF-IDF Transformation**: The preprocessed review is transformed into a TF-IDF vector.
3. **Prediction**: The model predicts the sentiment of the text based on the TF-IDF vector.

## Usage
- Enter a movie review in the text area provided.
- Click on the "Analyze" button.
- The app will display the predicted sentiment of the review.