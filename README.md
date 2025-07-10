# 💳 Credit Card Fraud Detection Using Logistic Regression

This project applies machine learning to detect fraudulent credit card transactions using a highly imbalanced dataset. It uses a **Logistic Regression** model trained on a balanced subset of data to effectively identify fraudulent activity.

---

## 🔍 Project Overview

Credit card fraud is a major threat in today's digital economy. Early detection of suspicious transactions is essential to reduce financial loss and protect user accounts. This project uses logistic regression for binary classification (fraud vs. legitimate), with focus on model evaluation and handling imbalanced data.

---

## 📂 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Total Records: 284,807 transactions
- Fraudulent Records: 492 (0.17%)
- Features:
  - `V1` to `V28`: PCA-transformed features
  - `Amount`: Transaction amount
  - `Class`: Target (0 = Legitimate, 1 = Fraudulent)

---

## 🧰 Technologies Used

- Python  
- NumPy, pandas  
- scikit-learn  
- Matplotlib, Seaborn  

---

## 🧠 Model Overview

- **Model**: Logistic Regression (from scikit-learn)
- **Handling Imbalance**:
  - Random under-sampling of majority class
  - Balanced dataset created by matching the number of non-fraud and fraud transactions
- **Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
