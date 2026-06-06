# 📰 Fake News Detection App

A machine learning web application that detects whether a given news article is **Real** or **Fake**. The system utilizes Natural Language Processing (NLP) for text preprocessing and feature extraction, paired with a **Logistic Regression** classifier to deliver fast and accurate predictions.

## 🚀 Features
* **Text Preprocessing:** Cleans and tokenizes raw news text (lowercasing, removing punctuation/stop words).
* **TF-IDF Vectorization:** Extracts key numerical features using `TfidfVectorizer` to gauge word importance.
* **Logistic Regression Engine:** An efficient, highly interpretable binary classification model optimized for text data.

## 📐 How It Works

1. **Data Ingestion:** The app takes a news headline or body text as input.
2. **Vectorization:** The text is converted into a numerical matrix using a pre-trained TF-IDF model.
3. **Classification:** A Logistic Regression model calculates the probability of the text being real or fake based on learned word weights.

