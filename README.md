# IT-Expenditure-Analysis

Overview

This project presents an interactive IT Expenditure Analysis Dashboard developed using Power BI. The dashboard was designed to help organizations monitor IT-related spending across different regions, departments, and functional areas.
The analysis compares Actual, Forecasted, and Planned expenditures to identify budget variances, spending patterns, and areas where financial optimization may be required.
The main goal of this project was to convert raw financial data into a centralized reporting solution that supports better budgeting decisions and improves financial visibility across the organization.

Business Objective

Managing IT budgets across multiple teams and locations can become difficult when data is fragmented across systems.

This dashboard helps answer key business questions such as:

Are IT departments staying within budget?

Which regions or business units contribute the highest IT costs?

Where are spending inefficiencies occurring?

How accurate are forecasting models compared to actual spending?

Which IT functions consume the majority of the budget?

The project enables stakeholders to evaluate financial performance quickly using interactive visuals and KPI tracking.

Dataset Information

The dataset contains month-wise IT spending records with the following major fields:

Column	Description

Date	Monthly transaction period

Actual	Actual IT expenditure incurred

Forecast	Predicted IT expenditure

Plan	Approved planned IT budget

IT Area	IT functional category

Business Area	Department or business unit

Region	Geographic operating region

Cost Element Group	Expense classification category

Data Cleaning & Transformation

Data preparation was performed using Power Query and DAX inside Power BI.

Steps Included:

Removed incomplete and irrelevant records

Handled null values in financial columns

Corrected data types for dates and currency values

Built a custom calendar table for proper time-based analysis

Established relationships between dimension and fact tables

Filtered zero-value records to improve reporting accuracy


DAX Measures Created:

Variance Amount = Actual – Plan

Variance % = (Actual – Plan) / Plan

Forecast Accuracy

Total Actual Spend

Total Planned Budget

Total Forecast Spend

These transformations ensured accurate calculations and smoother dashboard performance.

Dashboard Features

The dashboard includes multiple interactive visualizations for detailed expenditure analysis.

KPI Cards

Displays:

Total Actual Spend

Total Forecast Spend

Total Planned Budget

Variance Amount

Variance Percentage

Monthly Spending Trends

Clustered column and line charts were used to compare:

Actual spending

Forecast values

Planned budgets

This helps identify seasonal spending behavior and unusual spikes.

Spend Distribution by IT Area

A donut chart visualizes how IT spending is distributed across different functional areas such as:

Infrastructure

Functional IT

BU Support

Governance & Enablement

Regional Expenditure Analysis

Bar charts compare spending across global regions, making it easier to identify high-cost operational areas.

Interactive Filtering

Users can dynamically filter the dashboard using slicers for:

Region

Business Area

IT Area

Cost Element Group

This allows different stakeholders to analyze spending from their own perspective.

Key Insights

Actual IT expenditure remained approximately 3.7% below the planned budget, indicating overall cost control.

Infrastructure and Functional IT account for the majority of organizational IT spending.

The USA region contributes the highest share of IT expenses.

Spending significantly increases toward year-end, especially in December, suggesting bulk procurement or delayed budget utilization.

Governance-related IT functions appear comparatively underfunded.

Recommendations

Improve Forecast Planning

Review forecasting methods in departments showing large variances between forecast and actual spending.

Monitor Year-End Spending

Introduce quarterly budget reviews to prevent excessive end-of-year expenditure spikes.

Optimize Regional Allocation

Evaluate opportunities to balance spending more effectively across regions.

Strengthen Governance Investment

Increase visibility into governance and enablement functions to ensure operational sustainability.

Tools & Technologies Used

Power BI Desktop

Power Query

DAX

Microsoft Excel

Project Structure

IT-Expenditure-Analysis/

│

├── IT_Expenditure_Analysis.pbix

├── IT_Expenditure_Dataset.xlsx

└── README.md


Conclusion

This Power BI dashboard provides a centralized and interactive view of organizational IT spending. By comparing Actual, Forecast, and Planned expenditures, the report helps stakeholders identify financial inefficiencies, monitor budget performance, and make more informed strategic decisions.
The project demonstrates how Power BI can be used to transform raw financial data into actionable business intelligence through effective data modeling, visualization, and storytelling.
