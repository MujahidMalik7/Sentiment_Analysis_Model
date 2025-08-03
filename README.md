# Sentiment_Analysis_Model 🎭🔍

This repository contains a complete **Sentiment Analysis** pipeline built using **Python**, **Scikit-learn**, and **Streamlit**. The project applies **Natural Language Processing (NLP)** techniques to classify IMDB movie reviews as **positive** or **negative** sentiments.

---

## 📌 Project Overview

The goal of this project is to build an effective sentiment classifier using traditional machine learning methods and TF-IDF vectorization. This project consists of two main components:

1. **Model Training Notebook** (`sentiment_analysis.ipynb`)
2. **Streamlit Web Application** (`sentiment_analysis_app.py`)

---

## 🧠 Models Trained

- **Naive Bayes Classifier**  
  - Achieved ~86% accuracy on test data.  
  - Simple and fast but slightly less accurate.

- **Logistic Regression Classifier**  
  - Achieved ~89% accuracy on test data.  
  - Chosen for deployment in the Streamlit app due to better performance.

Both models use TF-IDF to convert text reviews into numerical features and a label encoder to handle sentiment labels.

---

## 📓 Jupyter Notebook: `sentiment_analysis.ipynb`

This notebook contains:

- Data preprocessing and cleaning  
- Exploratory data analysis  
- Feature extraction using TF-IDF vectorization  
- Model training and evaluation for both Naive Bayes and Logistic Regression  
- Saving trained model artifacts (`.pkl` files) for reuse  

The notebook was developed and run in **Google Colab**.

---

## 🌐 Streamlit App: `sentiment_analysis_app.py`

A user-friendly web app to input movie reviews and get instant sentiment predictions.

### Features:

- Input box to enter custom movie reviews  
- Real-time sentiment prediction on button click  
- Displays whether the sentiment is **positive** or **negative**  

### Live App Link:

👉 [Try the live app here](https://sentiment-analyzer-mujahidmalik7.streamlit.app/#sentiment-analysis-web-app)

---
### Tags: 
`#NLP` `#SentimentAnalysis` `#MachineLearning` `#Streamlit` `#Python` `#IMDB` `#TextClassification`
