# Time_Series_Forecasting

## Tools Used - Python, ARIMA , Statsmodels

### Table of Contents 
1. Project Objective
2. Dataset Description
3. Project Workflow
4. Predictions

### Project Objective

To build a forecasting model utilizing Time series analysis on the Air passenger dataset, integrating ARIMA method.

Steps involved in building the model -
1. Data Cleaning and Analysis
2. Check Stationary
3. Smoothing
4. Exploratory Data Analysis
5. Holt Winter Model
6. Building Accurate ARIMA model
7. Precitions

### Dataset Description

The dataset contains Month and Passengers 

Data columns (total 2 columns):
 #   Column      Non-Null Count  Dtype 
---  ------      --------------  ----- 
 0   Month       144 non-null    object
 1   Passengers  144 non-null    int64 
dtypes: int64(1), object(1)
memory usage: 2.4+ KB

##### df.describe()
        Passengers
count	144.000000
mean	280.298611
std	    119.966317
min	    104.000000
25%	    180.000000
50%	    265.500000
75%	    360.500000
max	    622.000000

### Project Workflow

