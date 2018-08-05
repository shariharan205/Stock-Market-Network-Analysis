# Stock-Market-Network-Analysis

In this project, stock market data is analyzed with network and graph theory. The goal of this part is to study correlation structures among fluctuation patterns of stock prices using
tools from graph theory. The intuition is that investors will have similar strategies of investment for stocks that are effected by the same economic factors. For example, the stocks belonging the transportation sector may have different absolute prices, but if for example fuel prices change or are expected to change significantly in the near future,
then one would expect the investors to buy or sell all stocks similarly and maximize their returns. 

Towards that goal, different graphs are constructed based on similarities among the time series of returns on different stocks at different time scales (day vs a week) and properties of such graphs are identified. The data is obtained from Yahoo Finance website for 3 years. 

The data has a number of csv tables, each containing several fields: Date, Open, High, Low, Close, Volume, and Adj Close price. 
The files are named according to Ticker Symbol of each stock and the market sector for each company is in Name_sector.csv.