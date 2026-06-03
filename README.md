# 📊 AI-Powered Delinquency Risk Analysis

---

## 🎯 Project Overview

This project was completed as part of the **Tata iQ GenAI Powered Data Analytics Job Simulation on Forage. The dataset and business scenario were provided for educational purposes**.

The objective was to analyze customer credit behavior, identify delinquency risk factors, assess data quality issues, and design an AI-assisted framework to support proactive collections strategies.

The project follows a complete analytics workflow:

* 📌 Exploratory Data Analysis (EDA)
* 📌 Missing Value Treatment
* 📌 Data Quality Assessment
* 📌 Customer Risk Profiling
* 📌 Predictive Modeling
* 📌 Business Recommendations
* 📌 Responsible & Ethical AI Considerations

---

## 🏢 Business Problem

Geldium Finance has observed an increase in credit card delinquency rates, with more customers missing payments beyond the 30-day late threshold.

The Collections Team requires a data-driven approach to:

* Predict customers at risk of delinquency
* Prioritize intervention efforts
* Improve collection efficiency
* Support fair and transparent AI-driven decision-making

---

## 📂 Repository Structure

```text
AI-Powered-Delinquency-Risk-Analysis/

├── README.md
├── notebooks/
│   └── Tata_IQ_Full_End_to_End_Notebook.ipynb
│
├── reports/
│   ├── Task_1_EDA_Report.pdf
│   ├── Task_2_Predictive_Model_Plan_Report.pdf
    └── Task_3_Business_Summary_Report.pdf
│
├── assets/
│   ├── tata_iq_certificate.png
│   ├── delinquency_distribution.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   └── employment_risk_analysis.png
│
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🛠️ Technology Stack

| Category                | Tools               |
| ----------------------- | ------------------- |
| Programming             | Python              |
| Data Analysis           | Pandas, NumPy       |
| Visualization           | Matplotlib, Seaborn |
| Machine Learning        | Scikit-Learn        |
| Development Environment | Jupyter Notebook    |
| AI Assistance           | Generative AI       |

---

## 📈 Exploratory Data Analysis

The EDA process focused on:

* Understanding dataset structure
* Identifying missing values
* Detecting anomalies and inconsistencies
* Assessing customer risk indicators
* Exploring relationships between variables and delinquency outcomes

### Key Data Quality Findings

| Variable     | Missing Values | Treatment         |
| ------------ | -------------- | ----------------- |
| Income       | 39             | Median Imputation |
| Loan Balance | 29             | Median Imputation |
| Credit Score | 2              | Mean Imputation   |

Additional observations:

* Employment status labels required standardization.
* Credit utilization contained anomalous values.
* The target variable exhibited class imbalance.

---

## 🚨 Key Delinquency Risk Indicators

The following variables were identified as important predictors of delinquency risk:

* Missed Payments
* Credit Utilization
* Debt-to-Income Ratio
* Credit Score
* Income Level
* Payment History

These indicators provide valuable signals for proactive intervention strategies.

---

## 🤖 Predictive Modeling Approach

### Selected Model

**Logistic Regression**

Why Logistic Regression?

* Highly interpretable
* Suitable for financial risk prediction
* Easy to explain to stakeholders
* Supports transparent decision-making

### Data Preparation

* Missing value imputation
* Categorical feature encoding
* Feature scaling using StandardScaler
* Class imbalance handling using `class_weight='balanced'`

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

## 📊 Model Insights

The predictive model was developed primarily as a proof-of-concept framework.

Observations:

* The dataset exhibited class imbalance.
* Delinquency cases represented a relatively small portion of observations.
* Model performance suggests limited predictive signal within the provided dataset.
* Future improvements may include feature engineering, oversampling techniques, and ensemble methods.

---

## 💡 Business Recommendations

### High-Risk Customers

Recommended actions:

* Early collections outreach
* Personalized repayment plans
* Proactive engagement strategies

### Medium-Risk Customers

Recommended actions:

* Automated reminders
* Payment incentives
* Account monitoring

### Low-Risk Customers

Recommended actions:

* Routine monitoring
* Standard customer servicing

---

## ⚖️ Ethical AI Considerations

### Fairness Risk 1

The model may unintentionally disadvantage certain customer groups due to historical data patterns.

**Mitigation:** Conduct regular fairness audits and monitor model performance across customer segments.

### Fairness Risk 2

Over-reliance on automated predictions may lead to inappropriate collection actions.

**Mitigation:** Maintain human oversight and use AI as a decision-support tool rather than a replacement for human judgment.

---

## 📜 Certification

Successfully completed the **Tata iQ GenAI Powered Data Analytics Job Simulation** on Forage.

---

## 🚀 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Missing Value Treatment
* Feature Engineering
* Credit Risk Analytics
* Predictive Modeling
* Business Storytelling
* Responsible AI

---

## 👨‍💻 Author

**Aman Khobragade**

Aspiring AI Engineer & Data Scientist | Machine Learning Engineer | GenAI & Agentic AI Enthusiast

---

### ⭐ If you found this project useful, consider starring the repository.
