# Sentiment Analysis on Social Media Data

## 📌 Overview
This project performs sentiment analysis on social media text (Twitter dataset).  
It classifies tweets into **Positive** or **Negative** sentiments using **Python, Scikit-learn, and NLTK**.

## 🚀 Features
- Preprocesses text (tokenization, stopword removal, stemming).
- Converts text into numerical vectors using TF-IDF.
- Trains machine learning classifiers (Logistic Regression, Naive Bayes).
- Achieved ~80% accuracy on test dataset.
- Visualizes sentiment distribution using Matplotlib.

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** NLTK, Scikit-learn, Pandas, Matplotlib  
- **Dataset:** Twitter Sentiment Dataset  

## 📂 Project Structure
```bash

├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for analysis
├── sentiment_model.py # Main training script
└── README.md
```
## 📊 Results
- Accuracy: ~80%  
- Sample predictions:  
  - *"I love this product!" → Positive*  
  - *"Worst service ever." → Negative*  

## 🎯 Future Enhancements
- Use deep learning models (LSTM/BERT).
- Extend to multi-class sentiments (positive, neutral, negative).
- Deploy as a web app with Flask/Django.