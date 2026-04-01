# 💳 Credit Card Fraud Detection System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview
This project explores and models **credit card fraud detection** using real-world transactional data. It combines **exploratory data analysis (EDA)**, **data visualisation**, and **machine learning** to identify patterns associated with fraudulent behaviour.

The dataset is highly imbalanced, making this a **realistic and challenging classification problem**.

---

## 📊 Dataset Description
- **Total Transactions:** 284,807  
- **Fraudulent Transactions:** 492 (~0.17%)  
- **Features:**  
  - `Time`  
  - `Amount`  
  - `V1–V28` (PCA-transformed features)  
  - `Class` (0 = Normal, 1 = Fraud)

---

## 🔍 Exploratory Data Analysis

### ✔ Fraud Distribution
- Severe class imbalance detected  
- Fraud accounts for **less than 1%** of transactions  

### ✔ Transaction Amount Analysis
- Fraudulent transactions show a **higher average amount**  
- Suggests unusual spending behaviour is a strong indicator  

### ✔ Correlation Analysis
- Correlation heatmap reveals relationships between features  
- Certain features exhibit patterns useful for classification  

---

## 📈 Visualisations Included
- 📊 Fraud vs Non-Fraud Count Plot  
- 📊 Percentage Distribution Chart  
- 📊 Average Transaction Amount Comparison  
- 🔥 Correlation Heatmap  
- 🔥 Confusion Matrix Heatmap  

---

## 🤖 Machine Learning Pipeline

### 🔧 Steps:
1. Data loading and preprocessing  
2. Feature exploration  
3. Train-test split  
4. Model training  
5. Prediction generation  
6. Model evaluation  

### 🧠 Model Used:
- Logistic Regression *(update if you used another model)*

---

## 📊 Model Evaluation

Due to class imbalance, multiple evaluation metrics were used:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

### 🔑 Key Insight:
> Accuracy is misleading in imbalanced datasets — **recall is critical** for fraud detection to minimise missed fraud cases.

---

## 🔥 Confusion Matrix

The confusion matrix heatmap highlights:
- True Positives (Fraud correctly detected)
- False Negatives (Missed fraud ⚠️)
- False Positives
- True Negatives

---

## ⚙️ Technologies Used

| Tool | Purpose |
|-----|--------|
| Python | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Basic visualisation |
| Seaborn | Advanced visualisation |
| Scikit-learn | Machine learning |

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Silverdon25/credit-card-fraud-detection.git

## Author

Devon Wildman
