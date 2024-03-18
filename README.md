# Project-1: Time Series Sales Forecasting

This project is my personal attempt to explore time series machine learning (ML) modeling to forecast sales. The dataset used is sourced from a Kaggle competition, which can be found [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting).

## Dataset Overview

The analysis focuses exclusively on the `train.csv` file, specifically data from `store_nbr` 5. This subset contains approximately 55,000 data points across 33 categories in the 'family' column. For this project, I will only use data from the AUTOMOTIVE category, which totals 1,684 data points.

## Modeling Approaches

I employed four different modeling approaches: three conventional ML models (ARIMA, SARIMA, SARIMAX) and one deep learning-based model (LSTM). For the SARIMAX model, the exogenous data were obtained from `train.csv` (`onpromotion`) and `oil.csv` (`dcoilwtico`).

## Jupyter Notebook and Code

The code in my Jupyter Notebook includes only the models that yielded the best results, with optimal non-seasonal and seasonal parameters. For each model, two versions are provided for execution: one for non-differenced data and another for differenced data.

The Jupyter Notebook is provided within for your viewing pleasure 
