# Risk Analysis

## Introduction

In this project, we will conduct risk analysis on four of the tech giants, Apple, Google, Amazon and Microsoft. 

We will web-scrape the past 5 years of data from Yahoo finance, visualize the trend, look at the correlations among each other and calculate Value at Risk(VaR) through bootstrap method and Monte Carlo simulation with Geometric Brownian Motion(GBM).

## Methods

1. Web-scrape the past 5 years of data from Yahoo finance.
2. Visualize the trend of each stock prices by using moving average approach with different window sizes
3. Obtain the expected return (mean) and risk (standard deviation).
4. Utilize Bootstrp method and Monte Carlo simulation to obtain the probability distribution of the final price (detailed procedures are in the notebook.)
5. Calculate the VaR (Value at Risk) based on the distribution.

## Consideration of possible improvement

The correlation plots display that the four companies's stock prices are highly correlated, supported by the fact that the NASDAQ companies have grown at a very fast pace in recent years. 

One company's downside effect can impact other three companies' risk exposure, so we can re-calculate VaR including this factor, possibly increasing the VaR (high loss severity).
