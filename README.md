# 📊 Customer Lifetime Value (CLV) & Churn Prediction

An end-to-end Data Science case study developed for the **Innovexa Catalyst Data Science Challenge**. This project predicts **Customer Lifetime Value (CLV)** and **Customer Churn** using customer demographics, subscription details, transaction history, engagement metrics, and support interactions.

---

## 🚀 Project Overview

Businesses need to understand customer behavior to maximize long-term revenue and reduce customer attrition. This project leverages machine learning techniques to:

- Predict the future Customer Lifetime Value (CLV)
- Identify customers likely to churn within the next 30 days
- Generate actionable business insights for marketing and retention teams

---

## 🎯 Objectives

- Predict Customer Lifetime Value using Regression
- Predict Customer Churn using Classification
- Perform Exploratory Data Analysis (EDA)
- Create meaningful engineered features
- Evaluate model performance
- Generate business recommendations

---

## 📂 Project Structure

```
innovexa-clv-churn-prediction/
│
├── data/
│   ├── customers.csv
│   ├── transactions.csv
│   ├── events.csv
│   ├── support_tickets.csv
│   ├── churn_labels.csv
│   └── clv_labels.csv
│
├── notebooks/
│   └── Customer_CLV_Churn_Prediction.ipynb
│
├── outputs/
│   ├── age_distribution.png
│   ├── gender_distribution.png
│   ├── plan_distribution.png
│   ├── clv_feature_importance.png
│   ├── churn_feature_importance.png
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Exploratory Data Analysis

The project includes:

- Missing Value Analysis
- Duplicate Record Check
- Customer Age Distribution
- Gender Distribution
- Country Distribution
- Subscription Plan Analysis
- Monthly Fee Distribution
- CLV Distribution
- Churn Distribution
- Payment Method Analysis
- Support Ticket Analysis

---

## ⚙️ Feature Engineering

The following features were created:

### Customer Features
- Age
- Gender
- Country
- Plan Type
- Monthly Fee

### RFM Features
- Tenure
- Recency
- Frequency
- Monetary Value

### Engagement Features
- Event Count
- Average Event Value

### Support Features
- Ticket Count
- Average Satisfaction Score
- Refund Count

---

# 🤖 Machine Learning Models

## 1️⃣ Customer Lifetime Value Prediction

### Model

- Random Forest Regressor

### Performance

| Metric | Score |
|-------------|------------|
| MAE | **41.64** |
| RMSE | **52.07** |
| R² Score | **94.90%** |

---

## 2️⃣ Customer Churn Prediction

### Model

- Random Forest Classifier

### Performance

| Metric | Score |
|-------------|------------|
| Accuracy | **89.40%** |
| Precision | **72.73%** |
| Recall | **47.68%** |
| F1 Score | **57.60%** |
| ROC-AUC | **72.25%** |

---

# 📈 Key Insights

### CLV Prediction

- Monetary Value is the most important predictor of Customer Lifetime Value.
- Monthly Subscription Fee significantly influences customer value.
- Premium customers generally have higher CLV.

### Churn Prediction

- Refund Count is the strongest indicator of churn.
- Customers with shorter tenure are more likely to churn.
- Lower spending customers have a higher churn probability.

---

# 💡 Business Recommendations

- Increase customer spending through personalized offers.
- Encourage upgrades to premium subscription plans.
- Monitor refund behavior proactively.
- Identify high-risk customers early using predictive analytics.
- Improve customer engagement and satisfaction to reduce churn.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📌 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Regression
- Classification
- Model Evaluation
- Business Analytics
- Data Visualization

---

# 📷 Project Outputs

The project generates:

- Customer Distribution Charts
- CLV Feature Importance Plot
- Churn Feature Importance Plot
- Confusion Matrix
- Business Insights

---

# 🔮 Future Improvements

- Hyperparameter Optimization
- XGBoost & LightGBM Models
- Customer Segmentation using K-Means
- Interactive Dashboard using Streamlit
- Model Deployment using Flask/FastAPI

---

# 👩‍💻 Author

**Solasa Sahithi Vasavi**

B.Tech – Computer Science Engineering (AI & Data Science)

GitHub: https://github.com/sahithisolasa

---

# ⭐ If you found this project useful, consider giving it a star!