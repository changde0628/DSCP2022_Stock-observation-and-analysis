# DSCP Final Project - Stock observation and analysis

**Author : cdp(41075901H)**

## Introduction

Hello everyone, my name is Peng Chang De.
Because I usually invest in stocks, sometimes I use technical indicators (TIs) as the basis for buying and selling, such as 5MA, 10MA, KD and RSI, but some apps provided by stock underwriters do not provide such charts. Through the final project I want to visualize stock information.
I will implement:

- Draw a candlestick chart through the Open, High, Low, Close of the stock price
- 5MA, 10MA, 20MA
- KD, RSI
- Use Prophetm to predict stock prices

## How to use

- Execute .ipynb according to the steps
- Enter the Taiwan stock code you want to query
  (Example: If you want to inquire the information of Yuanta/P-shares Taiwan Top 50 ETF, you must enter **0050**)
- Enter the time you want to start and end
  (Example: **2022-10-1** ~ **2022-12-1** )
- Enjoy!

Note: Please **make sure your input is valid**, otherwise you will be asked to re-enter the value until you figure it out.

## Implementation details

- Use the ta-lib module to easily calculate various TIs.
- Use the twstock module to get the current Taiwan stock information. (grab the .csv file from yahoo)
- Use the pandas module to process data.
- Visualize data using matplotlib modules.
- mplfinance is a module for graphing financial data, you can imagine it as matplotlib that focuses on processing financial data.
- Use the prophet model, developed by facebook company, to carry out simple stock forecasting, which can be used to forecast the expected range of statistical changes in the reference stock.

## Demo

![](https://github.com/changde0628/DSCP_FinalProject_2022_Stock-observation-and-analysis/blob/main/Demo1.png)

![](https://github.com/changde0628/DSCP_FinalProject_2022_Stock-observation-and-analysis/blob/main/Demo2.png)
