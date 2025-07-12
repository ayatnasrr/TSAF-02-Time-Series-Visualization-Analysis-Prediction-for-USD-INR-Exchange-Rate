# TSAF-02-Time-Series-Visualization-Analysis-Prediction-for-USD-INR-Exchange-Rate


This project focuses on analyzing and forecasting the USD to INR exchange rate using historical data retrieved from Yahoo Finance. It combines time series visualizations and machine learning modeling (Decision Tree Regression) to uncover patterns, correlations, and predictions based on key market indicators.

---

## 📌 Objectives

- Fetch and clean historical exchange rate data (USD/INR).
- Visualize closing prices over time using line plots.
- Analyze correlations between Open, High, Low, and Close values.
- Build a machine learning model to predict the Close rate.
- Provide insights into exchange rate behavior over time.

---

## 📊 Features

- Data pulled directly using `yfinance` API
- Interactive and static visualizations with `matplotlib` & `seaborn`
- Heatmap of feature correlations
- Machine Learning prediction using Decision Tree Regressor
- Clean data export to CSV

---

## 🛠️ Tools & Technologies

- yfinance
- pandas & numpy
- matplotlib & seaborn
- scikit-learn

---

## 📈 Methodology

1. Download USD/INR historical data (2022-07-12 to 2024-12-30)
2. Drop MultiIndex and clean the data
3. Convert date column to datetime format
4. Visualize price trends using time series plots
5. Compute correlation matrix for numeric features
6. Split the data into training and testing sets
7. Train a `DecisionTreeRegressor` using Open, High, and Low as features
8. Predict the Close price and display results

---

## 🧠 Prediction Output

Model: `DecisionTreeRegressor`  
Features used: `Open`, `High`, `Low`  
Target: `Close`  


---

## 📂 File Output

- `USD_INR_Historical.csv`: Cleaned historical exchange rate data
- `Predicted Rate`: Output predictions from the trained model

---

## 📅 Date Range

- **Start Date**: 2022-07-12  
- **End Date**: 2024-12-30
