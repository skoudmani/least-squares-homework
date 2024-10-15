# Homework Repository

This repository contains two Jupyter notebooks related to least squares fitting. The tasks focus on extrapolating trends from real-world datasets.

## Homework Overview

### 1. NVIDIA Stock Price Analysis
In this assignment, you will work through a Jupyter notebook to analyse NVIDIA stock price data and determine the line of best fit. You will then use this best-fit line to predict the value of NVIDIA's stock on 1st January 2025. 

Key tasks:
- Determine the line of best fit to the stock price data.
- Predict the stock price for 1st January 2025 based on the identified trend.
- Reflect on the accuracy of extrapolating from past data:
  - Why might the trend not continue?
  - What are the caveats to using a line of best fit for future predictions?

You can launch the notebook on Binder to easily run the analysis in an interactive environment.

### 2. Taylor Swift Ticket Sales Analysis
This second task involves analysing a dataset on Taylor Swift’s ticket sales over several of her tours. With only six data points, you are tasked with determining the line of best fit using either manual calculations or by modifying a provided Jupyter notebook.

Key tasks:
- Calculate the best-fit line coefficients (`m` and `c`) either manually (using formulae from the lecture) or by modifying the skeleton Jupyter notebook.
- Plot the data points and the best-fit line.
- Comment on any outliers or anomalies in the data and how they affect the best-fit line.

## Instructions for Use

1. **NVIDIA Stock Price Analysis**: Open the notebook `nvidia_stock_analysis.ipynb` in Binder to run the analysis. The notebook will guide you through the steps needed to calculate the line of best fit and make a stock price prediction.
2. **Taylor Swift Ticket Sales Analysis**: Use the `taylor_swift_sales_analysis.ipynb` notebook (or calculate manually) to find the best-fit line for the ticket sales data. You can modify the provided notebook to perform the analysis or calculate by hand and plot the results in the notebook.

## Requirements
- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**: Ensure you have the following Python libraries installed:
  - `numpy`
  - `matplotlib`
  - `pandas`

If you're working locally, you can install these by running:
```bash
pip install numpy matplotlib pandas

## Acknowledgments
- The NVIDIA stock data was downloaded from [MarketWatch](https://www.marketwatch.com/).
- The Taylor Swift ticket sales data was accessed from [Wikipedia](https://en.wikipedia.org/wiki/List_of_Taylor_Swift_live_performances).
