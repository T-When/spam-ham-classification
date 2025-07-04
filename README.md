# Spam and Ham Detection

This project is a basic **Spam vs Ham (non-spam)** message classifier using NLP (Natural Language Processing) techniques and machine learning. The goal is to accurately identify whether a given message is spam or not.

---

## Project Overview

This project focuses on classifying text messages as **spam** or **ham** using a Naive Bayes classifier. Two different NLP preprocessing and vectorization pipelines were explored:

### Model 1:
- **Preprocessing:**
  - Tokenization
  - Stopword removal
  - **Porter Stemming**
- **Vectorization:** Bag of Words (BoW)

### Model 2:
- **Preprocessing:**
  - Tokenization
  - Stopword removal
  - **Lemmatization**
- **Vectorization:** TF-IDF (Term Frequency - Inverse Document Frequency)

Both pipelines were trained using the **Naive Bayes** algorithm.

---

## Technologies Used

- **Language:** Python
- **Libraries:**
  - `scikit-learn`
  - `nltk`
  - `pandas`, `numpy`

---

## Models and Methods

### Text Preprocessing
- **Tokenization:** Splitting text into individual words
- **Stopword Removal:** Filtering out common words like "and", "is", etc.
- **Porter Stemming:** Reducing words to root form (e.g., “running” → “run”)
- **Lemmatization:** Using linguistic knowledge to reduce words to dictionary form (e.g., “better” → “good”)

### Vectorization
- **Bag of Words (BoW):** Counts word frequencies
- **TF-IDF:** Weighs words by importance across all documents

### Model
- **Naive Bayes:** A probabilistic classifier based on Bayes' Theorem, commonly used for text classification.

---

## Results

- Accuracy , precision and recall scores were compared between both models.
- Both stemming with BoW and lemmatization with TF-IDF showed competitive performance.
- Naive Bayes handled both feature representations efficiently.



