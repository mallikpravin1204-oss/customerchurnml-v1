# Customer Churn Prediction (E-Commerce / FinTech)

## 📌 Project Overview

This project predicts customer churn using machine learning models. The goal is to identify customers likely to leave and support business retention strategies.

---

## 📊 Dataset

* Source: Public E-commerce churn dataset
* LINK : https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction?resource=download
* Rows: 5630
* Features: 20
* Target: Churn (0 = No, 1 = Yes)

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn

---

## 🧠 Models Used

* Logistic Regression (Baseline)
* Random Forest
* XGBoost (Best Performing)

---

## 📈 Results

| Model               | Accuracy | F1 Score | ROC-AUC |
| ------------------- | -------- | -------- | ------- |
| Logistic Regression | ~0.81    | ~0.58    | ~0.76   |
| Random Forest       | ~0.86    | ~0.66    | ~0.83   |
| XGBoost             | ~0.88    | ~0.72    | ~0.88   |

---

## 🔥 Key Insights

* Customers with low tenure are more likely to churn
* Higher engagement → lower churn
* XGBoost performs best due to non-linear modeling

---

## ⚖️ Handling Challenges

* Class imbalance handled using SMOTE
* Hyperparameter tuning using GridSearchCV
* Proper train/validation/test split to avoid data leakage

---

## 🚀 Future Work

* Real-time prediction pipeline (Kafka + Spark)
* Deployment using REST API
* Add sentiment analysis (news/social media)

---

## 👨‍💻 Author

Pravin Mallik
