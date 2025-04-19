# 🛍️ Amazon Review Classification using NLP

This project focuses on classifying Amazon product reviews using Natural Language Processing (NLP) techniques. The aim is to automatically categorize customer feedback, aiding in better understanding user sentiment and product performance.

## 📌 Objective

- Clean and preprocess Amazon review text data
- Build and evaluate classification models (e.g., sentiment or category classification)
- Apply NLP techniques like TF-IDF, Word Embeddings, and Text Vectorization
- Deploy an interactive Streamlit app for real-time review prediction

## 🧰 Tech Stack

- **Python**
- **Libraries**: Pandas, NumPy, NLTK, Scikit-learn, XGBoost
- **NLP Techniques**: Tokenization, Lemmatization, TF-IDF
- **Modeling**: Logistic Regression, Random Forest, XGBoost
- **Deployment**: Streamlit

## 📂 Project Structure


## 🔍 Workflow

1. **Data Preprocessing**
   - Cleaning HTML tags, punctuation, stopwords
   - Tokenization and Lemmatization
   - Vectorization (TF-IDF)

2. **Model Training**
   - Train/test split
   - Evaluation using Accuracy, F1-Score, Confusion Matrix

3. **Deployment**
   - Real-time classification using Streamlit app

## 🚀 Run the App

```bash
streamlit run deploy_review_classifier.py
