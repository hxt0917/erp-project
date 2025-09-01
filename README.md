# ERP Project - Crude Oil Price Prediction

## Introduction

This project aims to predict future oil prices using various time series forecasting models. The project begins with data preprocessing, followed by exploratory data analysis, and then implements several models, including ARIMA, SVR, SVC, and LSTM (for both regression and classification).


## Dataset

* `DCOILWTICO.csv`: Raw data for WTI crude oil prices.
* `oil_price_cleaned.csv`: Cleaned and preprocessed data used for modelling.

## Methodology

1.  **Data Preprocessing (`data_preprocessing.ipynb`)**
    * Handles missing values and outliers.
    * Converts the date column to `datetime` format.
    * Prepares the data for subsequent analysis and modelling.

2.  **Preliminary Data Analysis (`preliminary_data_analysis.ipynb`)**
    * Conducts an initial exploration of the cleaned data.
    * Analyses the statistical properties of the data to identify trends, non-seasonality, and other patterns.

3.  **Modeling**
    * **ARIMA (`arima.ipynb`)**
        * Implements the Autoregressive Integrated Moving Average (ARIMA) model, a classic time series forecasting method for both Regression and Classification.
    * **SVR (`svr.ipynb`)**
        * Uses Support Vector Regression (SVR) to predict continuous oil prices.
    * **SVC (`svc.ipynb`)**
        * Employs Support Vector Classification (SVC) to predict the direction of price changes (up or down).
    * **LSTM Regression (`lstm_regression.ipynb`)**
        * Implements a Long Short-Term Memory (LSTM) neural network for oil price regression.
    * **LSTM Classification (`lstm_classification.ipynb`)**
        * Uses an LSTM network for binary classification of oil price movements.

## Usage

It is recommended to run the Jupyter Notebook files in the following order:

1.  `data_preprocessing.ipynb`
2.  `preliminary_data_analysis.ipynb`
3.  Any of the modelling notebooks (`arima.ipynb`, `svr.ipynb`, `svc.ipynb`, `lstm_regression.ipynb`, `lstm_classification.ipynb`).

## License

This project is released for academic purposes only. Please refer to the ERP Project for further details.
---
