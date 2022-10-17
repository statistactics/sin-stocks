# Important Note Before Running the Code
- The code is dependent on Stock_Universe.csv to filter for relevant sin and stimulant stocks using NAICS and SIC codes.
    - Please see Instructions.docx (Step 3 in particular) for details on how to retrieve the data from Compustat using WRDS. Thank you, Tilden!

# Details on Code Files
- 1_STOCK_FILTERING.ipynb: Relevant sin and stimulant stocks are selected based on previous literature. Exploratory Data Analysis is also conducted with boxplots, histograms, and descriptive statistics. Outliers are addressed and removed in this notebook.
- 2_PORTFOLIO_AND_REGRESSIONS.ipynb: A long-only, equally weighted Sin and Stimulant portfolios are generated. Regressions are conducted based on Formula 1 and 3 from Salaber, 2009. Additional steps are taken to include the US Recession Indicator from FRED/NBER.
- 3_CORRELATION_ANALYSIS.ipynb: Correlation analysis for portfolio performance against GDP Growth Rate and ExRm (Fama-French) in recessionary vs non-recessionary periods are conducted.

# Hypotheses
1. Sin stocks exhibit a counter-cyclical pattern of returns relative to the business cycle. 
2. Stimulant stocks exhibit a pro-cyclical pattern of returns relative to the business cycle.

