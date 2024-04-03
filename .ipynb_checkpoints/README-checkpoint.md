# Time Series Analysis and Forecasting Project

This project focuses on conducting time series analysis and forecasting for sales data of furniture and office supplies using Python. The analysis involves data preprocessing, time series decomposition, model fitting, and forecasting. Various techniques and models are employed to understand the underlying patterns in the data and make future predictions.

## Acknowledgement

This project draws inspiration from the insightful article [An End-to-End Project on Time Series Analysis and Forecasting with Python](https://towardsdatascience.com/an-end-to-end-project-on-time-series-analysis-and-forecasting-with-python-4835e6bf050b). I build upon the methodology presented in the article by incorporating enhancements such as train-test-split during model fitting and testing. These enhancements aim to improve the evaluation of the time series model on unseen data while maintaining temporal order, thereby enhancing the reliability and robustness of the analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- statsmodels
- itertools
- Prophet

## Getting Started

To begin with, ensure you have all the necessary dependencies installed. You can install them using pip:

```bash
pip install pandas numpy matplotlib statsmodels pystan fbprophet
```

## Data

The dataset used in this project contains sales data for furniture and office supplies. The data is loaded from an Excel file (`superstore.xls`) and preprocessed to aggregate sales by date.

## Analysis Steps

### 1. Data Preprocessing

- Filter data for specific categories (Furniture and Office Supplies)
- Aggregate sales by date
- Resample data to monthly frequency

### 2. Train-Test Split

- Split data into training and testing sets based on a specified end date for the training data (2016-12-31)

### 3. Time Series Decomposition

- Decompose time series data into components: level, trend, seasonality, and noise
- Visualize the components using plots

### 4. Time Series Forecasting with SARIMA

- Fit SARIMA models to the data using grid search to find optimal parameters
- Evaluate model performance using Mean Squared Error and Root Mean Squared Error
- Produce forecasts and visualize predictions

### 5. Furniture vs. Office Supplies Comparison

- Compare sales of furniture and office supplies over the same time period
- Analyze sales trends and patterns for both categories

### 6. Time Series Modeling with Prophet

- Utilize the Prophet library for time series modeling and forecasting
- Fit Prophet models to furniture and office supplies sales data
- Generate forecasts and visualize trends and patterns

## Conclusion

This project provides a comprehensive analysis of sales data for furniture and office supplies, including preprocessing, modeling, and forecasting. By leveraging various techniques and models, valuable insights are gained into sales trends, seasonality, and future predictions. Further exploration could involve advanced forecasting techniques and incorporating external data sources for more accurate predictions.