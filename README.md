# Predictive Inventory Optimization for Seasonal Products in Online Retail

## Abstract
This project aims to optimize inventory management for seasonal products in online retail using various predictive models including ARIMA, SARIMA, XGBoost, and LSTM. The analysis was conducted on the UCI Online Retail Dataset, and key performance metrics such as MAE, RMSE, MASE, and WMAPE were used to evaluate the models.

## Table of Contents
1. [Introduction](#Introduction)
2. [Data Description](#Data-Description)
3. [Models Used](#Models-Used)
4. [Results](#Results)
5. [Installation](#Installation)
5. [Usage](#Usage)
6. [Acknowledgements](#Acknowledgements)
7. [References](#References)

## Introduction
This project investigates predictive inventory optimization for seasonal products in online retail. The primary objective is to develop and compare different forecasting models to improve inventory management.

## Data Description
The analysis uses the UCI Online Retail Dataset, which includes transactions from a UK-based online retailer. Key features include:
- **InvoiceNo**: Invoice number
- **StockCode**: Product code
- **Description**: Product description
- **Quantity**: Quantity of products
- **InvoiceDate**: Date of the invoice
- **Price**: Price per unit
- **CustomerID**: Customer ID
- **Country**: Country of the customer

**Dataset Access:**
The dataset can be accessed from the UCI Machine Learning Repository available on Kaggle using the link: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail).

**Data Preparation:**
Download the dataset, place it in the root directory of the cloned repo, and rename it to `ucs_data.csv` before proceeding with the analysis.

## Models Used
1. **ARIMA**: Autoregressive Integrated Moving Average
2. **SARIMA**: Seasonal ARIMA
3. **XGBoost**: Extreme Gradient Boosting
4. **LSTM**: Long Short-Term Memory networks

## Results
The models were evaluated using the following performance metrics:
- **MAE**: Mean Absolute Error
- **RMSE**: Root Mean Squared Error
- **MASE**: Mean Absolute Scaled Error
- **WMAPE**: Weighted Mean Absolute Percentage Error

## Installation
To set up the environment, follow these steps:

1. **Clone the repository:**

git clone https://github.com/thejamesben/models.git
cd repository

## Usage
### Start Jupyter Notebook:

jupyter notebook

### Run the notebooks in the following order:
- Pre-processing and Feature Engineering Script: `data_preprocessing.ipynb`

- Historical Data Analysis Script: `historical_data_analysis.ipynb`
- Training Models Script:
`arima_model.ipynb`, 
`sarima_model.ipynb`, 
`xgboost_model.ipynb`, 
`lstm_model.ipynb`
- Findings Script: `findings.ipynb`
- Statistical Analysis Script: `statistical_analysis.ipynb`

## Acknowledgements
I would like to thank my supervisor, Prof. Olumide Babatope Longe, for his guidance and support throughout this project.


## References
- Chen, D., et al. (2012). Online Retail II dataset. UCI Machine Learning Repository. Retrieved from [https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data)
