# Fake News Detection Project

This project aims to create a machine learning model to detect fake news articles using Natural Language Processing (NLP) and sentiment analysis techniques. The project includes a fairness audit to identify potential biases and ensure equitable model performance across different groups.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Results and Findings](#results-and-findings)

---

## Project Overview

The Fake News Detection project uses machine learning and NLP techniques to analyze text data and classify news articles as "Real" or "Fake." Key aspects include:
- **Data Collection**: Using a dataset of news articles.
- **Data Preprocessing**: Cleaning and tokenizing text.
- **Feature Engineering**: Creating TF-IDF vectors.
- **Modeling**: Training models with Random Forest, logistic regression, and other algorithms.
- **Fairness Assessment**: Performing fairness audits using demographic parity difference metrics to detect any bias in model predictions.

This project is ideal for gaining insights into both the model’s performance and the ethical implications of machine learning in sensitive applications.

---

## Project Structure

Each notebook and file is organized sequentially to provide a step-by-step process of the project. 

1. Dataset Overview: Initial exploration of the dataset.
2. Data Cleaning: Removing noise and standardizing text data.
3. Keyword Detection: Extracting relevant keywords for analysis.
4. Text Title Analysis: Analyzing the text titles of articles.
5. Sensationalism Detection](05_Detecting_Sensationalism.ipynb): Identifying sensationalism in text.
6. Emotion Analysis: Analyzing emotions within the text.
7. Feature Engineering: Creating features for machine learning models.
8. Logistic Regression Model: Training a logistic regression classifier.
9. Random Forest Model: Training a Random Forest model for better accuracy.
10. Confusion Matrix: Visualizing model performance with a confusion matrix.
11. Fairness Audit: Performing a fairness audit to evaluate model bias.

Other supporting files include:
- **cleaned_dataset.csv**: Processed dataset ready for model training.
- **news_articles.csv**: Original dataset with news articles.

---

## Results and Findings

## Model Performance
**Random Forest Model:** Achieved a classification accuracy of 92% in detecting fake news.
**Logistic Regression:** Achieved slightly lower accuracy but provided interpretability advantages.

## Fairness and Bias Audit
Using demographic parity difference and equalized odds, we identified a demographic parity difference of 0.324, indicating some bias in predictions. Future steps include:
**Improving Fairness:** Exploring mitigation strategies, such as reweighting or retraining on balanced data.
Visualizing Fairness: Charts and graphs illustrate the disparity, showing areas for improvement.

