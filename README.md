# Skills Programming HSG: CryptoProject Python
Cryptocurrency Portfolio Construction and Performance Analysis\
Project of: Rakeesh Karunakaran & Venjamin Koscica

The aim of the project is that the user inputs several cryptocurrencies of his/ her interest and the code then provides historical performance numbers, risk metrics and optimal weights for this set of crypto assets. The methods used for the performance analysis are equally-weighted portfolio, equal risk contribution and the mean variance approach.

Before running the code, following installations of packages should be run as they are required:

pip install numpy\
pip install pandas\
pip install scipy\
pip install matplotlib\
pip install yahoo_fin\
pip install datetime\
pip install import-ipynb


Use the following link to a list of crypto assets of [Yahoo Finance](https://finance.yahoo.com/cryptocurrencies/) to select the crypto assets of interest. Use the input line in the code to enter the tickers as strings. Always use the the ticker with the suffix "-USD", e.g. "BTC-USD". In details the code does:

1. Get price data from defined starting date up to today
2. For each of the three strategies:
  - Calculate historical performance and plot it
  - Calculate mean return and volatility for period of analysis
  - Calculate the risk metrics Value-at-risk and maximum drawdown
The invested capital is set to 100 by default, but that can be adjusted by the user. The variable "invested_capital" can be changed accordingly.

3. Give summarizing output with all performance metrics, plot with all strategies and the weights of each strategy, where the user could then choose the right strategy and implement the weights of the output.

