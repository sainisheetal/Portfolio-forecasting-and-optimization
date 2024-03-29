![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)  ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
# Portfolio-forecasting-and-optimization
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
##The Mission:
-------------------------------------------------------------------------------------------------------------------------------------------

The mission of this project is to give a Bank client who is interested in creating a paid-tool for their clients who want to manage their own investment accounts.
To achive this we have to use portfolio optimisation methodologies: Mean-variance Optimisation. 
A user inputs an amount of money they want to invest using a parameter at the top of the dashboard in Tableau, and the Python script calculates the number of shares they should consider buying for each methodology. This is an illustrative example of a portfolio that considers the following crypto  : BitCoin, LiteCoin, Ethereum.
Other 3 stock which are as follows: Microsoft, Amazon and Macdonald.

#This repository contains the following directories:
---------------------------------------------------------------------------------------------------------------------

Tableau Workbook: This directory contains a Tableau file and a PNG image of the dashboard created for this project.
Notebooks This directory contains two Jupyter Notebooks:

Crypto.ipynb: This notebook creates random portfolios and includes code blocks to find the most efficient portfolios. This is for the socks BitCoin, LiteCoin, Ethereum. The Dashboard contains Daily price Trend of BitCoin, LiteCoin, Ethereum. I have used candel sick graph to represent the crypto. It gives more detailed 
              information to the client about the trend, which they have to follow for buying and selling the stock.
              
Portfolio_Optimizer.ipynb: This notebook creates random portfolios and includes code blocks to find the most efficient portfolios. This is for the socks  Microsoft, Amazon and Macdonald. This is for the future research also. However, the analysis of these 3 stocks also there in the file.

data loader.ipynb: This notebook extracts data using yfinance. This is seperated from the other files as maybe required in future to get different data with differnt sites. This notebook also seprated to keep history of the Tickers on which previously worked.

Data: This directory contains the output files generated by the notebooks, as well as CSV versions of the created dataframes.
Financial Research: This file contain all my research i have done on this topic.

Excel EF: This file contain the calculations and analysis i have made on Excel and made EF graph. It also returns, risk, standard deviation, voltality, and EF graph.


##Dashboards:
---------------------------------------------------------------------------------------------------------------------

![Dashboard](https://github.com/sainisheetal/Portfolio-forecasting-and-optimization/blob/main/profile_optimizer/Tableau%20Workbook/Dashboard.png)

This Dashboard represent daily price changes. I have used candelstick graph to represent Open price, Close price, Low price & High price. It's very easy to 
understand for anyone when prices are low and high. Its interactive and client can check data like 1 week, 3 months, 1 year ...so on.
![Dashboard](https://github.com/sainisheetal/Portfolio-forecasting-and-optimization/blob/main/profile_optimizer/Tableau%20Workbook/Dashboard_portfolio%20optimization.png)
This Dashboard represent complete portfolio to analyse the efficiency (return, volatility, sharpe ratio,...)of different portfolios. Its interactive and client can check data like 1 week, 3 months, 1 year ...so on. Just select the year you will get all data related to it and candel stick represent the Open price, Close price, Low price & High price.

Limits of the project
--------------------------------------------------------------------------------------------------------------------------------------------------
Here, Tableau Desktop free version is used which has very limited features. So, using Tableau professional gives more aspects to connect with the
server and also using the Python connections.

Author
--------------------------------------------------------------------------------------------------------------------------------------------------
@Sheetal Saini

