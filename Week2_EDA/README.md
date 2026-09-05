# Week 2 - Exploratory Data Analysis (EDA)

DecodeLabs Data Analytics Internship — Project 2

## What was done
- Calculated basic statistics (mean, median, standard deviation, min, max, count) for Quantity, UnitPrice, and TotalPrice
- Detected outliers in TotalPrice using the IQR method (Q1 = 410.52, Q3 = 1,578.48, IQR = 1,167.96)
- Found 8 outlier orders, all ranging from $3,334 to $3,456 — likely genuine large purchases rather than data errors, since UnitPrice and Quantity showed no anomalies in these rows
- Built a correlation matrix across Quantity, UnitPrice, TotalPrice, and ItemsInCart to check relationships between variables
- Built summary tables (using COUNTIF/SUMIF/AVERAGEIF formulas) breaking down order count, revenue, and average order value by Product, Order Status, Payment Method, and Referral Source
- Summarized key business observations based on the findings above

## Key findings
- Average order value ($1,053.97) is notably higher than the median ($823.62), indicating a small number of high-value orders pull the average upward
- UnitPrice has the strongest correlation with TotalPrice (0.72), while Quantity and UnitPrice show almost no relationship (0.01)
- Cancelled and Returned orders together make up nearly 41% of all orders — worth further investigation
- Instagram is the top referral source by order count

## Contents
- My_Project_2_Data_Analytics_DecodeLab.xlsx — full analysis workbook (Basic Stats, Outlier, Correlation, Summary Table, Key Observation tabs)

Dataset: Same cleaned dataset from [Week1_DataCleaning/My Cleaned Dataset for Week1.xlsx](../Week1_DataCleaning/My%20Cleaned%20Dataset%20for%20Week1.xlsx)
