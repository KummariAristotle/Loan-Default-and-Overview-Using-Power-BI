Loan Default Analysis & Risk Assessment | Power BI Project
Overview

This project analyzes loan default patterns and evaluates financial risk factors using Power BI. The aim is to understand borrower characteristics that contribute to loan defaults and provide actionable insights for better credit risk management.

By combining borrower demographics, financial attributes, and loan information, the interactive dashboard offers a comprehensive view of loan performance and risk. The insights help financial institutions make data-driven decisions to reduce credit losses and improve lending strategies.

Problem Statement

Loan defaults result in significant losses for financial institutions. The challenge is identifying high-risk borrowers before approving loans.

This project seeks to answer:

What factors influence loan defaults?

Which borrower profiles are more likely to default?

How do income, financial obligations, and demographics impact repayment?

Can borrowers be segmented into risk categories to improve lending decisions?

The goal is to create a framework that minimizes default risk while supporting smarter loan approvals.

Dataset

The dataset includes information on:

Demographics:

Age

Employment Status

Education Level

Marital Status

Residential Status

Financial Attributes:

Annual Income

Loan Amount

Credit Score

Debt-to-Income Ratio

Existing Liabilities

Loan Information:

Loan Status

Loan Purpose

Default Indicator

These variables allow an in-depth analysis of borrower behavior and default risk.

Data Preparation & Modeling

The dataset underwent cleaning and structuring before analysis:

Data Cleaning: Removed missing or inconsistent entries, standardized financial metrics, and verified categorical values.

Data Modeling: Organized data into a relational model with tables such as:

Borrower Information

Loan Details

Financial Indicators

This model supports multi-dimensional analysis and drives the interactive Power BI dashboards.

Key Metrics (DAX KPIs)

The dashboards use calculated measures to evaluate loan performance and risk:

Total Loan Applications: Count of loan applicants

Total Loan Amount: Total capital disbursed

Default Loan Count: Number of defaulted loans

Default Rate: Percentage of loans in default

Average Borrower Income: Financial capability assessment

Average Loan Size: Average value of loans issued

Risk Category Distribution: Segmentation into Low, Medium, High risk

These KPIs form the backbone of the dashboard analytics.

Dashboard Pages
Page 1: Default Loan Overview

Purpose: High-level view of loan distribution and defaults

Insights: Shows default vs non-default ratios and total loans issued

Business Value: Helps management quickly assess credit exposure and default trends

Page 2: Demographics & Financial Profile

Purpose: Explore borrower characteristics that affect repayment

Insights:

Higher default probability in certain age and employment groups

Lower-income borrowers experience more financial stress

Higher debt-to-income ratios correspond to higher default risk

Business Value: Supports improved credit scoring and loan approval criteria

Page 3: Financial Risk Matrix

Purpose: Evaluate risk based on creditworthiness, income stability, and repayment capacity

Risk Segmentation: Low Risk | Moderate Risk | High Risk

Insights: Highlights borrowers with high loan amounts but low repayment capacity and risk clusters requiring closer monitoring

Business Value: Supports risk-based interest rates and early-warning systems

Key Insights

Borrowers with higher debt relative to income are more likely to default.

Certain demographic groups show greater financial vulnerability.

Loan amounts exceeding repayment capacity significantly contribute to defaults.

Risk segmentation allows focused monitoring of high-risk borrowers.

Recommendations

Risk-Based Loan Approval: Factor in income stability and debt burden.

Enhanced Credit Scoring: Include demographic and financial indicators for more accurate predictions.

Risk-Based Interest Rates: Mitigate default risk by adjusting rates based on borrower risk.

Monitoring High-Risk Borrowers: Implement early-warning systems for potential defaults.

Business Impact

Applying these insights can help financial institutions:

Reduce loan default rates

Improve credit decision-making

Increase profitability

Strengthen portfolio risk management
