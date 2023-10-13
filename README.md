# Sentiment Analysis of Customer Reviews on Amazon

## Overview

This project focuses on performing sentiment analysis on customer reviews collected from Amazon. The primary objectives are to understand customer sentiment, improve model performance, and derive insights from the data.

## Table of Contents

- [Data Overview](#data-overview)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Class Imbalance](#class-imbalance)
- [Model Improvement](#model-improvement)
- [Future Work](#future-work)
- [Conclusion](#conclusion)

## Data Overview

- **Dataset**: The dataset consists of X customer reviews with Y columns, including the 'reviews.text' and 'sentiment' columns.
- **Sentiment Distribution**: The sentiment distribution is as follows: Z% positive, W% negative, and U% neutral.

## Data Preprocessing

- **Text Cleaning**: Text data underwent preprocessing to remove noise and irrelevant information.
- **Feature Engineering**: We used the TF-IDF vectorization technique for text representation.

## Model Training

- **Model**: A Random Forest model was selected for sentiment analysis.
- **Hyperparameters**: Key hyperparameters include n_estimators, max_features, min_samples_split, min_samples_leaf, and max_depth.

## Model Evaluation

- The model achieved an accuracy of X%.
- Precision, recall, and F1-score for each sentiment class are as follows:
  - Positive: Precision, Recall, F1-Score
  - Negative: Precision, Recall, F1-Score
  - Neutral: Precision, Recall, F1-Score

## Class Imbalance

- Class imbalance was addressed through random oversampling to ensure a more balanced dataset for model training.

## Model Improvement

- Challenges were identified in classifying negative and neutral sentiments.
- Future strategies will focus on improving model performance through feature engineering and advanced modeling techniques.

## Future Work

- Future plans include collecting more data, exploring alternative machine learning algorithms, and experimenting with ensemble techniques to enhance sentiment analysis.

## Conclusion

- This analysis provides valuable insights into customer sentiment on Amazon, highlighting the importance of addressing class imbalance and continuous model improvement.

---

Feel free to include additional sections or details relevant to your project. Make sure to provide clear explanations and document your process to help other team members and collaborators understand your work.

