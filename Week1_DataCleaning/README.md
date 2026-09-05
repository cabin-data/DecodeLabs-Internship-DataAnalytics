# Week 1 - Data Cleaning & Preparation

DecodeLabs Data Analytics Internship — Project 1

## What was done
- Audited the raw order dataset (1,200 rows, 14 columns) for missing values, duplicates, and formatting issues
- Checked for duplicate Order IDs, duplicate records, and duplicate Tracking Numbers — none found
- Verified date formatting — already in ISO 8601 (YYYY-MM-DD), no correction needed
- Checked text formatting across Product, Payment Method, Order Status, and Referral Source — consistent, no correction needed
- Checked for whitespace, negative values, and zero values — none found
- Verified TotalPrice = Quantity × UnitPrice on all rows — matched
- Found 309 blank values in the CouponCode column — imputed as "No Coupon" (a blank meant no discount was applied at checkout, not missing/unknown data; mean/median/mode imputation was intentionally avoided since it would have implied a discount that wasn't actually used)

## Result
- 0% duplicate identifiers, 0% incorrectly formatted dates — verification gate passed

## Contents
- Cleaned_Dataset.xlsx — the final cleaned dataset
- Change_Log_Project1.pdf — full documentation of the change made and reasoning
