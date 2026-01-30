# Customer-Churn-Analysis
Predicting Customer Churn Using Machine Learning: A Case Study on a Telecom Dataset

### Objective:
The goal of this project is to build a machine learning pipeline that predicts whether a customer will churn (i.e., leave the company) or stay, based on their demographic 
information, account details, and service usage patterns. This is a common and critical problem in the telecom industry, where customer retention has a direct impact on revenue.

### Content:
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.
The data set includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents
Inspiration

### Business Value:
By identifying customers at risk of churn, telecom companies can proactively implement strategies such as targeted marketing campaigns, loyalty programs, and customized offers 
to retain these customers.

---

## 🏗️ Project Architecture

```
MLSA-PROJECT/
├── Data/
│   └── Final Project MLSA- Dataset.csv
├── Note_Book/
│   └── Customer Churn Prediction.ipynb
├── app.py
├── ML_model.joblib
├── scaler.joblib
└── README.md
---

## 🔄 Workflow

```

## 🚀 Features

* 🔍 **Churn Prediction** — Predict whether a customer will churn based on input data.
* 💡 **Label Encoding & Scaling** — Categorical and numerical preprocessing are applied consistently.

---

## 🛠️ Technologies Used

* **scikit-learn** — For model training and preprocessing.
* **Pandas** — Data manipulation.
* **Joblib** — Model and scaler serialization.

---

## 🧠 Machine Learning Model

* **Model:** Random Forest Classifier
* **Target Variable:** `Churn` (Yes/No)
* **Features Used:**

  * Gender
  * Tenure
  * Internet Service
  * Online Backup
  * Tech Support
  * Contract Type
  * Payment Method
  * Monthly Charges
  * Total Charges
  * Average Charges per Month
