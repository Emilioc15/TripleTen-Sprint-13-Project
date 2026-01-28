# TripleTen-Sprint-13-Project
🚖 Time Series: Taxi Demand Prediction — Sweet Lift
📝 Project Overview

This project focuses on predicting hourly taxi orders for Sweet Lift, a taxi company serving airports. Using historical order data, the goal is to forecast demand for the next hour, helping the company attract drivers during peak periods and improve service availability.

The project emphasizes accurate predictions, proper time series modeling, and actionable insights, with the target metric being RMSE ≤ 48 on the test set.

📊 Dataset Description

The dataset contains historical taxi order records at airports:

Timestamp of each order

Number of orders per time unit

Data is resampled to hourly intervals to create a consistent time series for modeling.

🎯 Objectives

Load and preprocess the data, resampling it by hour

Explore and analyze patterns in taxi demand

Train multiple predictive models with different hyperparameters

Evaluate models using a 10% test sample

Ensure RMSE ≤ 48 for actionable forecasting

Provide recommendations for peak-hour driver allocation

🔍 Key Tasks Performed
🧹 Data Preparation

Loaded and inspected the dataset

Resampled the data by hourly intervals

Checked for missing timestamps or anomalies

📈 Exploratory Analysis

Identified hourly, daily, and weekly patterns in taxi orders

Visualized demand trends and seasonal fluctuations

🔧 Model Development

Trained multiple time series models (e.g., ARIMA, SARIMA, Gradient Boosting, or others)

Tuned hyperparameters for best performance

Split the dataset into training and a 10% test set

📊 Model Evaluation

Evaluated predictions using RMSE

Compared model performance to select the most accurate and reliable approach

Ensured RMSE met the target threshold (≤48)

🛠️ Tools & Technologies

Python

Pandas & NumPy for data manipulation

Scikit-learn for model evaluation

Statsmodels for ARIMA/SARIMA modeling

Matplotlib & Seaborn for visualization

Jupyter Notebook

📈 Final Deliverables

Cleaned and resampled hourly dataset

Trained time series models with hyperparameter tuning

RMSE evaluation and comparison for all models

Visualizations showing demand patterns and forecasts

Recommendations for peak-hour driver management

✅ Success Criteria

A successful project demonstrates:

Proper handling of time series data and resampling

Accurate prediction of taxi demand (RMSE ≤ 48)

Comparison of multiple models and hyperparameter tuning

Clear analysis and actionable insights

Well-documented, reproducible workflow

📌 Conclusion

This project illustrates the application of time series forecasting in a real-world business scenario. By predicting hourly taxi demand, Sweet Lift can optimize driver allocation, enhance service reliability, and improve operational efficiency at airports.
