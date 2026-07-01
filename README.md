# # Bank Loan Portfolio Performance & Risk Analysis Dashboard

## Project Overview

This project presents an end-to-end analysis of a bank's loan portfolio using Power BI to provide executives with actionable insights into loan performance, borrower behavior, portfolio risk, profitability, and recovery efficiency.

The dashboard was designed to transform raw lending data into a strategic decision-making tool that enables business leaders to monitor portfolio health, identify high-risk lending segments, improve underwriting decisions, and optimize loan recovery performance.

The analysis focuses on key lending metrics including funded amounts, repayment performance, loan status distribution, default exposure, borrower characteristics, loan purposes, and home ownership patterns.

---

# Business Problem

Financial institutions face significant challenges in balancing loan growth with risk management. Without clear visibility into borrower behavior and portfolio performance, lenders may experience:

* Increased loan defaults
* Reduced profitability
* Poor underwriting decisions
* High outstanding loan balances
* Inefficient recovery processes
* Difficulty identifying high-risk customer segments

The organization required a centralized reporting solution capable of providing real-time visibility into lending operations, portfolio performance, and risk exposure.

---

# Project Objectives

The project was designed to answer the following business questions:

### Portfolio Performance

* How much capital has been funded through loans?
* How much payment has been recovered from borrowers?
* What is the overall profitability of the loan portfolio?
* What is the current outstanding exposure?

### Risk Assessment

* What percentage of loans are considered good loans versus bad loans?
* What is the current default rate?
* What financial losses have resulted from loan defaults?
* Which loan statuses contribute most to portfolio risk?

### Borrower Analysis

* What is the average borrower income?
* How does home ownership influence lending performance?
* Which borrower segments present the highest risk?

### Lending Trends

* How does loan funding vary across customer groups?
* Which loan purposes account for the largest share of lending activity?
* How has loan funding changed over time?

### Recovery Performance

* What percentage of funded loans have been recovered?
* How effective are collection and repayment efforts?

---

# Dataset Features

The dataset contains key loan portfolio attributes including:

* Loan ID
* Member ID
* Loan Amount
* Total Funded Amount
* Total Payment Received
* Interest Rate
* Debt-to-Income Ratio (DTI)
* Annual Income
* Loan Status
* Loan Purpose
* Home Ownership
* Employment Information
* Verification Status
* Loan Grade & Sub-Grade
* Issue Date
* Payment Dates

---

# Tools & Technologies Used

| Tool            | Purpose                                                                   |
| --------------- | ------------------------------------------------------------------------- |
| Microsoft Excel | Initial data inspection and validation                                    |
| Power Query     | Data cleaning, transformation, standardization, and modeling              |
| Power BI        | Data modeling, DAX calculations, dashboard development, and visualization |
| GitHub          | Project documentation and portfolio hosting                               |

---

# Project Workflow

## 1. Data Inspection (Excel)

The raw dataset was initially reviewed in Excel to:

* Understand dataset structure
* Identify missing values
* Detect duplicate records
* Validate data consistency
* Review numerical distributions

---

## 2. Data Cleaning & Transformation (Power Query)

The data was prepared using Power Query through:

* Data type corrections
* Null value handling
* Date formatting
* Column standardization
* Data quality validation
* Creation of reporting-ready tables

---

## 3. Data Modeling & Measures (Power BI)

DAX measures were developed to calculate:

* Total Funded Amount
* Total Payment Received
* Recovery Rate
* Default Rate
* Outstanding Amount
* Total Loan Applications
* Total Profit
* Average Interest Rate
* Average Debt-to-Income Ratio
* Total Loss from Default

---

## 4. Dashboard Development

An executive-level dashboard was created to provide a single-page view of:

* Portfolio performance
* Loan quality
* Risk exposure
* Recovery efficiency
* Borrower segmentation

---

# Key Performance Indicators (KPIs)

The dashboard tracks the following strategic metrics:

| KPI                          | Value  |
| ---------------------------- | ------ |
| Total Funded Amount          | $436M  |
| Total Loan Applications      | 39K    |
| Total Payment Received       | $473M  |
| Total Profit                 | $37M   |
| Average Interest Rate        | 12.05% |
| Average Debt-to-Income Ratio | 13.33% |
| Average Annual Income        | $70K   |
| Default Rate                 | 13.82% |
| Total Outstanding Amount     | $19M   |
| Total Loss from Default      | $28M   |
| Recovery Rate                | 56.90% |

---

# Dashboard Analysis & Insights

## 1. Loan Portfolio Performance

The institution funded approximately $436 million across 39,000 loan applications.

