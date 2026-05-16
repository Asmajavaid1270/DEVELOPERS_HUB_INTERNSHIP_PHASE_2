# DEVELOPERS_HUB_INTERNSHIP_PHASE2

# 📊 Term Deposit Subscription Prediction

## 📌 Project Overview

This project was completed as part of the Data Science & Analytics Internship at DevelopersHub Corporation.

The objective of this project is to predict whether a bank customer will subscribe to a term deposit based on marketing campaign data using Machine Learning classification models.

---

# 🎯 Objective

The main goal of this project is to:

* Analyze customer marketing data
* Build classification models
* Predict customer subscription behavior
* Evaluate model performance
* Apply Explainable AI (XAI) using SHAP

---

# 📂 Dataset

Dataset Used:

* Bank Marketing Dataset
* Source: UCI Machine Learning Repository

Target Variable:

* `y` → Whether the customer subscribed to a term deposit (`yes/no`)

---

# 📊 Project Workflow

## 1️⃣ Data Loading

* Imported dataset using Pandas
* Explored dataset structure and features

## 2️⃣ Data Preprocessing

* Handled categorical variables
* Applied feature encoding
* Checked missing values
* Prepared data for modeling

## 3️⃣ Exploratory Data Analysis (EDA)

Performed:

* Distribution analysis
* Correlation analysis
* Class balance visualization
* Feature relationship analysis

## 4️⃣ Model Building

Implemented classification models:

* Logistic Regression
* Random Forest Classifier

## 5️⃣ Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* F1-Score
* ROC Curve
* Classification Report

## 6️⃣ Explainable AI (XAI)

Used SHAP (SHapley Additive Explanations) to:

* Explain feature importance
* Interpret model predictions
* Visualize feature impact on predictions

---

# 📈 Results

### Random Forest Performance

* High prediction accuracy
* Better classification performance compared to Logistic Regression

### SHAP Insights

Important features influencing predictions included:

* Duration
* Balance
* Age
* Campaign
* Previous Outcome

---

# 📷 Visualizations Included

* Count Plots
* Correlation Heatmap
* Confusion Matrix
* ROC Curve
* SHAP Summary Plot

---

# 🚀 How to Run the Project

## Clone Repository

```bash
git clone https://github.com/your-username/bank-marketing-prediction.git
```


---

# ✨ Conclusion

This project demonstrates how Machine Learning can help banks identify potential customers likely to subscribe to term deposits. The use of SHAP improved model transparency and interpretability, making the predictions easier to understand and explain.
