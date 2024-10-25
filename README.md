# 📊 Product Sales Forecasting

This project explores sales forecasting using various time series and regression models, including Seasonal Naïve, Holt-Winters, ARIMA, SARIMA, and Linear Regression. By applying and comparing multiple forecasting techniques, the project aims to identify the best model for predicting future sales.

## 🎯 Project Objective

The goal of this project is to forecast sales of products in the dataset by applying quantitative forecasting methods, including both time series and causal models. The steps involved include:

1. **Time Series Analysis**: Understand data patterns, trends, and seasonality.
2. **Model Testing**: Train multiple forecasting models on the training dataset.
3. **Model Selection**: Evaluate model performance and select the most accurate model for predictions on the test data.

## 🚀 Models Used

The forecasting models implemented in this project are:

1. **Seasonal Naïve Model**: Assumes seasonal patterns will repeat exactly in the future.
2. **Holt-Winters Model (Triple Exponential Smoothing)**: Captures level, trend, and seasonality in time series data.
3. **ARIMA Model**: AutoRegressive Integrated Moving Average, suited for univariate time series data.
4. **Seasonal ARIMA (SARIMA)**: Extends ARIMA by considering seasonality.
5. **Linear Regression Model**: A causal model that fits a linear trend line to the data, which may be effective when seasonal patterns are linear.

## 📊 Project Workflow

1. **Data Preparation**: Load and preprocess data, managing missing values and any anomalies.
2. **Exploratory Data Analysis**: Analyze trends, seasonality, and stationarity of the sales data.
3. **Model Training and Evaluation**: Train each model on the train set, evaluate performance using metrics like MAPE, RMSE, etc.
4. **Model Selection**: Select the best-performing model based on test data predictions.

## 🏆 Conclusion

After experimenting with different forecasting models, the **Linear Regression Model** outperformed other time-series models for this dataset. The data displayed strong seasonality and a linear trend, which aligned well with the assumptions of regression models. The project's results suggest that the Linear Regression model is suitable for forecasting future sales, given that patterns in historical data are likely to continue.

---

## 🛠️ Getting Started

### Prerequisites

- **Python 3.7+**
- Required Libraries:
  ```bash
  pip install numpy pandas matplotlib statsmodels sklearn
  ```

### Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Product_Sales_Forecasting.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Product_Sales_Forecasting
   ```

3. **Run the Jupyter Notebook**:
   Open `sales_forecasting_notebook.ipynb` in Jupyter Notebook to see the step-by-step implementation and results.

## 📂 Project Structure

- **`sales_forecasting_notebook.ipynb`**: Jupyter Notebook containing the complete project code, analysis, and results.
- **`data/`**: Directory containing the dataset used for forecasting.
- **`README.md`**: Project overview and instructions.

## 📈 Results Summary

- **Evaluation Metrics**: The models were evaluated using common forecasting metrics, with Linear Regression yielding the most favorable results.
- **Future Work**: Future improvements could include testing additional models or incorporating exogenous variables that could impact sales.



