# 👥 Employee Attrition Analysis

A statistical analysis project aimed at understanding and predicting employee attrition through demographic, performance, and engagement data.

---

## 📌 Project Overview

This project examines employee data to identify patterns and risk-factors associated with attrition (voluntary or involuntary). It includes exploratory analysis, hypothesis testing, feature engineering, statistical modelling, and actionable insights for HR professionals. The goal is to help organisations understand why employees leave and build strategies to improve retention.

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔄 Workflow Summary

### 1. Data Collection

Dataset includes features such as: employee ID, age, gender, department, job role, tenure, salary, job satisfaction, years since last promotion, number of trainings, and target variable indicating attrition (Yes/No).

### 2. Exploratory Data Analysis (EDA)

* Distribution of employees who left vs stayed by age, tenure, job satisfaction
* Boxplots/histograms of key features grouped by attrition status
* Correlation matrix for numeric features and attrition flag
* Summary statistics by department and role to identify high-attrition segments
* Check missing values, skewness and outliers

### 3. Hypothesis Testing & Feature Engineering

* Example hypotheses to test: “Employees with fewer trainings are more likely to leave” or “Higher job satisfaction reduces attrition risk”
* Use t-tests or chi-square tests to compare means/proportions between attrited vs retained groups
* Create derived features: e.g., tenure categories, ratio of years since last promotion to total years, training per year
* Encode categorical features (department, job role, gender) and scale numeric features if needed

### 4. Statistical Modelling & Interpretation

* Fit logistic regression or other classification models to predict attrition and interpret coefficients
* Use odds-ratios to quantify effect sizes of key predictors (e.g., odds of leaving if job satisfaction is low)
* Validate model (e.g., via cross-validation) and assess performance (accuracy, precision, recall)
* Analyse residuals and model assumptions

### 5. Insights & Business Application

* Identify top risk factors for attrition: e.g., low job satisfaction, long tenure without promotion, lack of training
* Provide actionable HR recommendations: enhanced training, promotion pathways, targeted retention programmes for high-risk roles
* Segment employees by risk and recommend monitoring or interventions

---




## 📈 Key Findings

* Employees with **low job satisfaction** and **long tenure without a promotion** had a significantly higher risk of leaving.
* Departments/roles with less frequent training or promotion opportunities showed elevated attrition rates.
* Statistical tests confirmed differences in means/proportions (e.g., training per year) between attrited vs retained employees.
* Logistic regression revealed that an increase in years since last promotion was one of the strongest predictors of attrition (odds-ratio > X).


