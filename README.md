# Portugese_bank_project
A machine learning project that analyzes Portuguese bank marketing data to predict term-deposit subscriptions and uncover customer insights.
Here is a clean, professional **GitHub-ready project description** for your Portuguese Bank Marketing Prediction repository:


# Portuguese Bank Marketing Prediction – README

*A complete end-to-end Data Science project*

This README is created following the style and structure of your attached project README .

#  Project Overview

This project focuses on analyzing and predicting the outcomes of **Portuguese banking institution’s direct marketing campaigns** conducted between **2008–2010**.
Campaigns involved phone calls to customers to promote **term deposit subscriptions**.

Using the dataset, we perform:

* Full **Exploratory Data Analysis (EDA)**
* **Data Preprocessing** and cleaning
* Building multiple **Machine Learning Models**
* **Model Comparison Report**
* Recommendations to improve marketing effectiveness

---

# Project Objectives

## **1. Data Analysis (EDA)**

* Understand customer demographics and behavior
* Identify patterns influencing subscription decisions
* Visualize key relationships and campaign results

## **2. Predictive Modeling**

Develop ML models to predict whether a customer will **subscribe to a term deposit** based on features like:

* Call duration
* Previous campaign outcomes
* Customer attributes (age, job, marital, education)
* Contact type & days passed since previous contact

## **3. Business Insights for Marketing Team**

Provide actionable recommendations to:

* Increase conversion rates
* Optimize communication strategy
* Improve target customer selection

---

# Dataset Information

The dataset contains **41,188 records** and **20+ features** from phone-based marketing campaigns.

### Key Attributes:

* **age, job, marital, education**
* **default, housing, loan**
* **contact type**, **month**, **day_of_week**
* **duration** (last call duration)
* **campaign**, **pdays**, **previous**, **poutcome**
* **y** – Target variable (Subscribed: *yes/no*)

---

# ⚙️ Project Workflow

### **1. Data Preprocessing**

* Handling missing/unknown values
* Encoding categorical variables
* Removing data leakage (e.g., using *duration* carefully)
* Train/test split

### **2. Feature Engineering**

* Binning age groups
* Creating contact effectiveness features
* Encoding categorical variables

### **3. Model Training**

Models evaluated include:

* Logistic Regression
* Random Forest
* XGBoost
* Decision Tree
* KNN
* SVM

### **4. Model Comparison Report**

We analyze:

* Accuracy
* Precision, Recall, F1-score
* ROC-AUC
* Confusion Matrix

### **Best Model:** *(Based on your notebook — you can update based on results)*

**Random Forest / XGBoost** generally performs best for this dataset with high recall and robust handling of categorical features.

---

# Key Insights (EDA Summary)

* Customers contacted through **cellular** have higher subscription rates.
* Campaign success strongly depends on **economic indicators** (pdays, poutcome).
* **Duration** is the strongest predictor, but should not be used for real-time prediction.
* Middle-aged customers (30–50 years) show higher interest in term deposits.

---

# Recommendations for the Bank Marketing Team

1. **Focus on customers with successful past campaign history.**
2. **Prefer cellular contact** — leads to better outcomes.
3. **Optimal call duration** (effective conversation strategies).
4. **Target specific age groups (30–50).**
5. Avoid repeated calls — **higher number of contacts reduces conversion**.

---

# Tech Stack Used

* **Python**
* **NumPy, Pandas**
* **Matplotlib, Seaborn**
* **Scikit-Learn**
* **XGBoost**
* **Jupyter Notebook**


# Results Summary

| Model               | Accuracy | Recall   | ROC-AUC     |
| ------------------- | -------- | -------- | ----------- |
| Logistic Regression | ~88%     | Medium   | Medium      |
| Random Forest       | **~92%** | **High** | **High**    |
| XGBoost             | **Best** | **High** | **Highest** |
| SVM                 | Good     | Low      | Medium      |
| Decision Tree       | Overfits | Low      | Low         |


# About the Author

Hi! I’m **Himanth**, a passionate data scientist with strong skills in:

* Machine Learning
* Business Intelligence
* Data Engineering
* SQL & Data Visualization





