README — E-Commerce Transaction & Customer Purchase Analysis

1. PROJECT OVERVIEW

This project focuses on analyzing e-commerce transaction data to understand customer purchasing behavior and identify useful sales patterns.

The analysis looks at purchase amounts across different product categories, countries, age groups, payment methods, and time periods.

The main objective is to use transaction data to find business insights and provide practical recommendations.


2. DATASET

Dataset: E-commerce Transactions Dataset

Records: 50,000
Columns: 8

Main Columns:
- Transaction_ID
- User_Name
- Age
- Country
- Product_Category
- Purchase_Amount
- Payment_Method
- Transaction_Date

The dataset was selected because it contains enough transaction records and different attributes to analyze customer and sales patterns from multiple perspectives.


3. TOOLS USED

- Google Sheets — data organization and analysis
- Google Apps Script — data processing and cleaning
- Pivot Tables — descriptive analysis
- Looker Studio — interactive dashboard
- ChatGPT — supporting guidance during the project


4. DATA PROCESSING

The raw data was processed before performing the analysis.

Major processing steps:
- Removed duplicate Transaction IDs.
- Removed completely blank rows.
- Standardized Age as a numeric field.
- Standardized Purchase Amount as a numeric field.
- Standardized Transaction Date.
- Created Age Groups:
  - Under 18
  - 18–35
  - 36–60
  - 61+

The processed data was stored in the "Processed Data" worksheet.


5. BUSINESS QUESTIONS

The analysis focused on the following questions:

1. Which product categories generate the highest purchase amounts?
2. Which countries contribute the most to total sales?
3. Which age groups have higher purchasing activity?
4. Which payment methods are most commonly used?
5. How does purchase activity change over time?


6. KEY FINDINGS

- Beauty had the highest purchase amount among product categories — $3,057,387.79.
- Australia had the highest purchase amount among countries — $2,514,911.65.
- The 18–35 age group had the highest purchase amount — $8,541,038.11.
- COD was the most frequently used payment method with 8,434 transactions.
- January recorded a purchase amount of $2,157,491.06.


7. RECOMMENDATIONS

1. Focus on the Beauty Category
Maintain product availability and consider targeted promotions because Beauty generated the highest purchase amount.

2. Target the 18–35 Age Group
Consider specific campaigns and offers for this segment because it generated the highest total purchase amount.

3. Optimize Payment Options
Continue providing COD while also encouraging customers to use digital payment methods.


8. DASHBOARD

An interactive Looker Studio dashboard was created to provide an easy-to-understand view of the analysis.

The dashboard includes:
- Total Purchase Amount
- Total Transactions
- Average Purchase Amount
- Purchase Amount by Product Category
- Purchase Amount by Country
- Purchase Amount by Age Group
- Transactions by Payment Method
- Purchase Amount Over Time
- Country Filter

Dashboard Link:
PASTE YOUR LOOKER STUDIO LINK HERE


9. PRESENTATION

A 7-slide presentation was prepared covering:
- Business Problem
- Data & Methodology
- Key Findings
- Deep-Dive Insight
- Recommendations
- Expected Business Impact
- Limitations & Next Steps

Presentation:
Q9 – E-Commerce Transaction & Customer Purchase Analysis


10. LIMITATIONS

The dataset has some limitations:

- It does not contain cost or profit information.
- Quantity information is not available.
- Discount information is not available.
- Deeper customer lifetime analysis is limited by the available transaction data.

Therefore, profitability or profit margin cannot be concluded from this dataset.


11. AI USAGE

ChatGPT was used as a supporting tool to understand the assignment requirements, plan the data-processing steps, and organize the analysis and presentation.

AI-generated suggestions were checked against the dataset before being used.

For example, Transaction_ID was initially considered for transaction activity using its sum, but this was corrected because Transaction_ID is only an identifier. Count of Transaction_ID was used instead, resulting in 8,434 COD transactions.


12. PROJECT FILES

The project folder contains:

- Google Sheet with raw and processed data
- Apps Script code
- Analysis worksheets
- Looker Studio dashboard
- Q9 presentation
- README / Methodology


FINAL NOTE

This project demonstrates the process from raw transaction data to data cleaning, analysis, dashboard creation, business insights, and recommendations.
