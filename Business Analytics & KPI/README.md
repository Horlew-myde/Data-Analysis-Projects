# Business Analytics & KPI Dashboards Project Series

## 📖 Introduction

This repository contains a series of six data analysis projects designed to simulate real-world business challenges. The primary objective was to move beyond basic data exploration and focus on answering business-centric questions, identifying Key Performance Indicators (KPIs), and deriving actionable insights. All analyses were conducted in Python using core data science libraries.

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas:** For data manipulation and cleaning.
* **Matplotlib & Seaborn:** For data visualization and creating insightful plots.
* **Jupyter Notebook:** For interactive analysis and documentation.

---

## 🚀 Projects Overview

This series covers a range of common business problems, from sales performance to fraud detection.

* **1. Retail Sales Analysis:**
    * **Question:** Where are the hidden profit drains in our sales data?
    * **Insight:** Discovered that the 'Furniture' category, despite having strong sales, was a major drain on profitability due to specific loss-making products like 'Tables'.

* **2. Telco Customer Churn:**
    * **Question:** What does a high-risk customer who is about to churn look like?
    * **Insight:** Identified a clear high-risk profile: customers on flexible month-to-month contracts with low tenure.

* **3. A/B Test Analysis:**
    * **Question:** Did our new webpage design actually improve user conversion?
    * **Insight:** Proved with statistical significance (p-value > 0.05) that the new design had no positive impact, preventing a costly and ineffective site change.

* **4. Employee Attrition:**
    * **Question:** Why are we losing valuable employees?
    * **Insight:** Found strong correlations between attrition and two key factors: working overtime and low monthly income, highlighting issues with burnout and compensation.

The following would be done and updated in the nearest future
* **5. Marketing Campaign ROI:**
    * **Question:** Is our marketing budget being spent effectively?
    * **Insight:** Revealed that one specific campaign and a single age demographic (30-34) were responsible for the most cost-effective customer acquisitions (lowest CPA).

* **6. Credit Card Fraud Detection:**
    * **Question:** What are the tell-tale signs of a fraudulent transaction?
    * **Insight:** Identified powerful behavioral markers for fraud, such as transactions being online, far from home, and for amounts significantly higher than a user's average.

---

## 🧠 Key Cross-Project Insights

Across these diverse datasets, several recurring themes emerged that are fundamental to effective business analytics:

1.  **The Power of Segmentation:** In almost every project, looking at aggregated data told an incomplete story. True insights were only uncovered by segmenting the data—whether by product category, customer contract type, age group, or job role. This consistently revealed the top performers and the biggest problem areas.

2.  **Efficiency Metrics Trump Volume Metrics:** Projects like the Retail Sales and Marketing Campaign analyses showed that focusing only on volume (e.g., total sales, total clicks) can be misleading. The most valuable insights came from efficiency metrics like **Profit Margin** and **Cost Per Acquisition (CPA)**, which measure the return on investment.

3.  **Behavior is More Predictive Than Demographics:** While demographics can be useful, behavioral data proved to be a far more powerful predictor of future outcomes. How a customer uses a service (`Contract Type`), how much they spend relative to their average (`ratio_to_median_purchase_price`), or whether an employee works overtime are all strong signals that can inform proactive business strategies.

---

## 📂 How to Use This Repository

To explore these analyses yourself:

1.  Clone the repository: `git clone <repository-url>`
2.  Navigate to the project directory: `cd <repository-name>`
3.  Each project is contained within its own Jupyter Notebook (`.ipynb`) file for easy exploration.
