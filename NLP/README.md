# NLP Project — Text Classification (IMDb Sentiment + News Articles)

This repository contains two Natural Language Processing (NLP) projects:

- **Part A:** IMDb Sentiment Analysis (Binary Classification)
- **Part B:** News Article Classification (Multi-Class Classification)

Both projects demonstrate end-to-end NLP pipelines including data preprocessing, vectorization, model training, evaluation, and insights.

---

## 📌 Part A — IMDb Sentiment Analysis

### 🎯 Objective
Predict whether movie reviews are **positive** or **negative** based on review text.

### 🧪 Dataset
- ~50,000 reviews
- Binary labels: `positive` / `negative`

### 🔧 Techniques & Workflow
- Text Cleaning & Preprocessing
- Tokenization
- Lemmatization
- Stopword Removal
- TF-IDF Vectorization
- Logistic Regression & SVM Models
- Train/Test Split
- Evaluation Metrics (Accuracy, Precision, Recall, F1)
- ROC Curve Analysis

### 📊 Results
- **Best Model:** Logistic Regression
- **Accuracy:** ~89%

### 📝 Key Insight
Bigrams improved sentiment context and helped distinguish subtle sentiment differences in movie reviews.

---

## 📌 Part B — News Article Classification

### 🎯 Objective
Classify news articles into topic categories using NLP and supervised machine learning.

### 🧪 Dataset
- ~50,000+ news articles
- 10-topic multi-class labels

### 🔧 Techniques & Workflow
- Text Cleaning & Normalization
- TF-IDF Vectorization
- Multi-Class Classification
- Logistic Regression, SVM, Random Forest, XGBoost
- Hyperparameter Tuning (GridSearch)
- Confusion Matrix Analysis

### 📊 Results
- **Best Model:** Linear SVM
- **Accuracy:** ~81%

### 📝 Key Insight
Hyperparameter tuning significantly improved classification performance and reduced class imbalance issues.

---

## 📁 Dataset Download

> Datasets are stored externally due to GitHub file size limits.

| Dataset | Link |
|--------|------|
| IMDb Reviews | [Download](https://docs.google.com/spreadsheets/d/1U3BM4ouUJgOOVSzcHHV5lkqohPdupHvw/edit?usp=sharing&ouid=108392858297942092020&rtpof=true&sd=true) |
| News Articles Dataset | [Download](https://docs.google.com/spreadsheets/d/19vE8_mjt_eOgLF8jenPZKuRrMnIlz9oY/edit?usp=sharing&ouid=108392858297942092020&rtpof=true&sd=true) |

---

## 🛠 Tools & Libraries Used

**Languages:**  
Python

**Libraries:**  
Pandas · NumPy · Scikit-Learn · XGBoost · Matplotlib · Seaborn

**NLP Techniques:**  
TF-IDF · Tokenization · Lemmatization · Stopword Removal

**ML Concepts:**  
Binary Classification · Multi-Class Classification · Model Evaluation

---

## 📂 Project Structure

<pre>

nlp-project/
│
├── notebooks/
│ ├── imdb_sentiment_analysis.ipynb
│ └── news_classification.ipynb
│  
├── data/ (not included — see download links)
└── README.md
  
</pre>


