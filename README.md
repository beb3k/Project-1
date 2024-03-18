# Project-1: Time Series Sales Forecasting

This project is my personal attempt to explore time series machine learning (ML) modeling to forecast sales. The dataset used is sourced from a Kaggle competition, which can be found [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting).

## Dataset Overview

The analysis focuses exclusively on the `train.csv` file, specifically data from `store_nbr` 5. This subset contains approximately 55,000 data points across 33 categories in the 'family' column. For this project, I will only use data from the AUTOMOTIVE category, which totals 1,684 data points. The dataset with the relevant columns are compiled in `store5.csv` that I uploaded here as well

## Modeling Approaches

I employed four different modeling approaches: three conventional ML models (ARIMA, SARIMA, SARIMAX) and one deep learning-based model (LSTM). For the SARIMAX model, the exogenous data were obtained from `train.csv` (`onpromotion`) and `oil.csv` (`dcoilwtico`).

## Jupyter Notebook and Code

The code in my Jupyter Notebook includes only the models that yielded the best results, with optimal non-seasonal and seasonal parameters. For each model, two versions are provided for execution: one for non-differenced data and another for differenced data.

The Jupyter Notebook is provided within for your viewing pleasure 

## Caveats

As this is my first attempt at machine learning and I'm just getting used to python, also because my domain understanding lies [elsewhere](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1122955/#:~:text=Bioinformatics%20is%20defined%20as%20the,and%20interpretation%20of%20biological%20data.) there are lots of things that had and could go wrong, whether it is the coding, the EDA, the implementation etc. The model results are pretty bad lol, but it is mine, which I'm proud of as a result of maybe 36-ish cumulative hours of coding.

## Acknowledgments
- [Bayuzen Ahmad](https://www.linkedin.com/in/bayuzenahmad/)
- [Dwiweka Naratama](https://www.linkedin.com/in/dwiwekan/)
