# 📉 Customer Churn Prediction

This project aims to predict whether a customer will churn (leave) or stay with a service using machine learning techniques. The model is trained on customer data and leverages various features related to user behavior and account information to make accurate predictions.

## 📌 Problem Statement

Customer churn is a critical metric for subscription-based businesses. Being able to predict churn in advance allows companies to take proactive actions to retain their customers. This project uses historical customer data to train machine learning models to predict churn status.

---

## 📂 Dataset

The dataset contains customer details such as:
- Demographic information (Gender, Age)
- Account information (Contract type, Tenure, Payment Method)
- Services subscribed (Internet, Streaming, Tech Support)
- Monthly and Total charges
- Target variable: `Churn` (Yes/No)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / Random Forest / SVM
- Jupyter Notebook / VS Code

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values
- Visualized distributions and correlations
- Explored patterns between churn and various features
- Feature engineering where applicable

---

## 🤖 Models Trained

| Model              | Accuracy | Precision | Recall  | F1      | ROC AUC |
|--------------------|----------|-----------|---------|---------|---------|
| Gradient Boosting  | 0.791045 | 0.637931  | 0.494652| 0.557229| 0.839909|
| Random Forest      | 0.725657 | 0.490164  | 0.799465| 0.607724| 0.836599|
| Logistic Regression| 0.725657 | 0.490099  | 0.794118| 0.606122| 0.834218|
| XGBoost            | 0.727790 | 0.492487  | 0.788770| 0.606372| 0.833914|
| SVM                | 0.686567 | 0.450517  | 0.815508| 0.580400| 0.826163|


## 🧪 Evaluation Metrics

- Confusion Matrix
- ROC-AUC Curve
- Classification Report
- Cross-validation


## 💡 Key Insights

- Customers with month-to-month contracts churn more often
- High monthly charges correlate with higher churn probability
- Lack of tech support and online security increases churn likelihood

---

## 🚀 Future Work

- Integrate real-time churn prediction using a web interface (Streamlit/Flask)
- Use more advanced feature selection techniques
- Tune models using GridSearchCV
- Address class imbalance using SMOTE or similar techniques

