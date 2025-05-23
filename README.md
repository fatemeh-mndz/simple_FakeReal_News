

# 📰 Fake News Classifier - Simple NLP Project

This is a basic machine learning project that classifies news articles as **real** or **fake** using **Natural Language Processing (NLP)** techniques.  
I used two classic algorithms: **Naive Bayes** and **K-Nearest Neighbors (KNN)**.

## 🧠 Goal

The goal is to explore simple text classification using machine learning, and understand how different algorithms perform on fake news detection.

## 🧰 Tech and Tools

- Python
- Scikit-learn
- Pandas
- NLP tools (CountVectorizer / TfidfVectorizer)
- Jupyter Notebook

## 🧪 Algorithms Used

- **Multinomial Naive Bayes**: A fast and simple model, often used in text classification.
- **K-Nearest Neighbors (KNN)**: A basic but intuitive algorithm, used here for comparison.

## 📊 Dataset

- I used a public dataset of labeled news articles (real or fake).
- The dataset is split into **training** and **testing** sets.


## ⚙️ How It Works

1. Load and clean the dataset.
2. Convert text into numerical features.
3. Train the model (Naive Bayes or KNN).
4. Evaluate performance using accuracy, confusion matrix, etc.



## 📁 Structure

```
├── data/
│   └── fake_or_real_news.csv
├── notebook.ipynb
└── README.md
```
