# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The objective is to build a model that can accurately identify fraud in a highly **imbalanced dataset**, minimizing false negatives while maintaining good overall performance.

This project demonstrates the complete **end-to-end ML pipeline** including data preprocessing, model training, evaluation, and result interpretation.

---

## 🧠 Problem Statement
Credit card fraud leads to massive financial losses worldwide.  
Traditional rule-based systems fail to adapt to evolving fraud patterns.

The challenge is:
- Extremely **imbalanced data** (fraud cases are very rare)
- High cost of **false negatives** (missing a fraud)

This project applies machine learning models to classify transactions as **fraudulent** or **legitimate**.

---

## ⚙️ Technologies & Tools Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📊 Dataset
The dataset used in this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/mlg-ulb/creditcardfraud  

📌 **Note:**  
Due to GitHub file size limitations, the dataset is **not included** in this repository.  
Please download the dataset and place it inside the `dataset/` folder before running the code.

---

## 🔍 Methodology
1. Data loading and exploration  
2. Handling missing values (if any)  
3. Feature scaling  
4. Handling class imbalance  
5. Model training  
6. Model evaluation  

---

## 🤖 Models Used
- Logistic Regression  
- (Mention others if you used: Random Forest, SVM, etc.)

---

## 📈 Model Evaluation Metrics
Since the dataset is imbalanced, the following metrics were used:
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

Accuracy alone is **not sufficient** for fraud detection problems.

---

## 🚀 How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
