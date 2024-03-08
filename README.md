# Alcohol_Sales_Forecasting

# Alcohol Sales Forecasting with SARIMAX Model

This project focuses on forecasting alcohol sales using the SARIMAX (Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors) model. The dataset used spans from January 1992 to January 2019, containing 234 records. The goal is to predict alcohol sales for the next 12 months, from February 2019 to January 2020.

## Dataset

The dataset used for this project is the alcohol sales dataset, which contains 234 records spanning from January 1992 to January 2019, with two columns: date and alcohol sales.

## Requirements
Python 3.x
Jupyter Notebook
pandas
numpy
statsmodels
matplotlib
seaborn
pmdarima


## Approach
1.Data Cleaning/Preprocessing: The dataset is loaded and preprocessed to ensure compatibility with SARIMAX modeling requirements. 
This includes handling missing values, converting date column to datetime format, and ensuring stationarity if needed.

2.Model Building: SARIMAX model is built using the statsmodels library. Appropriate parameters are selected through analysis and tunning.

3.Forecasting: Finally, the model is used to forecast alcohol sales for the next 12 months (February 2019 to January 2020)


## Files Included

1. Alcohol_Sales_Forecasting.ipynb:  Jupyter Notebook containing the SARIMAX model implementation..

2. alcohol_sales_dataset.csv: CSV file containing the alcohol sales dataset used for analysis.
   

## Usage
- Clone the repository.

- Install the required dependencies mentioned in the requirements.

- Open the Jupyter Notebook Alcohol_Sales_Forecasting.ipynb.

- Follow the instructions provided in the notebook to run the code cells and generate forecasts.

## Conclusion
The SARIMAX model provides a forecast for alcohol sales for the next 12 months, which can be used for planning and decision-making purposes.
