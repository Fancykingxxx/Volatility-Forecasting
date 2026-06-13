# Volatility Forecasting During the 2008 Financial Crisis

## Overview

This project investigates the behaviour of financial markets during the 2008 Global Financial Crisis using classical time-series modelling techniques.

The objective is to analyse the volatility dynamics of the S&P 500 Index and evaluate whether ARIMA-GARCH models can capture extreme market fluctuations during periods of financial stress.

The project was originally developed as part of my quantitative finance and time-series analysis training during my Mathematics degree at the University of Manchester.

## Methods

The project combines:

* ARIMA models for modelling the conditional mean process
* GARCH models for modelling time-varying volatility
* Akaike Information Criterion (AIC) for model selection
* Value at Risk (VaR)
* Expected Shortfall (ES)

The analysis focuses on the period surrounding the 2008 Financial Crisis, one of the most volatile periods in modern financial history.

## Dataset

* S&P 500 Index
* Daily closing prices
* August 2008 – November 2008

Key Questions

1. Can ARIMA models capture short-term market dynamics during a crisis?
2. Can GARCH models successfully model volatility clustering?
3. How accurately can risk measures such as VaR and Expected Shortfall describe downside risk during market stress?

Technologies

* R
* forecast
* rugarch
* PerformanceAnalytics
* TSstudio

## Learning Outcomes

This project demonstrates:

* Time-series modelling
* Financial risk analysis
* Statistical model selection
* Volatility forecasting
* Quantitative research workflows

## Author

Fengxi Jin

PhD Neuroscience (University of Manchester)

MMath Mathematics (University of Manchester)
