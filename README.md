# Twitter-Sentiment-Analysis
## 1. Project Overview

The objective of this project is to classify tweets into Positive, Negative, or Neutral sentiments. Understanding customer sentiment helps businesses make informed decisions and improve their brand strategies.

---

## Business Use:
Analyze customer opinions about products/brands.
Identify areas of improvement based on negative feedback.
Leverage positive feedback in marketing campaigns.

---

## 2. Business Problem

Social media generates a huge volume of unstructured text data, making it difficult for companies to determine whether customer sentiment towards their brand or product is positive, negative, or neutral. Automating sentiment analysis enables faster and more accurate insights.

---

## 9. Tech Stack
Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, SpaCy, Scikit-learn, WordCloud
Tools: Jupyter Notebook, GitHub

---

## 3. Dataset
Source: Kaggle – Twitter Entity Sentiment Analysis
Size: 110k+ tweets
Columns: id, entity, sentiment, content

---

## 5. Data Cleaning
Added column names
Removed missing values and duplicates
Checked dataset info and basic statistics

---

## 6. Exploratory Data Analysis (EDA)
Sentiment distribution
Top entities mentioned in tweets
Word frequency & WordClouds
Tweet length distribution

----

## 7. Text Preprocessing
Performed text cleaning and lemmatization using SpaCy:
Lowercasing
Removed URLs, mentions, hashtags, special characters
Removed stopwords
Lemmatization

---

## 8. Feature Engineering
Converted text into numerical features using TF-IDF Vectorization

---

## 9. Model Building
Models used: Logistic Regression, Naive Bayes, SVM
Train-Test Split: 80% train, 20% test

---

## 10. Model Evaluation
-Evaluated using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
-SVM performed best, followed by Logistic Regression and Naive Bayes.

---
## Insights

Positive tweets indicate brand strengths and customer satisfaction.
Negative tweets reveal customer pain points and areas for improvement.
Neutral tweets provide contextual information that can help in understanding trends.
Filtering irrelevant or spam tweets can increase model accuracy and business relevance.
Sentiment analysis can guide marketing strategies, product development, and customer service improvements.

---

## Conclusion

This project demonstrates a complete end-to-end sentiment analysis workflow on social media data.
By combining data cleaning, EDA, text preprocessing, and machine learning models, we can classify tweets with good accuracy and extract actionable insights for business decisions.

Key takeaways:
Preprocessing and feature engineering are critical for text analysis.
SVM provided the best accuracy among tested models for this dataset.
Sentiment insights can directly impact brand strategy, customer engagement, and service improvement.
The approach can be extended to other social media platforms or languages with minimal adaptation.

---


