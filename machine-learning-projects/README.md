# Machine Learning Projects — Text Classification (Part A & Part B)

This repository contains two machine learning projects focused on text classification using NLP techniques:  
(1) IMDb Movie Review Sentiment Analysis, and  
(2) News Article Topic Classification.

---

## 📌 Part A — IMDb Sentiment Analysis

### 📍 Objective
Build a binary classifier to predict whether a movie review is **positive** or **negative** using NLP and Machine Learning techniques.

### 🧩 Dataset
- IMDb movie reviews dataset (50,000 reviews)
- Binary labels: `positive` / `negative`

### 🔧 Techniques Used
- Data Cleaning & Preprocessing
- Tokenization
- Stopword Removal
- Lemmatization
- TF-IDF Vectorization
- Logistic Regression & SVM
- Train/Test Split
- Model Evaluation

### 📈 Model Performance
- Logistic Regression achieved the best performance
- **Accuracy:** ~89%
- Evaluation using: Accuracy, Precision, Recall, F1, ROC-AUC

### 🧠 Key Insights
- Bigrams improved sentiment context
- Positive & negative words were identified through feature coefficients
- ROC curve showed strong separability between classes

---

## 📌 Part B — News Article Classification

### 📍 Objective
Classify news articles into multiple categories (e.g., Business, Sports, Politics) using multi-class text classification.

### 🧩 Dataset
- News article dataset (`~50,000+ samples`)
- Multi-class labels across 10 categories

### 🔧 Techniques Used
- Text Preprocessing & Cleaning
- TF-IDF Vectorization
- Multi-class Classification
- Logistic Regression, SVM, Random Forest, XGBoost
- Hyperparameter Tuning (GridSearch)
- Confusion Matrix Analysis

### 📈 Model Performance
- Linear SVM provided the highest performance
- **Test Accuracy:** ~81%

### 🧠 Key Insights
- Class imbalance impacted accuracy for certain categories
- Hyperparameter tuning improved classification margin
- Confusion matrix helped identify frequently misclassified categories

---

## 🛠 Tools & Libraries

- **Languages:** Python
- **Libraries:**  
  `Pandas`, `NumPy`, `Scikit-Learn`, `XGBoost`,  
  `Matplotlib`, `Seaborn`
- **ML Techniques:** Classification, NLP, TF-IDF, Model Evaluation
- **Metrics:** Accuracy, Precision, Recall, F1, ROC-AUC

---

## 🚀 Possible Improvements

- Experiment with neural models (RNN/CNN/BERT)
- Apply ensemble voting methods
- Expand preprocessing with contextual embeddings (Word2Vec/FastText)
- Integrate deployment through an API

---

## 📌 Project Structure (Suggested)

