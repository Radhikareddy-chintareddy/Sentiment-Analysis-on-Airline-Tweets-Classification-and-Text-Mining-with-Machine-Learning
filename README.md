# Sentiment Analysis on Airline Tweets: Classification and Text Mining with Machine Learning

This project applies text mining and machine learning techniques to classify sentiment in airline-related tweets. By analyzing customer feedback on social media, the project aims to provide insights into public sentiment, helping airlines enhance customer experience and reputation management.

## Problem Statement
Airlines frequently receive feedback on social media platforms, often reflecting customer satisfaction or dissatisfaction. This project leverages machine learning to classify tweets into positive, negative, or neutral sentiments, enabling airlines to monitor and respond effectively to customer sentiment.

## Objectives
1. Perform **Exploratory Data Analysis (EDA)** to understand the structure and distribution of sentiment labels.
2. Preprocess and clean text data using **text mining techniques**.
3. Implement **classification algorithms** to predict sentiment.
4. Evaluate the performance of machine learning models using appropriate metrics.

## Methodology
### 1. Data Preprocessing
- Removed noise such as special characters, URLs, and stop words from tweets.
- Tokenized text and applied lemmatization for better feature representation.

### 2. Text Mining
- Extracted features using term frequency (TF) and TF-IDF (Term Frequency-Inverse Document Frequency).
- Explored n-grams (unigrams and bigrams) for improved context understanding.

### 3. Classification Models
- Implemented various classification algorithms, including:
  - Logistic Regression
  - Naïve Bayes
  - Random Forest
  - Support Vector Machines (SVM)
- Balanced class distribution using oversampling techniques like SMOTE.

### 4. Evaluation
- Used metrics like accuracy, precision, recall, and F1-score for performance assessment.
- Visualized results using confusion matrices and precision-recall curves.

## Tools and Libraries
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **NLP Libraries**: nltk, TextBlob
- **Classification Algorithms**: Logistic Regression, Naïve Bayes, Random Forest, SVM

## Key Results
- Achieved robust classification performance with high accuracy and balanced precision-recall scores.
- Insights into customer sentiment trends help airlines identify key areas for improvement.

