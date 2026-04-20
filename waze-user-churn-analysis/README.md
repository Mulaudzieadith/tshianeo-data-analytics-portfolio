# 📊 Waze User Churn Analysis

## Project Overview
This project analyzes Waze user data to understand patterns associated with user churn and prepare the dataset for future predictive modeling.

## Objectives
- Inspect and understand the dataset
- Identify missing values and assess whether they appear random
- Compare churned users and retained users
- Engineer simple behavioral features to better understand usage patterns
- Summarize findings for future exploratory data analysis and model development

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset
- ~15,000 Waze users
- 13 variables
- Includes user activity, driving behavior, device type, and churn label

## Key Insights
- The dataset contains missing values, primarily in the churn label, and the missingness appears random
- Churned users show more intense but less consistent usage patterns
- Retained users use the app more regularly across more days
- Device type does not appear to have a meaningful relationship with churn
- Median-based comparisons were useful because several variables contain extreme values

## Feature Engineering
Created additional variables to better understand user behavior:
- `km_per_drive`
- `km_per_driving_day`
- `drives_per_driving_day`

## Business Takeaway
Users who churned tended to drive more intensely over fewer days, while retained users showed more consistent usage. This suggests that consistency of app engagement may be more closely related to retention than raw activity volume alone.

## Next Steps
- Perform full exploratory data analysis
- Investigate high-intensity driver segments further
- Explore class imbalance before model development
- Build a churn prediction model
