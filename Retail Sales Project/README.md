# 🛒 Retail Sales Forecasting Project

This project analyzes and forecasts monthly retail sales using Python. It involves data cleaning, exploratory data analysis (EDA), trend and seasonality detection, and time series forecasting using SARIMA and Auto-ARIMA models.

## 📊 Project Objectives

* Prepare and clean historical sales data for analysis.
* Explore monthly sales trends and seasonal purchasing behavior.
* Build and evaluate time series models to forecast future sales.

## 🛠️ Tools & Libraries Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Statsmodels** for SARIMA modeling
* **pmdarima** for Auto-ARIMA forecasting
* **Jupyter Notebook** for code and visualization

## 🔍 Key Insights

* Monthly sales data revealed seasonal spikes in Q4 (especially around November and December).
* Average monthly sales were highest in early Q1 due to initial demand surges.
* SARIMA models effectively captured seasonality and trend, with forecast accuracy validated using test data.

## 📈 Forecasting Approach

* Converted daily transaction data into monthly totals (`Month-End` frequency).
* Used train-test split: last 3 months of data used for validation.
* Applied Auto-ARIMA and SARIMA models to forecast sales and compared forecasts against actuals.
* Visualized trends, seasonality, and model predictions to interpret business implications.

## 📁 Files

* `Retail Sales Project.ipynb` – Complete Jupyter notebook with analysis and model.
* `README.md` – Project documentation (this file).

## 🚀 How to Run

1. Clone the repo
2. Open the notebook in Jupyter
3. Run all cells to reproduce the analysis

> Requires: Python 3.x, Jupyter, and libraries listed above (install via pip if needed)
