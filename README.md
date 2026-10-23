# Sales Data Analysis (Python + SQL)

Cleaned and analysed a retail sales dataset to find what drives profit and loss.

## What I did
- Checked data quality: missing values, 35 duplicate rows, inconsistent region spelling
- Cleaned the data with Pandas and created new columns (month, year, shipping days, profit margin)
- Answered business questions using SQL (SQLite) and Pandas
- Built charts with Matplotlib

## Key findings
- Overall profit margin is about 4.6%
- Orders with 30%+ discount lose money; no-discount orders earn about 17% margin
- Furniture is loss-making overall (Tables and Bookcases)
- Copiers are the most profitable sub-category; Machines the least
- Sales peak in November and December

## Tools
Python, Pandas, SQL (SQLite), Matplotlib

## Files
- `Sales_Data_Analysis.ipynb`: full analysis
- `superstore_sales_sample.csv`: practice dataset (3,035 rows, includes intentional data-quality issues)

## How to run
Open the notebook in Google Colab, upload the CSV, and run all cells.
