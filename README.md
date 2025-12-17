# Bank Loan Report Analysis

## Project Overview
This project analyses bank loan data to evaluate lending performance, portfolio health, and risk exposure.  
The analysis is built using SQL and Excel dashboards and focuses on key financial and operational metrics used by banks to monitor loan performance.

The project contains **two main dashboards**:
- Summary Dashboard
- Overview Dashboard

Each dashboard addresses different business questions and together they provide a complete view of the loan portfolio.


## Tools Used
- SQL
- Microsoft Excel
- GitHub


## Dashboard 1: Summary Dashboard
**Purpose:**  
Provides a high-level snapshot of the bank’s loan portfolio and overall performance.

**Key Metrics:**
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI)
- Performing vs Non-Performing Loans

**Insights:**
- Performing loans account for the majority of the portfolio
- Non-performing loans represent a smaller but critical risk segment
- Interest rate and DTI differ significantly between loan categories


## Dashboard 2: Overview Dashboard
**Purpose:**  
Provides deeper insights into trends and distributions across different dimensions.

**Key Analyses:**
- Monthly loan application trends
- State-wise loan distribution
- Loan term comparison (36 vs 60 months)
- Loan purpose analysis
- Home ownership impact on loans
- Employment length analysis

---

## Key KPIs Analysed
- Total Loan Applications
- Month-to-Date (MTD) metrics
- Month-over-Month (MoM) changes
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI)
- Good Loans vs Bad Loans


## SQL Analysis
The SQL queries used in this project calculate:
- Core KPIs and financial metrics
- MTD and PMTD comparisons
- Good vs Bad loan classification
- Aggregations by loan status, state, purpose, term, and employment length

All SQL logic is documented in the queries file.


## Repository Structure
Bank-Loan-Report-Analysis/
│
├── data/ → Loan dataset
├── sql/ → SQL queries and KPI calculations
├── dashboards/ → Dashboard images
├── docs/ → Problem statement and domain knowledge
└── README.md