The portfolio generated $473 million in repayments, resulting in a positive profit position of approximately $37 million.

This indicates that the loan book is generating returns despite exposure to defaults and bad loans.

### Key Insight

The loan portfolio remains profitable, demonstrating effective lending and repayment performance.

---

## 2. Good Loans vs Bad Loans Analysis

The dashboard categorizes loans into:

### Good Loans

* Represent approximately 86.2% of the portfolio
* Total Funded Amount: $370M
* Total Applications: 33K
* Total Payments Received: $436M

### Bad Loans

* Represent approximately 13.8% of the portfolio
* Total Funded Amount: $66M
* Total Applications: 5K
* Total Payments Received: $37M

### Key Insight

The institution maintains a healthy loan portfolio with over 86% classified as performing loans.

---

## 3. Default Risk Analysis

The portfolio records a default rate of approximately 13.82%.

Defaulted loans contributed to:

* $28M in losses
* Significant outstanding balances
* Reduced recovery efficiency

### Key Insight

While the majority of loans perform successfully, default losses remain a major profitability risk requiring continuous monitoring.

---

## 4. Recovery Performance Analysis

The dashboard reports a recovery rate of approximately 56.9%.

This indicates that more than half of funded loan value has been successfully recovered through borrower repayments.

### Key Insight

Recovery efforts are producing positive results but still present opportunities for further optimization.

---

## 5. Home Ownership Analysis

Borrowers are segmented into:

* Mortgage
* Own
* Rent
* Other/None

The visualization compares funded amounts across ownership categories.

### Key Insight

Home ownership status provides a valuable indicator of borrower stability and lending behavior.

Mortgage and renter categories account for significant portions of funded loans, making them critical segments for future portfolio growth strategies.

---

## 6. Loan Purpose Analysis

The dashboard analyzes borrower demand across multiple loan purposes including:

* Debt Consolidation
* Credit Card
* Home Improvement
* Educational
* Car Financing

### Key Insight

Debt-related borrowing categories represent major drivers of loan demand, providing opportunities for targeted lending products and risk-adjusted pricing strategies.

---

## 7. Interest Rate Analysis

Average portfolio interest rate is approximately 12.05%.

### Key Insight

Current pricing levels are generating positive profitability while maintaining loan demand.

Interest rates should continue to be evaluated against default performance to ensure risk-adjusted returns.

---

## 8. Debt-to-Income (DTI) Analysis

Average DTI is approximately 13.33%.

### Key Insight

The borrower base generally demonstrates manageable debt levels, suggesting reasonable repayment capacity.

DTI remains a critical underwriting indicator for future risk management decisions.

---

## 9. Geographic Funding Distribution

The dashboard visualizes funded amounts by borrower locations.

### Key Insight

Funding concentrations can be identified across specific regions, enabling the business to understand geographic lending patterns and regional risk exposure.

---

# Business Impact

The dashboard enables decision-makers to:

* Monitor portfolio performance in real time
* Reduce default risk exposure
* Improve loan approval strategies
* Strengthen collection processes
* Identify profitable customer segments
* Optimize lending policies
* Support data-driven executive decisions

---

# Recommendations

### 1. Strengthen Underwriting for High-Risk Segments

Review approval criteria for borrower segments associated with higher default rates.

### 2. Improve Recovery Strategies

Implement proactive collection measures for delinquent accounts to improve recovery rates and reduce losses.

### 3. Risk-Based Pricing

Align interest rates more closely with borrower risk profiles to maximize profitability.

### 4. Focus on High-Performing Loan Segments

Increase investment in loan categories and borrower groups demonstrating strong repayment behavior.

### 5. Monitor DTI and Income Metrics

Use affordability indicators more aggressively during loan approval processes.

### 6. Develop Early Warning Risk Models

Leverage borrower characteristics and payment behavior to identify potential defaults before they occur.

---

# Conclusion

The Bank Loan Portfolio Dashboard provides a comprehensive view of lending performance, profitability, borrower behavior, and portfolio risk.

The analysis reveals a largely healthy loan portfolio with 86.2% performing loans, strong repayment activity, and positive profitability. However, default-related losses and outstanding balances highlight the need for continued focus on risk management and recovery optimization.

By leveraging these insights, executives can make informed lending decisions, improve portfolio quality, reduce financial losses, and drive sustainable growth.

---

# Author

**Cosmos Isuru**

Data Analyst | Business Intelligence Analyst | Power BI Developer | Safety/HSE Analyst

Specializing in data analytics, business intelligence, dashboard development, and data-driven decision-making.
