# AlgoTrading-Python

Developed three distinct algorithmic trading programs in Python, guided by Nick McCullum's course.
Used the IEX Cloud API for all projects.

Project 1: Equal-Weight S&P 500 Index Fund
- This program leverages batch API calls and Python libraries such as numpy and pandas to compute the number of shares to buy for each S&P 500 constituent. The aim is to achieve an equal-weighted portfolio based on a specified total investment amount.
- The results are exported to a well-organized Excel document using xlsxwriter.

Project 2: Quantitative Momentum Strategy
- This program uses batch API calls and Python libraries like numpy and pandas to identify the top 50 momentum stocks, assessed by various metrics such as price returns over different periods.
It calculates the number of shares to purchase based on a defined portfolio value.
- The findings are exported to a neatly formatted Excel document using xlsxwriter.

Project 3: Quantitative Value Strategy
- Similar to the momentum strategy, this program employs batch API calls and Python libraries (numpy and pandas) to select the top 50 stocks based on value metrics, including P/E ratio, P/B ratio, and P/S ratio.
- It determines the number of shares to buy according to a specified total investment amount.
- The outputs are exported to a structured Excel document using xlsxwriter.
