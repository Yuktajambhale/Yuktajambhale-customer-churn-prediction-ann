# 🚀 Customer Churn Prediction using Artificial Neural Network (ANN)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ANN-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 **Problem Statement**
Customer churn prediction helps businesses identify customers who are likely to stop using a service.  
The objective of this project is to build a **machine learning model** that predicts whether a customer will churn based on historical banking data.

---

## 📊 **Dataset**
The dataset used in this project is the **Customer Churn dataset from Kaggle**.

It contains customer demographic details, account information, and service usage patterns.  
🎯 **Target Variable:** `Exited` (1 = Churned, 0 = Not Churned)

---

## 📑 **Dataset Features**
- **RowNumber** – Row index  
- **CustomerId** – Unique customer identifier  
- **Surname** – Customer surname  
- **CreditScore** – Customer credit score  
- **Geography** – Customer location  
- **Gender** – Customer gender  
- **Age** – Customer age  
- **Tenure** – Years with the bank  
- **Balance** – Account balance  
- **NumOfProducts** – Number of products used  
- **HasCrCard** – Has credit card (1 = Yes, 0 = No)  
- **IsActiveMember** – Active member status  
- **EstimatedSalary** – Estimated annual salary  
- **Exited** – **Target variable (Churn)**  

🚫 **Removed during preprocessing:** `RowNumber`, `CustomerId`, `Surname`

---

## 🛠 **Tech Stack**
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas  
- **Machine Learning:** Scikit-learn  
- **Deep Learning:** TensorFlow, Keras  
- **Visualization:** Matplotlib, Seaborn  

---

## 🤖 **Model Used**
- **Artificial Neural Network (ANN)**
- **Binary Classification Problem**
- **Train–Validation split** for performance evaluation

---

## 📈 **Model Performance**
- ✅ **Training Accuracy:** ~86%  
- ✅ **Validation Accuracy:** ~85%  
- ⚠️ Observed **slight overfitting**, indicating scope for regularization and early stopping

---

## 📉 **Evaluation**
- Accuracy metric used for evaluation  
- Training vs Validation accuracy plotted to analyze overfitting behavior  

---

## ✅ **Conclusion**
The ANN model successfully predicts customer churn with **reasonable accuracy**.  
This project demonstrates a complete **end-to-end machine learning workflow**, including:
- Data preprocessing  
- Feature selection  
- Model training  
- Validation & performance analysis  

---

## 🚀 **Future Improvements**
- Feature engineering  
- Handling class imbalance  
- Hyperparameter tuning  
- Early stopping & regularization  
- Trying advanced models like **XGBoost** or **Random Forest**

---

## 📁 **Project Structure**
customer-churn-prediction-ann
│
├── Customer_Churn_Prediction.ipynb
├── README.md
└── requirements.txt




⭐ **If you like this project, feel free to star the repository!**

