
💳 Credit Card Financial Analysis & Data Pipeline
📌 Project Overview
This project provides a comprehensive analysis of credit card operations, focusing on transaction patterns, revenue drivers, and customer demographics. It features an end-to-end data workflow—from SQL database architecture and ETL processes to Power BI visualization—to deliver actionable business intelligence for financial institutions.

🎯 Key Objectives
Revenue Analysis: Track weekly revenue trends, interest earned, and total transaction volumes.

Customer Segmentation: Identify high-value segments based on age, income, and profession.

Operational Efficiency: Monitor Customer Satisfaction (CSS) and delinquency rates.

Strategic Growth: Highlight low-growth areas like online transactions to suggest marketing improvements.

🛠️ Technical Stack
Database: MySQL (Relational Schema Design, Data Loading).

Visualization: Power BI (Interactive Dashboards, Star Schema Modeling).

Analysis: DAX (Custom Measures for Revenue, Interest, and KPIs).

🗂️ Database Architecture
The project utilizes a relational structure with two primary tables:

cc_detail: Contains transaction-level data including annual fees, credit limits, revolving balances, and interest earned.

cust_detail: Stores demographic information such as age, gender, education, income, and job type.

📊 Business Insights & Findings
Performance: Achieved a total revenue of $55.3M with $7.8M in interest earned.

Top Drivers: Blue and Silver card categories dominate, contributing $51.6M to total revenue.

Spending Habits: The highest expenditures were recorded in Bills ($14M) and Entertainment ($10M).

Demographics: Customers aged 40-50 and those with a Graduate level education represent the strongest revenue segments.

🚀 Key Recommendations
Digital Adoption: Launch targeted promotions (cashback/app rewards) to increase the $3M online transaction segment.

Regional Targeting: Scale awareness campaigns in underperforming states like New Jersey and Florida.

Premium Offers: Develop exclusive benefits for the high-income businessman segment (contributing $17.3M in revenue).

📁 Repository Structure
Plaintext

├── sql_scripts/
│   └── database_setup.sql      # Database & table creation scripts
├── data/
│   ├── credit_card.csv         # Transaction datasets
│   └── customer.csv            # Demographic datasets
├── dashboard/
│   └── credit_card_report.pbix  # Power BI Dashboard file
└── README.md
