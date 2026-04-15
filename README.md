# Multiclass Sentiment Analysis of Phone Reviews

## Overview

This project explores sentiment analysis on Amazon unlocked mobile phone reviews using multiple machine learning, deep learning, and transformer-based models.

The goal was to classify customer reviews into:

* Positive
* Neutral
* Negative

---

## Dataset

* Source: Amazon Unlocked Mobile Phones Reviews (Kaggle)
* Size: 400,000+ reviews
* Features: Review text, rating, product details, timestamps

---

## Key Techniques

### Data Preprocessing

* Lowercasing text
* Removing punctuation and stopwords
* Tokenization
* TF-IDF vectorization
* Label encoding

### Models Used

* Logistic Regression
* Random Forest
* LSTM
* DistilBERT
* ELECTRA

---

## Results

| Model               | Accuracy | F1 Score  |
| ------------------- | -------- | --------- |
| Logistic Regression | 0.83     | 0.85      |
| Random Forest       | 0.94     | 0.94      |
| LSTM                | 0.91     | 0.91      |
| DistilBERT          | 0.94     | 0.94      |
| ELECTRA             | **0.95** | **0.957** |

---

## Key Insights

* Transformer-based models (ELECTRA, DistilBERT) achieved the highest performance
* Logistic Regression provided a fast baseline with lower accuracy
* LSTM balanced performance and computational cost

---

## Limitations

* High computational cost for transformer models
* Limited GPU resources during training
* Training time was significantly longer for deep learning models

---
