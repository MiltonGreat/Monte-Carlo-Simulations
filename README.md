# Portfolio Optimization Using Monte Carlo Simulation & Modern Portfolio Theory

![screenshot-localhost_8888-2025 04 05-13_56_16](https://github.com/user-attachments/assets/9198223c-2b71-4290-bb51-ba58af4836cc)

### Project Overview

This project applies Modern Portfolio Theory (MPT) and Monte Carlo Simulations to historical stock price data in order to:

- Estimate expected portfolio returns
- Quantify risk profiles (volatility)
- Identify optimal portfolios along the efficient frontier

Using a large number of simulated portfolio allocations, we calculate key financial metrics such as returns, volatility, and Sharpe ratio, and visualize the trade-offs between risk and return.

### Dataset

The dataset contains historical stock price data for a group of selected assets. This data is used to compute:

- Daily and annualized returns
- Covariance and correlation matrices
- Inputs for portfolio performance simulation

#### Key Features

- Monte Carlo Simulations (25,000+ simulations) for diverse portfolio allocations
- Visualization of the Efficient Frontier
- Maximum Sharpe Ratio Portfolio
- Minimum Volatility Portfolio

### Summary statistics

- Expected return
- Risk (standard deviation)
- Sharpe Ratio

### Methodology

1. Load and Clean Data
- Read in stock prices and calculate daily log returns.

2. Generate Simulated Portfolios
- Randomly allocate weights across assets for thousands of simulations.

3. Calculate Metrics for Each Simulation
For each allocation, compute:
- Expected annual return
- Volatility
- Sharpe Ratio

Identify Optimal Portfolios
- Maximum Sharpe Ratio (risk-adjusted return)
- Minimum Volatility (most stable)

Visualize Efficient Frontier
- Plot all portfolios, color-coded by Sharpe ratio.

### Interpretation

- Monte Carlo simulations help understand risk-return trade-offs.
- Optimal portfolios help maximize return for a given level of risk.
- The efficient frontier serves as a decision-making guide for investors.

### Source

[Stock Portfolio Optimization Dataset for Efficient from Kaggle](https://www.kaggle.com/datasets/chibss/stock-dataset-for-portfolio-optimization)


    
