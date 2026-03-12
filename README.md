# 💳 Bank Churn Intelligence: Predictive Modeling & Financial Impact

> **Strategic Machine Learning solution** designed to identify at-risk credit card customers. By leveraging gradient boosting architectures, the model achieves an **85% precision rate**, enabling proactive retention strategies with a projected financial recovery of **$171K+**.

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-1.7+-017CEE?logo=xgboost&logoColor=white)](https://xgboost.ai/)
[![LightGBM](https://img.shields.io/badge/LightGBM-3.3+-0FAA4F?logo=lightgbm&logoColor=white)](https://lightgbm.readthedocs.io/)

---

## 🎯 Business Case & Objectives
In the banking sector, the Cost of Acquisition (CAC) is significantly higher than the cost of retention. This project addresses a **16% churn rate** by:
* **Targeting:** Identifying high-risk customers before they cancel.
* **Optimization:** Increasing Customer Lifetime Value (CLV) through data-driven discounts.
* **Profitability:** Reducing unnecessary marketing spend on low-risk profiles.



---

## 📈 Model Performance & Metrics
I conducted a benchmark between 5 different algorithms, with **XGBoost** and **LightGBM** delivering the best balance between precision and recall.

| Metric | Score | Insight |
| :--- | :---: | :--- |
| **ROC-AUC** | **0.91** | Excellent ability to distinguish between churners and loyalists. |
| **Accuracy** | 89% | High overall reliability. |
| **Precision** | 85% | Minimizes "False Alarms" in retention campaigns. |
| **Recall** | 82% | Captures the vast majority of real churn risk. |



---

## 💰 Financial ROI Analysis
The true value of this project lies in the **cost-benefit simulation**:
* **Estimated Recovery:** **$171,477** by applying targeted 10% retention discounts.
* **Efficiency:** By identifying False Positives, the bank avoids wasting budget on customers who weren't planning to leave.



---

## 🔍 Key Churn Drivers (Feature Importance)
Analysis of the model's decision-making revealed:
1.  **Transaction Volume:** Low transaction counts are the strongest indicator of disengagement.
2.  **Spending Patterns:** Sudden drops in average spend precede cancellation by 2-3 months.
3.  **Customer Tenure:** Newer customers exhibit higher volatility; long-term relationship is a protective factor.

---

## 🛠️ Technical Implementation
* **Pipeline:** Automated Feature Engineering (20+ new metrics created).
* **Optimization:** Hyperparameter tuning via Optuna/GridSearchCV.
* **Stack:** Python, Scikit-learn, Pandas, Plotly for interactive business dashboards.

---

## 📂 Project Governance
* `notebooks/`: Comprehensive EDA and model benchmarking.
* `images/`: Performance visualizations and correlation matrices.
* `application.py`: Main script for model inference.

---
**Giulia Bugatti** - *Data Scientist | Software Developer at Viasat Inc.*
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/giulia-bugatti-fonseca-226955267/)
