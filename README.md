# Busget-vs-Actual-Financial-Analysis
This project analyzes three years of financial transaction data to compare budgeted amounts against actual spending and identify the departments, expense categories, periods and regions contributing to budget overruns.

**Project Overview**

Management needs visibility into how effectively the company is managing its allocated budget and where unfavorable spending patterns are occurring.
This project analyzes three years of financial transaction data to compare budgeted amounts against actual spending and identify the departments, expense categories, periods and regions contributing to budget overruns.
Objective
Transform raw sales data into meaningful business insights through data cleaning, SQL analysis, interactive dashboards, and data storytelling.

Reporting Period:

January 2021 – December 2023

Records Analyzed:

10,000

Tools:

SQL, Power BI, Excel

**Business Qestions**
1. Are we spending within budget, and how is budget performance changing over time?
2. Which departments are overspending or underspending the most?
3. Which expense categories are contributing most to overspending?
4. Which regions have the best and worst budget performance?
5. What actions should management take to improve budget performance?

**Data Preparaion & Quality Assessment**

The original dataset contained 10,010 records and 8 columns covering transactions from January 2021 to December 2023.
Initial data quality checks identified:
10 exact duplicate records
8 missing values
Missing values across Region, Transaction ID, Category and Department

**Cleaning Approach**

Using SQL, exact duplicate records were removed and missing categorical values were standardized as "Unknown" rather than being arbitrarily assigned to a business category.
The cleaned dataset contained 10,000 records and was then used for analysis and Power BI reporting.

**Analytical Approach**

The analysis followed an end-to-end workflow:
Raw Data → SQL Data Quality Assessment → Cleaning → Business Questions → SQL Analysis → Validation → Power BI Modeling → Dashboard → Insights → Recommendations

Budget variance was calculated as: Actual Spending − Budget
Therefore, Positive variance = Overspending
                Negative variance = Spending below budget
This convention was used consistently throughout the analysis.

