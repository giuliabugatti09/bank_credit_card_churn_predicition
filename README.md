# 💳 Bank Churn Intelligence: Predictive Modeling & Financial Impact

> **Strategic Machine Learning solution** designed to identify at-risk credit card customers. By leveraging gradient boosting architectures, the model achieves a high **F1-Score**, enabling proactive retention strategies with a projected financial recovery of **$171K+**.

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![LightGBM](https://img.shields.io/badge/LightGBM-3.3+-0FAA4F?logo=lightgbm&logoColor=white)](https://lightgbm.readthedocs.io/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2+-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

---

## 🎯 Business Case & Objectives
In the banking sector, the **Cost of Acquisition (CAC)** is significantly higher than the cost of retention. This project addresses a **16% churn rate** by:
* **Targeting:** Identifying high-risk customers before they cancel.
* **CLV Optimization:** Increasing **Customer Lifetime Value** through data-driven retention triggers.
* **Operational Efficiency:** Reducing wasted marketing budget on low-risk profiles.

---

## 🏗️ Technical Architecture & Pipeline
Different from basic models, this solution implements a **Production-Ready Pipeline**:

1. **Automated Feature Engineering:** Custom transformers to generate 20+ business metrics (e.g., *Credit Utilization Rate*, *Inactivity Ratio*).
2. **Preprocessing:** Robust handling of categorical data and numerical scaling within a `scikit-learn` Pipeline to prevent **Data Leakage**.
3. **Model Selection:** Benchmark between Linear Models, Random Forest, and **LightGBM**.
4. **Evaluation:** Focus on **F1-Score** and **ROC-AUC** due to class imbalance.

---

## 📈 Model Performance & Metrics
The **LightGBM** classifier was selected for its superior ability to handle sparse data and non-linear relationships.

| Metric | Score | Business Insight |
| :--- | :---: | :--- |
| **ROC-AUC** | **0.91** | High discriminative power between Churners and Loyalists. |
| **F1-Score** | **0.80** | Balanced precision and recall for effective targeting. |
| **Precision** | **85%** | Minimizes "False Alarms" in retention campaigns. |
| **Recall** | **82%** | Captures the vast majority of real churn risks. |

---

## 💰 Financial ROI Analysis
The true value of this project lies in the **Profit-Driven Evaluation**. Instead of focusing only on accuracy, I developed a cost-benefit simulation:

* **Business Scenario:** Assuming an 18% tax on revolving balances.
* **Strategic Gain:** **$171,477 estimated recovery** by applying targeted 10% retention discounts to identified at-risk customers.
* **Budget Optimization:** By identifying **False Positives**, the bank avoids offering unnecessary discounts to customers who weren't planning to leave.

---

## 🔍 Key Churn Drivers (Feature Importance)
The model identified that **transactional behavior** is more predictive than demographics:

1. **Transaction Count (`Total_Trans_Ct`):** The strongest indicator of disengagement.
2. **Revolving Balance:** Customers with zero balance show higher volatility (lower "lock-in" effect).
3. **Contact Frequency:** Sudden spikes in support contacts often precede cancellation.

---

## 📂 Project Governance & Usage
```text
├── notebooks/          # Exploratory Data Analysis 
├  ├── eda.ipynb  
├  ├── modelling.ipynb  
├── requirements.txt    # Project dependencies
└── README.md           # Documentation