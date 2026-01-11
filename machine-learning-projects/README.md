# Machine Learning Project — Airbnb Price Prediction & Customer Churn Modeling

This repository contains two machine learning projects:

- **Part A:** Airbnb Price Prediction (Regression)
- **Part B:** Telecom Customer Churn Prediction (Classification)

Both projects cover end-to-end ML workflows including data preprocessing, feature engineering, model training, tuning, and evaluation.

---

## 📌 Part A — Airbnb Price Prediction (Regression)

### 🎯 Objective
Predict nightly Airbnb listing prices using listing, location, and host-related features.

### 🧪 Dataset
- ~74,000 Airbnb listings from major U.S. cities
- Target variable: `price` (continuous)

### 🔧 Techniques & Workflow
- Data Cleaning & Missing Value Handling
- Categorical Encoding (One-Hot)
- Feature Engineering
- XGBoost Regression Model
- RandomizedSearch for Hyperparameter Tuning
- Train/Test Split
- Model Evaluation

### 📊 Results
- **Best Model:** XGBoost Regressor
- Metrics: RMSE · MAE · R²
- Important predictive features included:
  - City
  - Accommodates
  - Bedrooms
  - Number of Reviews

### 📝 Key Insight
Pricing varies significantly by city and property capacity. Features related to location and space had the strongest predictive influence.

---

## 📌 Part B — Customer Churn Prediction (Classification)

### 🎯 Objective
Predict whether a telecom customer will churn based on demographic, service, and billing features.

### 🧪 Dataset
- ~7,000 customers
- Target variable: `Churn` (Yes/No)

### 🔧 Techniques & Workflow
- Data Cleaning & Handling Missing Values
- Standardization
- One-Hot Encoding for Categorical Features
- Train/Test Split (Stratified)
- XGBoost Classifier
- RandomizedSearch for Parameter Tuning
- Early Stopping
- Feature Importance Analysis

### 📊 Results
- **Best Model:** XGBoost Classifier
- Performance:
  - Accuracy: ~77%
  - Recall: ~75%
  - ROC-AUC: ~0.84

### 📝 Key Insight
Contract Type and Internet Service were key churn drivers. Recall was prioritized due to business value in catching churners for customer retention.

---

## 🛠 Tools & Libraries Used

- **Languages:** Python
- **Libraries:**
  - Pandas · NumPy · Scikit-Learn · XGBoost
  - Matplotlib · Seaborn
- **ML Concepts:**
  - Regression · Classification
  - Feature Engineering · Model Evaluation
  - Hyperparameter Tuning

---

## 📂 Suggested Project Structure

<pre>
📁 Machine-Learning-Project/
│
├── 📁 notebooks/
│ ├── 📄 airbnb_price_prediction.ipynb
│ └── 📄 churn_prediction.ipynb
│
├── 📁 data/
│ ├── 📄 Customer_data.xlsx
│ └── 📄 Airbnb_data.xlsx 
└── 📄 README.md
 </pre>
