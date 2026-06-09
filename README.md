# AI Jobs Market Analysis

An end-to-end Data Science, Machine Learning, and Business Intelligence project focused on analyzing the global AI jobs market, predicting salaries, and estimating AI automation risk using advanced machine learning models and interactive Power BI dashboards.

---

## 📌 Project Overview
This project investigates the rapidly evolving AI job market by combining:
* Data Cleaning & Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Regression Models
* AI Automation Risk Analysis
* Interactive Power BI Dashboards

### The project answers key business questions such as:
1. Which AI jobs pay the highest salaries?
2. Which skills provide the highest salary premium?
3. Which roles are most vulnerable to AI automation?
4. How accurately can salaries be predicted using machine learning?

---

## 🎯 Project Objectives
* Analyze 15,000 AI job postings
* Predict salaries using regression models
* Engineer an AI Automation Risk Score
* Compare multiple ML models
* Build an interactive 5-page Power BI dashboard
* Deliver actionable business insights

---

## 🛠️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Programming** | Python 3 |
| **Notebook** | Jupyter Notebook |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn |
| **Dashboard** | Power BI |
| **Dataset** | Kaggle AI Jobs Dataset |
| **Version Control** | Git & GitHub |

---

## 🤖 Machine Learning Models Used
* Linear Regression
* Ridge Regression
* Lasso Regression
* Gradient Boosting Regressor
* **Random Forest Regressor** ✅ *(Best Model)*

### Best Model Performance
The Random Forest Regressor achieved the highest predictive accuracy and was selected as the production model.

* **$R^2$ Score:** 0.88
* **MAE:** \$15,635
* **RMSE:** \$21,871

---

## 💡 Key Features

### 💵 Salary Prediction
Predicts AI job salaries based on factors like:
* Experience & Education
* Skills & Premium Skill Presence
* Company Size & Location
* Industry & Remote Ratio

### 🛡️ AI Automation Risk Score
A custom-engineered risk metric ($0–100$) estimating how vulnerable specific jobs are to AI automation based on salary level, experience depth, skill complexity, and job title category.

### 🧪 Feature Engineering
Created advanced features such as:
* Skill Count & Premium Skill Detection
* Days to Apply & Posting Quarter
* Automation Risk Indicators

---

## 📊 Dataset Information

| Property | Value |
| :--- | :--- |
| **Dataset Size** | 15,000 rows |
| **Features** | 20 columns |
| **Missing Values** | 0 |
| **Industries** | 15 |
| **AI Job Roles** | 20 |
| **Countries** | 20+ |

> **Dataset Source:** [Kaggle AI Jobs Dataset](https://www.kaggle.com/)

---

## 📁 Project Structure

```text
AI-JOBS-MARKET-ANALYSIS/
│
├── Dashboard/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   ├── dashboard_page3.png
│   ├── dashboard_page4.png
│   └── dashboard_page5.png
│
├── AI JOBS MARKET ANALYSIS.docx
├── ai_jobs_predictions_final.xlsx
├── feature_importance.xlsx
├── model.ipynb
├── model.pkl
├── model_performance_summary.xlsx
│
├── README.md
└── requirements.txt