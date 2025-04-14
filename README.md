# 📊 Store Sales Time Series Forecasting

A comprehensive project focused on predicting daily sales for a retail store using time series forecasting and machine learning techniques. Built on the Kaggle "Store Sales - Time Series Forecasting" competition dataset.

## 📌 Project Overview

The goal of this project is to forecast sales for multiple stores based on historical data and various external factors. This involves:
- Extensive feature engineering
- Time-based exploratory data analysis
- Building and evaluating models for accurate forecasting

## 🧰 Tech Stack

- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- LightGBM  

## 📂 Workflow

### 1. **Data Understanding & Cleaning**
- Loaded datasets: `sales`, `stores`, `oil`, and `holidays`
- Merged all relevant datasets
- Handled missing values and inconsistent formats

### 2. **Exploratory Data Analysis**
- Analyzed sales trends across stores and dates
- Examined seasonality, holidays, and oil price influence
- Plotted rolling averages and trend decomposition

### 3. **Feature Engineering**
- Created time-based features: day, week, month, year, day-of-week
- Lag features, rolling windows, and promotional flags
- Extracted information from holiday types and oil prices

### 4. **Modeling**
- Used LightGBM and XGBoost for regression modeling
- Split data into training and validation based on dates
- Evaluated using RMSLE (Root Mean Squared Log Error)

### 5. **Results**
- Achieved competitive RMSLE score
- Visualized predictions vs. actual sales

## 📸 Visualizations

| Sales Trend | Feature Correlation |
|-------------|---------------------|
| ![Sales Trend](path/to/your/sales_trend.png) | ![Correlation Heatmap](path/to/your/heatmap.png) |

> *(Update image paths after uploading images to your GitHub repo.)*

## 📈 Key Insights

- Significant seasonality and weekly patterns in store sales
- Holidays and promotions have strong impact on forecasting
- Oil prices, while less direct, influence trends over time

## 🚀 Future Improvements

- Implement advanced time series models: Prophet, ARIMA, or LSTM
- Include external macroeconomic indicators
- Explore hierarchical forecasting for store-level granularity

## 📁 Dataset

- Available on Kaggle: [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

## 💡 Key Learnings

- Learned how to structure a full pipeline for time series regression
- Enhanced skills in feature engineering and data visualization
- Gained experience tuning tree-based ensemble models for forecasting

---

## 📬 Contact

Feel free to connect or collaborate:

- GitHub: [github.com/your-username](https://github.com/your-username)
- LinkedIn: [linkedin.com/in/your-link](https://linkedin.com/in/your-link)

---

⭐ *If you like this project, consider giving it a star!*
