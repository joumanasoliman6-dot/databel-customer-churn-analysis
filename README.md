# 📊 Databel Customer Churn Analysis Dashboard

An interactive Power BI dashboard analyzing customer retention and churn dynamics for **Databel**. This project identifies primary churn drivers, high-risk customer segments, and financial impacts to help inform data-driven retention strategies.

---
DASHBOARD OVERVIEW [Dashboard.pdf](https://github.com/user-attachments/files/31027915/Dashboard.pdf)



---
## 📌 Key Metrics Overview

* **Total Customers:** 6,687
* **Churned Customers:** 1,796
* **Overall Churn Rate:** 26.86%
* **Total Charges:** $7.0 Million
* **Average Monthly Charge:** $31

---

## 🔍 Key Insights & Analysis

### 1. Top Reasons for Churn
 Competitive offers are the leading cause of customer loss:
* **Competitor made better offer:** 303 customers
* **Competitor had better devices:** 297 customers
* **Attitude of support person:** 203 customers
* **Competitor offered more data:** 110 customers

### 2. Service Calls & Retention Risk
* Churn rate drastically increases with customer service interactions.
* Customers making **3 or more customer service calls** experience a churn rate exceeding **87%**, reaching **100%** at 5 calls.

### 3. Contract Type & Demographics
* **Month-to-Month Contracts** exhibit the highest churn rates (~40%–47% across genders).
* **Two-Year Contracts** show superior retention, with churn rates dropping to **3%**.
* Older age demographics (65+) display significantly higher churn rates compared to younger bins.

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop** – Data modeling, DAX measures, visual design, and interactive dashboards.
* **Data Visualization** – Bar charts, line graphs, gauge charts, and geospatial maps.

---

## 📁 Repository Structure

```text
├── data/
│   └── databel_churn_dataset.csv     # Raw/Processed dataset
├── reports/
│   └── Databel_Churn_Analysis.pbix  # Power BI Dashboard file
├── images/
│   └── dashboard_preview.png         # Screenshot of the dashboard
└── README.md                         # Project documentation
