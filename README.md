# GFC-systemic-risk-analysis 
# Global Financial Crisis — Systemic Risk Analysis
An empirical analysis of market and systemic risk during the 2008 Global Financial Crisis, examining the equity performance of JPMorgan Chase and Citigroup relative to the S&P 500 across the 2005–2010 period.
# Project Overview
This project was completed as part of the Financial Risk Management module of the MSc in Finance programme at Dublin City University (DCU).
The analysis combines academic literature on systemic risk with quantitative modelling of real market data, exploring how the GFC manifested in observable equity and volatility outcomes.
# What's Inside
GFC1 risk analysis.ipynb (Main Python notebook) — full analysis and visualisations
S_P_500.xlsx - S&P 500 daily price data
JP_Morgan_Final.xlsx - JPMorgan Chase daily price data
Citi_Group_Inc_Final.xlsx - Citigroup daily price data
CBOEVIXCLS.xlsx - CBOE VIX Index data
TEDRATE.xlsx - TED Spread data (liquidity risk indicator)
# Analysis Includes
Descriptive statistics and log return calculation
Correlation analysis and heatmap across banking stocks and VIX
Time-series visualisation of daily returns, VIX, and TED Spread
Value at Risk (VaR) at 95% confidence level
Expected Shortfall (ES) — tail risk beyond VaR
GARCH modelling for time-varying volatility
# Tools & Libraries
Python · pandas · NumPy · matplotlib · seaborn · arch (GARCH)
# Key Finding
Citigroup's Expected Shortfall was approximately 14x that of the S&P 500 at the height of the crisis — a quantitative illustration of how concentrated banking sector exposure amplified systemic risk.

MSc Finance | DCU | Financial Risk Management Module
