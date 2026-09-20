# 📞 Customer Churn & Retention Analytics Dashboard

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.30%2B-FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.9%2B-3F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)

> An interactive Exploratory Data Analysis (EDA) and business intelligence dashboard designed to identify customer attrition patterns, evaluate revenue loss, and deliver data-backed retention strategies for telecom/subscription services.

---

## 📌 Executive Summary & Problem Statement

Customer churn is one of the most critical metrics for subscription businesses. Acquiring new customers costs up to **5x more** than retaining existing ones. 

The objective of this project is to analyze customer demographic, contract, and behavioral data to answer three core business questions:
1. **What is the current churn rate and recurring revenue impact?**
2. **Which contract types and service profiles represent the highest flight risk?**
3. **What behavioral signals (e.g., support friction, price sensitivity) indicate imminent churn?**

---

## 🔑 Key Business Insights & Strategic Findings

Through multi-variable exploratory data analysis, three primary churn drivers were identified:

* 🚨 **The Contract Lock-in Effect:** Customers on **Month-to-Month contracts** account for **over 80% of all churn**, whereas customers on 1-Year or 2-Year contracts maintain sub-5% churn rates.
* ⚠️ **Support Friction as a Churn Predictor:** There is a critical tipping point at customer service interactions: customers making **3 or more customer support calls exhibit a 90%+ churn rate**, signaling unresolved service frustration.
* 💸 **Price Sensitivity:** Churned users had a significantly higher average monthly bill (**$85.50**) compared to retained users (**$60.20**), indicating strong churn elasticity in higher billing tiers.

---

## 📊 Dashboard Features & Architecture

* **Executive KPI Cards:** Real-time metrics for Total Customer Volume, Churn Rate (%), Retained Accounts, and Total Monthly Recurring Revenue (MRR) Lost.
* **Dynamic Slicing & Filtering:** Multi-select sidebar filters for `Contract Type` and `Internet Service` with instant reactive re-rendering.
* **Interactive Visualizations (Plotly):**
  - **Contract vs. Churn Breakdown:** Grouped Bar Chart highlighting contract tenure vulnerability.
  - **Overall Retention Ratio:** Interactive Donut Chart showing active vs. lost customer proportions.
  - **Service Call Frequency:** Grouped Histogram tracking the threshold where calls trigger attrition.
  - **Billing Distribution:** Box Plots comparing median charges and outlier distribution between churned and active cohorts.
* **Self-Service Data Export:** Built-in CSV download functionality for downstream stakeholder reporting.

---

## 🛠️ Tech Stack & Tools

| Component | Tool / Library | Purpose |
| :--- | :--- | :--- |
| **Language** | Python 3.11 | Core analytical logic and data processing |
| **Data Wrangling** | Pandas | Data cleaning, filtering, and aggregation |
| **Data Visualization** | Plotly Express | Interactive charts with hover tooltips |
| **Web Dashboard** | Streamlit | Rapid, responsive web interface |
| **Version Control** | Git & GitHub | Source code tracking and portfolio hosting |

---

## 💻 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/<YOUR_USERNAME>/customer-churn-analysis.git
cd customer-churn-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the dashboard
```bash
python -m streamlit run app.py
```
*The application will automatically open in your browser at `http://localhost:8501`.*

---

## 📄 Resume-Ready Project Summary (ATS Optimized)

**Customer Churn & Retention Analytics Dashboard** | *Python, Streamlit, Pandas, Plotly*
- Engineered an interactive Exploratory Data Analysis (EDA) dashboard in Streamlit to identify customer attrition patterns across demographic, contract, and billing variables.
- Tracked core business KPIs including Churn Rate (%), Recurring Revenue Loss, and Retention Ratios with dynamic multi-attribute filtering.
- Uncovered that month-to-month contracts drove 80%+ of total churn and flagged 3+ support calls as a 90% churn predictor, delivering actionable customer retention strategies.
- Visualized behavioral distribution patterns using interactive Plotly charts and implemented 1-click CSV data export capabilities for business stakeholders.

---

## 👤 Author
- **Portfolio Project** • Aspiring Data Analyst
- Built with Python, Streamlit, and Plotly.
