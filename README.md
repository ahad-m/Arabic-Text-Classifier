# Arabic-Text-Classifier
# Arabic Sentiment Analysis

## Overview
This project implements a sentiment analysis system for Arabic text using machine learning techniques. The system classifies Arabic reviews into positive or negative sentiment categories with high accuracy.

Features
- **Comprehensive Arabic text preprocessing pipeline**
- **Multiple machine learning models for sentiment classification**
- **Custom feature engineering for Arabic sentiment analysis**
- **Evaluation and comparison of model performance**

- **TF-IDF with ExtraTreesClassifier**
- **Word2Vec with LinearSVC**
- **FastText with SVC**

## Model Performance
Here are the accuracy results for each model:

- **TF-IDF with ExtraTreesClassifier**: Accuracy: **0.84**
- **Word2Vec with LinearSVC**: Accuracy: **0.81**
- **FastText with SVC**: Accuracy: **0.83**

### Dataset

This project uses the **Arabic Reviews** dataset from Kaggle, sourced from the user **ahmedmoabbas**. The dataset consists of Arabic reviews that are utilized to train and test the sentiment analysis models. You can find more details about the dataset on [Kaggle](https://www.kaggle.com).

### Future Improvements

- **Expand the training dataset with more diverse Arabic text**
- **Implement deep learning models (BERT, transformers) for Arabic**
- **Add support for dialectal Arabic variations**
- **Improve negation handling for complex sentences**
