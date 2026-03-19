# Customer Churn Prediction (SAS Model Studio)

A machine learning project focused on predicting customer churn using SAS Model Studio, aiming to support data-driven business decision-making.

## 📌 Project Overview
This project aims to predict customer churn using machine learning models built in SAS Model Studio. The goal is to identify key factors influencing churn and support data-driven decision-making.

## 🛠️ Tools & Technologies
- SAS Studio
- SAS Model Studio
- Machine Learning (Logistic Regression, Decision Tree, Neural Network)

## ⚙️ Methodology
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model building and evaluation (ROC, AUC)

## 📊 Results
- Developed and compared multiple models (Logistic Regression, Decision Tree, Neural Network)
- Achieved strong predictive performance using ROC-AUC evaluation
- Identified key churn drivers such as contract type and tenure

## 💡 Business Impact
The model enables organizations to identify high-risk customers and implement targeted retention strategies, improving customer loyalty and reducing revenue loss.
## 📸 Project Screenshots

### 🔹 Model Pipeline
![Model Pipeline](pipeline.png)

### 🔹 ROC Curve
![ROC Curve](roc.png)

### 🔹 Accuracy Analysis
![Accuracy](accuracy.png)

### 🔹 F1 Score
![F1 Score](f1 score.png)

### 🔹 Classification Results
![Classification](classification.png)


## 🔍 Model Interpretability

### 🔹 Partial Dependence Plot (PD)
![PD Plot](pd_plot.png)

This plot shows the overall effect of contract type on churn prediction.
- Month-to-month contracts have higher churn probability
- Long-term contracts reduce churn risk

---

### 🔹 PD & ICE Plot
![PD ICE](pd_ice.png)

This visualization combines global and individual-level effects:
- Confirms consistent churn patterns across customers
- Shows variation in individual predictions

---

### 🔹 LIME Explanation
![LIME](lime.png)

This explains a single prediction:
- Contract type has the strongest influence
- Internet service and tenure also contribute
- Provides transparency into model decisions
