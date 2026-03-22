# Loan Repayment Risk Dashboard

## Project Overview
This project presents an interactive Power BI dashboard for analyzing loan repayment risk using borrower credit characteristics, loan purpose, interest rate, debt-to-income ratio, FICO score, and credit policy status.

## Dataset
- Records: 9,578
- Format: CSV
- Target variable: Not Fully Paid

## Tools Used
- Power BI
- CSV / Excel
- GitHub

## Dashboard Pages

### 1. Risk Overview
The first page provides a high-level view of loan repayment risk, including:
- Total loans
- Loans not fully paid
- Non-payment rate
- Average interest rate
- Average FICO score
- Non-payment rate by loan purpose
- Non-payment rate by FICO band
- Non-payment rate by DTI band
- Non-payment rate by interest rate band

### 2. Policy & Behavior
The second page focuses on borrower credit behavior and lending policy, including:
- Non-payment rate by credit policy status
- Average FICO score by credit policy status
- Non-payment rate by revolving utilization

## Key Insights
- Small business loans show the highest non-payment rate.
- Lower FICO bands are associated with higher non-payment rates.
- Higher interest rate bands correspond to higher repayment risk.
- Higher DTI bands are associated with greater non-payment risk.
- Borrowers who do not meet credit policy show higher non-payment rates.
- Higher revolving utilization is associated with increased repayment risk.

## Dashboard Preview

### Risk Overview
![Risk Overview](Risk%20Overview.jpg)

### Policy & Behavior
![Policy & Behavior](Policy%20%26%20Behavior.jpg)

## Project Files
- `loan-repayment-risk-dashboard.pbix`
- `loan_data.csv`
- `Risk Overview.jpg`
- `Policy & Behavior.jpg`
