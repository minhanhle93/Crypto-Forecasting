# Installation

1. Clone the project repository from GitHub: https://github.com/minhanhle93/Crypto-Forecasting
2. Install the required dependencies: 
- pandas
- numpy
- matplotlib
- pathlib
- hvplot
- alpaca_trade_api
- json

3. Download the necessary data for tickers and place them in the appropriate directory. Ensure that you have data files available for each ticker you want to analyze. The data should be in CSV format and contain the necessary price information for the specified 5-year span (from May 1, 2018, to May 1, 2023).

# Usage

- Once the installation steps are complete, you can use the Portfolio Analysis and Monte Carlo Forecasting Tool
- Ensure that you have placed the required data files for the tickers in the appropriate directory
- The tool will start processing the data and performing the analysis. Wait for the analysis to complete.
- Once the analysis is finished, the tool will generate various visualizations and output the results to the terminal.
    - Line Plot: The cumulative returns of each ticker over the 5-year period will be displayed as a line plot.
    - Probability Distribution and Confidence Intervals: The tool will show the probability distribution of cumulative returns along with the lower and upper 95% confidence intervals.
    - Interactive Plot: An interactive plot will be generated to explore the simulated cumulative returns.
    - Mean/Median of Simulated Cumulative Returns: The mean and median values of the simulated cumulative returns will be displayed.
- Review the results and visualizations to gain insights into the portfolio's performance