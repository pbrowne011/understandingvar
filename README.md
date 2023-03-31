# Understanding Value at Risk (VaR)

## Overview
Value at Risk (VaR) is a measure utilized to determine the downside risk of an investment or portfolio. This repository contains a Jupyter Notebook showcasing calculations for each method highlighted in the presentation. The notebook offers an in-depth analysis of VaR calculation methods and their corresponding risks.

## Methods of Calculating VaR
The notebook demonstrates the following methods for calculating VaR:

### Historical Method
The historical method calculates a nonparametric VaR based on the previous returns of the security or portfolio. This method assumes that past performance is a good indicator of the near-future.

### Variance-Covariance Method
Also referred to as the parametric method, the variance-covariance method uses historical price movements of a security or portfolio and probability theory to calculate the maximum loss. It assumes that returns are normally distributed and similar to past returns. A variance-covariance matrix is employed to determine volatility.

### Monte Carlo Method
The Monte Carlo method simulates downside risk by utilizing historical data. This method assumes some continuity of historical returns and can be adjusted to reflect a non-normal distribution if desired.

## Criticisms of VaR
There are various criticisms of VaR, including:

* Its inability to estimate the risk of black swan events
* Ignoring the tails of risk distribution
* Providing a false sense of security
* Underestimating risk in worst-case scenarios
* Relying on simplistic assumptions

... and many others.

The repository includes a Jupyter Notebook containing Python code for setting up the data and utilizing each of the three VaR calculation methods.