# Retail-Analysis-with-Walmart-Data
This project focuses on analyzing Walmart’s weekly sales data across 45 stores in the United States, identifying sales trends, holiday impacts, and predicting future sales using statistical models.

📁 Dataset Overview

Sales history from 2010-02-05 to 2012-11-01 with the following features:

Store Number

Date (Weekly)

Weekly Sales

Holiday Flag

Temperature

Fuel Price

CPI (Consumer Price Index)

Unemployment Rate

Holiday events considered: Super Bowl, Labour Day, Thanksgiving, Christmas.

🔍 Key Analysis Tasks

✔ Store with maximum total sales
✔ Store with highest sales deviation
✔ Quarterly growth analysis (Q3 2012)
✔ Impact of holidays vs non-holiday average sales
✔ Monthly & Semester sales insights

🤖 Predictive Modeling

Forecasting for Store 1 using:

Linear Regression

Feature engineering on date (converted to numeric day index)

Evaluation of CPI, Unemployment, Fuel Price impact

📌 Model with best accuracy is selected and reported.

🛠 Tech Stack
Tool	Purpose
Python	Data Processing & Analysis
Pandas, NumPy	Data Manipulation
Matplotlib, Seaborn	Visualization
Scikit-learn	Regression Modeling
📈 Outcomes

Identified key seasonal and holiday-driven trends

Insights to support better demand forecasting

Reduced chances of stock-out situations through prediction
