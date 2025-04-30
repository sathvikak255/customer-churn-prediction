# 📉 Customer Churn Prediction

This project aims to build a machine learning model that predicts customer churn — i.e., whether a customer is likely to leave a service. Accurate churn prediction can help businesses improve customer retention by proactively addressing at-risk users.

---

## 📊 Dataset

- **Source**: [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features**: Customer demographics, account information, service usage, and tenure
- **Target Variable**: `Churn` (Yes/No)

---

## 🧹 Data Preprocessing

- Handled missing values
- Converted categorical variables to numeric using one-hot encoding
- Standardized numerical features using `StandardScaler`
- Split the dataset into training and test sets

---

## 🧠 Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

---

## ⚖️ Model Evaluation

Evaluation metrics include:

- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)
- **ROC-AUC Curve**

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 86.5%    | 0.79      | 0.71   | 0.75     |
| Random Forest      | 89.1%    | 0.83      | 0.77   | 0.80     |
| XGBoost            | 90.2%    | 0.84      | 0.79   | 0.81     |

---

## 📈 Visualizations

### Churn Distribution

![Churn Distribution](images/churn_distribution.png)

---

### Feature Importance (Random Forest)

![Feature Importance](images/feature_importance.png)

---

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## 🛠️ Technologies Used

- Python
- pandas, numpy, seaborn, matplotlib
- scikit-learn
- XGBoost

---

## 📁 File Structure

