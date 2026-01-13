# MBA Business Analytics Project  
## Credit Card Fraud Detection using Python

---

## 📌 Project Overview
This project was completed as part of my **MBA curriculum** and focuses on solving a real-world **financial risk and fraud detection problem** using **data analytics and machine learning techniques**.

The project demonstrates how **data-driven approaches** can help financial institutions identify **fraudulent credit card transactions** hidden within large volumes of legitimate transactions.
---

## 🎯 Business Problem
Credit card fraud causes:
- Significant financial losses to banks and customers  
- Reduced customer trust  
- Increased compliance and operational risk  

**Key Challenge:**  
Fraudulent transactions are extremely rare and embedded in a highly imbalanced dataset, making traditional rule-based detection ineffective.

---

## 🧠 Business Objective
- Analyze credit card transaction data  
- Identify abnormal transaction patterns  
- Apply anomaly detection techniques for fraud identification  
- Recommend a suitable model for fraud risk management  

---

## 📊 Dataset Information
- Transaction-level credit card data  
- Features are anonymized for confidentiality  
- Highly imbalanced dataset (fraud cases are very limited)  
- Target variable: `Class` (Fraud vs Non-Fraud)

> ⚠️ Dataset is not uploaded due to confidentiality reasons.

---

## 🛠 Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning  

---

## 🔍 Analysis & Methodology

### 1️⃣ Data Understanding & Preparation
- Loaded and examined transaction data  
- Verified data quality and structure  
- Separated features and target variable  

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed transaction distribution  
- Observed severe class imbalance  
- Visualized fraud vs non-fraud behavior  

### 3️⃣ Machine Learning Models Used
Unsupervised anomaly detection models were selected due to class imbalance:

- **Isolation Forest**
- **Local Outlier Factor (LOF)**
- **One-Class Support Vector Machine (SVM)**

These models learn normal transaction behavior and flag deviations as potential fraud.

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy score  
- Classification report  

**Isolation Forest** demonstrated the strongest performance in identifying anomalous transactions.

---

## 💡 Key Insights
- Fraudulent transactions exhibit distinct abnormal patterns  
- Anomaly detection techniques are effective for imbalanced financial datasets  
- Model selection significantly impacts fraud detection performance  

---

## 🏦 Business Impact
- Enables early detection of suspicious transactions  
- Helps reduce financial losses due to fraud  
- Strengthens fraud monitoring and risk management systems  
- Supports data-driven decision-making in banking  

---

## 📌 Business Recommendations
- Use anomaly detection models alongside rule-based systems  
- Continuously retrain models with new transaction data  
- Integrate fraud detection outputs into real-time monitoring dashboards  

---

MBA-Business-Analytics-Project/
│
├── credit_card_fraud_detection.ipynb
└── README.md


## ▶️ How to Run This Project

1. Clone the repository:
git clone    https://github.com/vivek263kumar/MBA-Business-Analytics-Project



## 👤 Author
Vivek Kumar | MBA | Business Analytics

🔗 GitHub: https://github.com/vivek263kumar  
🔗 LinkedIn: www.linkedin.com/in/vivek263kumar

