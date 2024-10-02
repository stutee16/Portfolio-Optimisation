# Portfolio Optimization 

## Overview

This project focuses on optimizing a stock portfolio using historical price data from several prominent companies, including Apple, Amazon, Google, Goldman Sachs, JP Morgan, Meta, Microsoft, and Walmart. The goal is to maximize expected returns while minimizing risk, utilizing various financial metrics such as daily returns, volatility, covariance, and correlation.

## Key Features

- **Data Acquisition**: Utilizes CSV files containing historical stock price data for multiple companies, loaded into a Spark environment for efficient processing.
  
- **Data Processing**: 
  - Computes daily returns for each stock.
  - Calculates volatility (standard deviation of returns) and expected returns (mean of returns) for each stock.
  
- **Statistical Analysis**:
  - Calculates the covariance matrix to assess the relationship between the stocks.
  - Computes the correlation matrix to understand how stocks move together, aiding in diversification.

- **Portfolio Construction**: 
  - Uses optimization techniques to construct an efficient portfolio that balances expected returns against risk.
  - Implements the Efficient Frontier to visualize the trade-off between risk and return.

- **Visualization**: 
  - Generates visual representations of the Efficient Frontier to facilitate portfolio performance analysis.

## Technologies Used

- **Apache Spark**: For handling large datasets and performing distributed data processing.
- **SQL**: To perform data manipulation and calculations within the Spark environment.
- **Matplotlib**: For visualizing results and creating plots of the Efficient Frontier.

## Getting Started

### Prerequisites

- Apache Spark installed (or access to Databricks).
- Python environment with necessary libraries (e.g., Matplotlib).
- Access to historical stock price data in CSV format.

