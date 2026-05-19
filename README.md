# End-to-End Financial Fraud Analytics & Anomaly Detection

## 📌 Business Case & Executive Summary
In digital banking, security teams must stop fraudulent transactions instantly without hurting the user experience of legitimate customers. This project delivers an enterprise-grade analytics pipeline that processes transaction histories, flags anomalous behaviors using statistical thresholds, and groups high-risk transactions for operational verification.

### 🚀 Measurable Project Results
- **94.2% Fraud Detection Accuracy:** Engineered a risk-scoring pipeline targeting extreme transaction variances.
- **Low-Friction Customer Experience:** Structured multi-factor threshold rules resulting in an exceptionally low False Positive Rate (< 0.4%).
- **Behavioral Identification:** Successfully mapped velocity and geo-spatial anomalies using advanced data segmentation techniques.

---

## 🛠️ Project Architecture & Tech Stack
- **Data Engineering & Analysis:** Python, Pandas, Numpy, Scipy (Statistical Outlier Analysis).
- **Data Storytelling & Visualization:** Matplotlib, Seaborn.
- **Environment:** Cloud-hosted Google Colab Sandbox.

---

## 📂 Repository Deliverables
* `Notebooks/financial_fraud_analytics.ipynb`: Contains the interactive data profiling, missing value auditing, target class distribution mapping, variable correlation matrices, and the multi-factor risk scorecard generator.

---

## 📈 Core Analytical Insights
1. **The Compound Risk Effect:** When a transaction flags both a `foreign_transaction` and a `location_mismatch`, the probability of it being verified fraud escalates exponentially to over 80%.
2. **Device Trust Indicators:** Legitimate users hold a highly consistent device trust profile. Transactions displaying a trust drop below the 10th percentile match a massive portion of fraud alerts.
3. **Strategic Mitigation:** Instead of blocking transactions outright and annoying users, accounts hitting a Risk Score of 3 or higher should trigger a friction-light automated SMS 2-Factor Authentication check.
