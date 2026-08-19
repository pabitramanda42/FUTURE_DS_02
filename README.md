📊 FUTURE_DS_02 — Customer Retention & Churn Analysis

<p align="center">
  <b>Future Interns · Data Science & Analytics · Task 2</b><br>
  <i>Turning customer churn data into actionable retention strategy</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Task-02-0B3B82?style=for-the-badge" alt="Task 2">
  <img src="https://img.shields.io/badge/Python-Pandas%20%7C%20NumPy-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

👤 Author

M Pabitra Kumar
Data Science & Analytics Intern — Future Interns

Project: Customer Retention & Churn Analysis
Task: Future Interns — Data Science & Analytics Task 2
Repository: FUTURE_DS_02

🎯 Executive Summary

Customer retention is a critical business challenge for subscription-based companies. Losing customers can reduce recurring revenue, customer lifetime value, and long-term growth.

This project analyzes customer churn and retention behavior to answer four core business questions:

Where is churn happening?
Why are customers leaving?
Which customers are most valuable and vulnerable?
What can the business do to improve retention?

The final solution combines data preparation, exploratory analysis, customer lifetime analysis, churn-driver analysis, and an interactive Power BI dashboard to turn customer data into business-focused recommendations.

💼 Business Problem

The business needs a clear understanding of customer churn in order to:

Identify high-risk customer segments

Understand the major reasons customers leave

Detect vulnerable stages of the customer lifecycle

Understand retention and customer lifetime behavior

Identify high-value customers at risk

Prioritize practical retention initiatives

The analysis is designed to communicate results clearly to a:

Product Manager

Startup Founder

Business Stakeholder

🔎 Project Objectives

#

Objective

01

Measure overall customer churn and retention

02

Identify important churn patterns

03

Analyze key retention drivers

04

Understand customer lifetime / tenure trends

05

Analyze churn categories and reasons where available

06

Identify high-value customers exposed to churn risk

07

Build a client-ready retention dashboard

08

Translate analytical findings into practical recommendations

🛠️ Technology Stack

Tool

Purpose

🐍 Python

Data analysis and preparation

🐼 Pandas

Data cleaning and transformation

🔢 NumPy

Numerical analysis

📈 Matplotlib

Exploratory visualizations

📊 Power BI

Interactive business dashboard

📓 Jupyter Notebook

Reproducible analysis

📁 GitHub

Portfolio and project documentation

🔄 Analytical Workflow

                    ┌──────────────────────┐
                    │   Customer Dataset   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Data Cleaning & QA   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Exploratory Analysis │
                    └──────────┬───────────┘
                               │
                 ┌─────────────┼─────────────┐
                 ▼             ▼             ▼
          Churn Analysis  Retention       Lifetime
                          Analysis         Analysis
                 │             │             │
                 └─────────────┼─────────────┘
                               ▼
                    ┌──────────────────────┐
                    │ Business Insights    │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Recommendations      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Power BI Dashboard   │
                    └──────────────────────┘

📊 Dashboard

The final dashboard is structured into three client-facing pages.

01 — Customer Retention & Churn Overview

Purpose

Provide an executive-level snapshot of customer retention performance.

KPI Layer

Total Customers

Churned Customers

Churn Rate

Retention Rate

Average Tenure

Revenue at Risk

Visual Analysis

Churn by Contract Type

Churn by Tenure Group

Churn by Payment Method

Churn by Internet Type

Interactive Filters

Contract

Gender

Senior Citizen

Internet Type

Payment Method

Tenure Group

Churn Label, where applicable

Business Question

What is happening with customer retention, and which customer segments are most exposed to churn?

02 — Churn Drivers & Reasons

Purpose

Move from what is happening to why it is happening.

Visual Analysis

Churn Category

Top 10 Churn Reasons

Churn by Contract Type

Churn by Monthly Charge

Churn by Satisfaction Score

Churn by Service Type

Business Question

Why are customers leaving?

This page is intended to help stakeholders prioritize the operational and commercial areas that require attention.

03 — Retention & Customer Lifetime Analysis

Purpose

Understand customer lifecycle behavior and identify retention opportunities.

Visual Analysis

Churn Rate Across Tenure

Average CLTV by Tenure

Average Revenue by Tenure

Contract × Tenure Churn Risk Matrix

High-Value Churned Customer Analysis

Retention Recommendations

Business Question

Which customers should the business prioritize, and what actions can improve long-term customer value?

📌 Core Metrics

The project is designed around business-focused KPIs such as:

Metric

Business Meaning

Total Customers

Size of the analyzed customer base

Churned Customers

Customers identified as churned

Churn Rate

Share of customers who churned

Retention Rate

Share of customers retained

Average Tenure

Typical customer lifetime in the available data

Revenue at Risk

Revenue associated with churned customers under the project definition

CLTV

Customer lifetime value, where available

Data integrity note: Final KPI values must come from the actual analyzed dataset. Any example values used in dashboard design mockups are not presented as final analytical results.

🔬 Analysis Areas

Churn Analysis

The analysis examines churn across available dimensions such as:

Contract type

Tenure

Payment method

Internet/service type

Monthly charges

Satisfaction

Customer characteristics

Retention Analysis

Retention patterns are evaluated across:

Lifecycle / tenure groups

Contract segments

Service segments

Customer-value segments

Customer Lifetime Analysis

Available lifetime metrics include:

Tenure in months

Total revenue

Monthly charges

