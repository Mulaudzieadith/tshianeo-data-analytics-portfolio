# Unicorn Companies Time-to-Valuation Analysis

## Project Overview

This project analyzes a dataset of 1,074 unicorn companies to explore how long companies take to reach a $1B valuation.

The analysis focuses on structuring date fields, creating time-based features, and identifying patterns by founding year, month joined, and quarter joined.

## Business Problem

An investing firm wants insights into unicorn companies to help identify patterns that may support future investment decisions.

This project explores:

- When unicorn companies were founded
- How long companies took to reach unicorn status
- Which months had lower median time-to-unicorn values
- How average valuations differed across quarters in 2020 and 2021

## Dataset

The dataset used is `Unicorn_Companies.csv`.

It contains:

- 1,074 rows
- 10 columns
- Company names
- Valuation
- Date joined
- Industry
- City
- Country/Region
- Continent
- Year founded
- Funding
- Select investors

## Tools Used

- Python
- pandas
- NumPy
- seaborn
- matplotlib
- Jupyter Notebook

## Key Steps

- Loaded and inspected the dataset
- Checked for duplicates
- Reviewed column data types
- Sorted companies by year founded
- Counted companies founded per year
- Converted `Date Joined` to datetime format
- Created `Month Joined`
- Created `Years To Join`
- Filtered companies that joined in 2021
- Grouped companies by week joined
- Compared average valuation by quarter for 2020 and 2021
- Created box plots and bar charts for analysis

## Key Insights

- 2015 had the highest number of companies founded in the dataset.
- Many companies founded in 2021 were based in the United States and belonged to industries such as fintech, e-commerce, and internet software services.
- Companies that joined in September and October had lower median `Years To Join` values.
- In 2021, Week 37 had the highest number of companies reaching $1B valuation.
- Average valuation patterns differed between 2020 and 2021 by quarter.

## Limitations

This dataset only includes companies that had already reached unicorn status by March 2022. This may create time-based bias because newer companies have had less time to appear in the dataset.

The analysis also depends on the countries, industries, and companies included in the dataset, so it may not fully represent every startup market globally.

## Files

- `unicorn_time_to_valuation.ipynb` - full analysis notebook
- `Unicorn_Companies.csv` - dataset

## Author

Tshianeo Eadith Mulaudzi
