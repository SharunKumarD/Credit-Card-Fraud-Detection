# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project aims to detect fraudulent credit card transactions using Machine Learning. The dataset contains anonymized transaction features, and the objective is to classify each transaction as either **Fraud (1)** or **Non-Fraud (0)**.

---

## 📂 Dataset

The dataset contains:

- Time – Time elapsed between transactions
- Amount – Transaction amount
- V1 to V28 – Anonymized features
- Class – Target variable
  - 0 = Non-Fraud
  - 1 = Fraud

The dataset is highly imbalanced, with fraudulent transactions representing only a small fraction of the total data.

---

## 🎯 Objective

- Analyze transaction data.
- Perform data preprocessing and feature scaling.
- Build a Logistic Regression model for fraud detection.
- Evaluate model performance using standard classification metrics.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Workflow

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Preprocess the data
4. Scale features
5. Split data into training and testing sets
6. Train Logistic Regression model
7. Evaluate the model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## 📈 Results

- High classification accuracy on the test dataset.
- Successfully identified fraudulent transactions using Logistic Regression.
- Evaluation performed using precision, recall, F1-score, and confusion matrix.

---

## 📷 Visualizations

- Fraud vs Non-Fraud Transaction Count
- Correlation Heatmap
- Confusion Matrix

---

## 🚀 Future Improvements

- Handle class imbalance using SMOTE.
- Compare Logistic Regression with ensemble models such as Random Forest and XGBoost.
- Perform hyperparameter tuning to improve model performance.

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│── Credit_Card_Fraud_Detection.ipynb
│── creditcard.csv
│── README.md
```

---

## 👨‍💻 Author

**Sharun Kumar D**

M.Tech Integrated CSE (Data Science)  
VIT Vellore

---

## ⭐ If you found this project useful, please consider giving it a Star.
