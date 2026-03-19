# Customer Churn Prediction (SAS Model Studio)

A machine learning project that predicts customer churn using SAS Model Studio, combining predictive modeling and explainable AI techniques (PD, ICE, LIME) to support business decision-making.

## 📌 Project Overview
This project aims to predict customer churn using machine learning models built in SAS Model Studio. The goal is to identify key factors influencing churn and support data-driven decision-making.

## 📂 Dataset
The dataset contains customer information such as:
- tenure
- contract type
- monthly charges
- internet service

Used to classify whether a customer will churn.

## 🛠️ Tools & Technologies
- SAS Studio
- SAS Model Studio
- Machine Learning (Logistic Regression, Decision Tree, Neural Network)

## 🚀 Key Skills Demonstrated
- Predictive modeling using SAS
- Model evaluation (ROC, Accuracy, F1)
- Explainable AI (PD, ICE, LIME)
- Business insight generation

## ⚙️ Methodology
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model building and evaluation (ROC, AUC)
  
## 📊 Results
- ROC-AUC: 0.84
- Accuracy: 78%
- F1 Score: 0.62

- Developed and compared multiple models (Logistic Regression, Decision Tree, Neural Network)
- Identified key churn drivers such as contract type and tenure

## 📸 Project Screenshots

### 🔹 Model Pipeline
![Model Pipeline](pipeline.png)

### 🔹 ROC Curve
![ROC Curve](roc.png)

### 🔹 Accuracy Analysis
![Accuracy](accuracy.png)

### 🔹 F1 Score
![F1 Score](f1_score.png)

### 🔹 Classification Results
![Classification](classification.png)


## 🔍 Model Interpretability

### 🔹 Partial Dependence Plot (PD)
![PD Plot](pd.png)

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

## 💡 Business Impact
The model enables organizations to identify high-risk customers and implement targeted retention strategies, improving customer loyalty and reducing revenue loss.
