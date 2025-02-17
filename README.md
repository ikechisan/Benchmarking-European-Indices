# Benchmarking-European-Indices

## Description
Analysis of 4 European Indices over 5 years (2020-2024) with python(Pandas) and visualization with Tableau

<h2>Data Manipulation</h2>

- Extracted data for FTSE 100, DAX, CAC 40 and Euro Stoxx 50 from Yahoo Finance using yfinance.
- Calculated daily and annual returns and volatilities with numpy.
- Initial plot of Adjusted Closing Prices done with matplotlib.

## Exploratory Data Analysis
Conduct exploratory data analysis to uncover trends, patterns, and key insights within the dataset

## Visualization
Export clean data tables from python into CSV files then use Tableau for visualization.

[Visualization Using Tableau](https://public.tableau.com/views/Europeanindexdashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Results
- The FTSE 100 had the lowest annualized return over the 5-year period, at approximately 1.32%. This indicates relatively modest growth compared to the other indices.
- The DAX had the highest annualized return, at roughly 8.26%. This suggests strong growth in the German stock market over the 5-year period.
- Generally, higher returns come with higher risk. In this case, the DAX, which had the highest annualized return, also has a relatively high volatility. The FTSE 100, which had the lowest return, has the lowest volatility. This illustrates the classic risk-return tradeoff in finance.
