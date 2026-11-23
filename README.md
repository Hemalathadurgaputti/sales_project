# sales_project
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hemalathadurgaputti/sales_project/blob/main/sales_project.ipynb)

This project analyzes 2,823 sales order lines from January 2003 to May 2005 using Python and Pandas. I checked the data for missing values and duplicates, converted the order dates, and grouped the sales by product line, month, country, deal size, and customer. The results are shown in 11 charts, and each one has a short insight and recommendation.

## Main findings
- Classic Cars bring in about 39% of total sales (3.92M of 10.03M)
- The USA is the biggest market, with about 36% of sales
- Sales peak every November (about 1.0M a month vs 200K to 450K in most other months)
- Medium-sized deals bring in about 61% of revenue
- Two customers account for about 16% of sales

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Files
- `sales_project.ipynb`: full analysis with charts and insights
- `sales_data_sample.csv`: dataset

## How to run
Click the "Open in Colab" badge above, then choose Runtime → Run all.

To run it locally, install the libraries with `pip install pandas numpy matplotlib seaborn`, then open `sales_project.ipynb` in Jupyter Notebook.

## Limitations
- 2005 covers only five months
- No cost or profit data, so profitability was not analyzed
