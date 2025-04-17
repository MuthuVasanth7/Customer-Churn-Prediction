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

> *Note: Dataset source - [Insert source if public, e.g., Kaggle link]*

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / Random Forest (if used)
- Jupyter Notebook / VS Code

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values
- Visualized distributions and correlations
- Explored patterns between churn and various features
- Feature engineering where applicable

---

## 🤖 Models Trained

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| XX%      | XX%       | XX%    | XX%      |
| Random Forest      | XX%      | XX%       | XX%    | XX%      |
| XGBoost            | XX%      | XX%       | XX%    | XX%      |

> *Model performance based on test set evaluation.*

---

## 🧪 Evaluation Metrics

- Confusion Matrix
- ROC-AUC Curve
- Classification Report
- Cross-validation

---

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

---

## 📬 Contact

For questions or feedback, feel free to reach out:

**Muthu Vasanth**  
[pvsbym@gmail.com]

---

⭐️ If you found this useful, give it a star on GitHub!


