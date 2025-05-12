# Pidilite Stock Analysis and Forecasting
This repository contains the project files for the Pidilite Stock Analysis and Forecasting project, which focuses on analyzing and forecasting the closing stock prices of Pidilite Industries using time series analysis techniques. The analysis leverages ARIMA and Holt-Winters models to predict future stock price movements and assess model performance.

## Project Overview
Pidilite Industries, a leading player in the Indian adhesives and sealants market, has exhibited strong growth over the past decade. This project seeks to analyze and predict the closing stock prices of Pidilite, aiding investors and financial strategists in making data-driven investment decisions.

## Key Objectives:
Analyze historical stock price data of Pidilite Industries.

Identify trends, seasonality, and residuals through seasonal decomposition.

Apply ARIMA and Holt-Winters models to forecast future stock prices.

Compare model performance based on RMSE, MAE, and MAPE metrics.

## Dataset
The dataset comprises daily closing stock prices of Pidilite Industries from 2016 to early 2024.

Key Data Attributes:

Date: Trading date of the stock.

Close: Closing stock price of Pidilite Industries.

## Methodology
### Exploratory Data Analysis (EDA):

Visualized the time series to detect trends, seasonality, and volatility.

Analyzed the effect of significant economic events (e.g., COVID-19) on stock price behavior.

### Data Transformation:

Applied log transformation to stabilize variance and linearize exponential growth.

Differencing was employed to achieve stationarity.

### Model Selection:

ARIMA model configurations were selected based on AIC values.

Holt-Winters model was implemented for trend analysis and double exponential smoothing.

Diagnostic Checks and Evaluation:

Conducted residual analysis using Q-Q plots and residual plots.

Evaluated models using RMSE, MAE, and MAPE to assess predictive accuracy.

## Results & Findings
### Seasonal Decomposition Analysis:

Strong upward trend observed over the 8-year period.

Annual seasonality evident, suggesting periodic fluctuations in stock prices.

### Model Performance:

ARIMA (1,1,0): Achieved an RMSE of 28.66 and a MAPE of 1.16%.

Holt-Winters: Demonstrated slightly better performance with an RMSE of 25.87 and a MAPE of 1.12%.

### Forecasting Analysis:

Both models projected continued growth in Pidilite's stock price.

The 95% confidence interval widened over time, indicating increasing uncertainty in long-term predictions.


## Technologies Used
Python

NumPy, Pandas

Matplotlib, Seaborn

Statsmodels

Jupyter Notebook
