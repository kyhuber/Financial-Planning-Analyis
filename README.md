# Financial Planning Tool

This app creates a Financial Planning Tool for emergencies and retirement, which can be used by members at a credit union.

First, the tool collects real-time price data via API for two cryptocurrency assets, BTC and ETH. The tool then accesses the Alpaca API to get historical price data for two tickers, AGG (bonds) and SPY (stocks). The Financial Planning Tool analyzes the portfolio composition and calculates its total value before comparing it to emergency fund needs based on the member's monthly income. If the total portfolio value exceeds the emergency fund needs, the tool congratulates the member.

Second, the Financial Planning Tool forecasts retirement portfolio performance for two hypothetical investment strategies. Using historical price data, the tool runs 10- and 30-year Monte Carlo simulations with two different portfolio allocations across AGG and SPY. To support the analysis, data is visualized in line plots and histograms. Finally, the tool recommends which of the investment strategies is more appropriate for the member.

The Financial Planning Tool creates value for the credit union member by determining whether their portfolio has enough money for emergencies. The member can check this tool and see real-time data for making investment decisions. The tool also helps members understand how changes in their retirement investment strategy may affect their ability to retire. The Financial Planning Tool makes it easy for members to simulate different portfolio allocations over multiple time horizons.

---

## Technologies

The Financial Planning Tool is written in Python 3.10.1 using Jupyter Lab. It is compatible with Mac and PC OS.
The tool uses the Pandas libraries to collect, prepare, and analyze the data.
The MCForecastTools library provides the Monte Carlo Simulations.
Data visualization plots are rendered using Matplotlib.

This app references cryptocurrency price data via the Free Crypto API.
Market data for AGG and SPY are collected via API using the Alpaca SDK.

---

## Installation Guide

This app can be run in Gitbash or Terminal. The app and supporting files are located in the below Github repository:
https://github.com/kyhuber/Financial-Planning-Tool

---

## Usage

To use the Financial Planning Tool, the user must have a key for the Alpaca SDK. The app will then automatically do the analysis and plot the data.

---

## Contributors

The Financial Planning Tool was written by Kyle Huber in February 2022.

---

# Financial Planning Tool
