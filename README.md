# movie-review
# 🎬 Movie Review Sentiment Analysis using Naive Bayes

This project performs **sentiment analysis** on movie reviews using the **Naive Bayes classifier** and the **NLTK Movie Reviews Dataset**. It predicts whether a movie review is **positive** or **negative** based on its text content.

---

## 📚 Project Overview

The goal of this project is to classify movie reviews into positive or negative sentiments using machine learning and natural language processing (NLP) techniques.

We use:
- **NLTK** for accessing the movie reviews dataset.
- **scikit-learn** for text vectorization and model building.
- **Naive Bayes (MultinomialNB)** as the classification algorithm.

---

## 🧠 Key Features

- Preprocessing of text data using `CountVectorizer`
- Training a Naive Bayes model on real movie review data
- Accuracy evaluation on the test set
- Allows users to input their own movie review for live sentiment prediction

---

## 🧩 Tech Stack

- Python 🐍  
- NLTK  
- Scikit-learn  
- NumPy (optional)  

---

## 📦 Installation

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/<your-username>/movie-review-sentiment.git
cd movie-review-sentiment
pip install -r requirements.txt
