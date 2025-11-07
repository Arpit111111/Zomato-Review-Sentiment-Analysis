# Zomato-Review-Sentiment-Analysis
Sentiment Analysis of Zomato restaurant reviews using NLP and Machine Learning.
Author: Arpit Nayak  
Tech:Python · NLP · Machine Learning · Pandas · Scikit-Learn

## Project Overview
This project analyzes customer reviews from food delivery platforms like Zomato to determine whether a review expresses a **Positive**, **Negative**, or **Neutral** sentiment.

The goal is to understand customer feedback patterns and help restaurants improve service, food quality, and overall customer experience.

## Objectives
- Clean and preprocess customer review text
- Convert text into machine-readable numerical features (TF-IDF)
- Train machine learning models for sentiment classification
- Evaluate model performance and compare accuracy
- Visualize insights from review data

## Techniques Used
| Area | Method/Tool |
|------|-------------|
| Data Handling | Pandas, NumPy |
| Text Preprocessing | Stopword removal, Lemmatization |
| Feature Extraction | TF-IDF Vectorization |
| ML Models | Logistic Regression / Naive Bayes / SVM |
| Visualization | Matplotlib / WordCloud |

## Dataset
- The dataset contains restaurant reviews labeled as **Positive**, **Negative**, or **Neutral**.
- Includes features like review text, sentiment label, and star rating.

> Note: Dataset used here is generated / sample-based and is intended for demonstration and        model development.

## Model Output Example
| Review Text | Predicted Sentiment |
|------------|--------------------|
| "The food was amazing and delivered hot!" | Positive |
| "Worst delivery experience, completely cold food." | Negative |
| "Food was okay, nothing special." | Neutral |

##  How to Run the Project
```bash
# Install required libraries
pip install -r requirements.txt

# Run the notebook
jupyter notebook "Zomato Review Sentiment Analysis.ipynb"
