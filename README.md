# 📉 Customer Churn Prediction

This project builds a machine learning model to predict whether a customer is likely to churn (i.e., stop using a service). Accurate churn prediction allows businesses to take proactive measures to improve customer retention.

---

## 🧾 Project Objectives

- Analyze customer behavior data to understand key churn indicators
- Apply multiple classification algorithms to model churn
- Evaluate models using relevant metrics focused on recall and F1-score
- Select the best-performing model for potential deployment

---

## 📊 Dataset Overview

- **Source**: Telco Customer Churn Dataset (Kaggle)
- **Records**: Customer account info, service usage, tenure, and demographics
- **Target**: `Churn` (Yes/No)

---

## 🧹 Data Preprocessing

Steps taken:

- Handled missing or inconsistent values
- Categorical encoding (label and one-hot encoding)
- Feature scaling with `StandardScaler`
- Train-test split using stratification to preserve churn ratio

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost

Each model was trained and evaluated on the same dataset for comparison.

---

## 📈 Evaluation Metrics

Models were evaluated using:

- **Accuracy**
- **Precision**
- **Recall** (key metric for churn detection)
- **F1-score**
- **ROC-AUC Score**
- **Confusion Matrix**

---

## ⚖️ Sample Results

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 86.5%    | 0.79      | 0.71   | 0.75     |
| Random Forest      | 89.1%    | 0.83      | 0.77   | 0.80     |
| XGBoost            | 90.2%    | 0.84      | 0.79   | 0.81     |

---

## 🛠️ Modules to Install

Make sure you have Python installed. Then install the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
## 🗂️ File Structure
```bash
customer-churn-prediction/
├── churn_prediction.ipynb    # Jupyter notebook with code and output
├── README.md                 # Project overview
```
## 🚀 Future Enhancements

- Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Try ensemble techniques or stacking
- Implement deep learning models (e.g., ANN)
- Deploy as a Streamlit or Flask web application
- Add user input interface for real-time predictions

## ▶️ How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/sathvikak255/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install required modules (see above)
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook churn_prediction.ipynb
   ```


   
---