CLTV, where available

Churn rate by tenure group

High-Value Customer Analysis

Where CLTV or another customer-value metric is available, the analysis highlights customers combining:

High customer value + churn exposure

These customers can represent high-priority retention opportunities.

💡 Business Insights Framework

The final project should convert analysis into decisions rather than stopping at charts.

Examples of insight categories include:

🔴 Churn Concentration

Which customer segment has the highest churn rate?

🟠 Lifecycle Risk

At what tenure stage is the customer most vulnerable?

🟡 Commercial Risk

Are pricing or contract structures associated with higher churn?

🔵 Service Risk

Are support, product, or service issues contributing to customer loss?

🟢 Retention Opportunity

Which customer groups show stronger retention and what characteristics do they share?

🟣 Value Risk

Which high-value customers are currently exposed to churn?

🚀 Retention Recommendations

Recommendations should be finalized from the actual analytical results.

01 — Encourage Long-Term Contracts

If short-term customers show higher churn, use:

Loyalty incentives

Contract upgrade offers

Long-term customer benefits

Targeted discounts

02 — Strengthen Early Customer Engagement

If early-tenure customers are more vulnerable:

Improve onboarding

Run early satisfaction checks

Introduce 30/60/90-day engagement

Provide proactive support

03 — Address the Biggest Churn Reasons

Prioritize the largest recorded churn categories/reasons.

Potential actions:

Improve service quality

Resolve billing issues

Improve pricing transparency

Reduce response times

Improve product/service value

04 — Improve Customer Support

If service-related churn is material, strengthen proactive support and issue resolution.

05 — Review Pricing & Value

If price-related churn is significant, evaluate:

Pricing plans

Bundles

Discounts

Value-added services

Competitive positioning

06 — Protect High-Value Customers

Use CLTV/revenue-based segmentation to identify valuable customers who need personalized retention treatment.

🧹 Data Preparation

The project includes standard data-quality checks:

Dataset structure review

Data-type validation

Missing-value analysis

Duplicate checks

Numerical-field conversion

Churn indicator creation

Tenure-group creation

Customer-value segmentation where appropriate

KPI validation

All transformations should be reproducible through the project notebook/scripts.

🧩 Cohort & Lifecycle Note

A true signup-month cohort analysis requires a reliable customer signup/acquisition date.

If the selected dataset does not contain a suitable signup-date field, this project uses:

Tenure-based lifecycle groups and subscription segments

rather than inventing signup dates.

This keeps the analysis transparent, reproducible, and supported by the available data.

📁 Repository Structure

FUTURE_DS_02/
│
├── 📄 README.md
│
├── 📂 data/
│   ├── 📂 raw/
│   │   └── customer_churn.csv
│   │
│   └── 📂 processed/
│       └── cleaned_customer_churn.csv
│
├── 📂 notebooks/
│   └── customer_retention_churn_analysis.ipynb
│
├── 📂 scripts/
│   └── data_cleaning.py
│
├── 📂 dashboard/
│   └── customer_retention_dashboard.pbix
│
├── 📂 reports/
│   └── customer_retention_analysis.pdf
│
├── 📂 images/
│   ├── dashboard_page_1.png
│   ├── dashboard_page_2.png
│   └── dashboard_page_3.png
│
└── 📄 requirements.txt

Keep this section synchronized with the actual files in the repository. Remove entries for files you do not include.

🖼️ Dashboard Preview

Page 1

Customer Retention & Churn Overview

Place final screenshot here:

images/dashboard_page_1.png

Page 2

Churn Drivers & Reasons

Place final screenshot here:

images/dashboard_page_2.png

Page 3

Retention & Customer Lifetime Analysis

Place final screenshot here:

images/dashboard_page_3.png

📈 Expected Business Outcome

This project is designed to help stakeholders:

Identify where churn is concentrated

Understand why customers leave

Detect vulnerable lifecycle stages

Identify high-value customers at risk

Prioritize retention initiatives

Improve customer lifetime value

Support data-informed retention decisions

The goal is:

From customer data → to insight → to action.

⚠️ Limitations

Findings depend on the variables available in the selected dataset.

Association does not automatically imply causation.

Revenue-at-risk values depend on the definition used in the analysis.

True signup-month cohort analysis requires reliable signup dates.

Additional behavioral, product-usage, customer-service, and transaction-level data could improve retention analysis.

🏁 Conclusion

This project transforms customer churn data into a structured retention analysis solution.

By combining:

Data Cleaning → Churn Analysis → Retention Analysis → Customer Lifetime Analysis → Power BI → Recommendations

the project provides a business-oriented framework for understanding customer loss and identifying opportunities to improve retention.

The final dashboard is designed to communicate findings clearly to both technical and non-technical stakeholders.

👨‍💻 Author

M Pabitra Kumar

Data Science & Analytics Intern
Future Interns — Task 2

📚 Internship Reference

This project was completed as part of the Future Interns Data Science & Analytics Internship — Task 2: Customer Retention & Churn Analysis.

The internship brief specifies a retention analysis dashboard/report covering churn reasons, retention trends, customer lifetime analysis, and actionable recommendations. It also recommends documenting completed work in a public GitHub repository using the Data Science & Analytics repository format FUTURE_DS_02.

📜 Disclaimer

This project is prepared for educational and portfolio purposes as part of the Future Interns internship task.

Final conclusions and numerical findings should be interpreted within the limitations of the underlying dataset and analysis methodology.
