🚖 Rapido Ride Data Analysis

This project focuses on analyzing Rapido ride data to uncover key insights related to ride demand, revenue patterns, service usage, and cancellation behavior. 
The analysis helps understand customer trends and operational efficiency.

🛠️ Tools & Technologies

Python (Pandas, NumPy)
Matplotlib
Jupyter Notebook

📂 Dataset Description

The dataset includes the following features:

services – Type of ride (Economy, Premium, etc.)
date – Ride date
time – Ride duration (converted to timedelta)
ride_status – Completed / Cancelled
source – Pickup location
destination – Drop location
distance – Distance of ride (km)
ride_charge, misc_charge, total_fare – Fare details
payment_method – Payment type

🔍 Data Cleaning & Preprocessing

Handled missing values using median/mode strategies
Converted time column into proper timedelta format
Created new features:
time_minutes (duration in minutes)
hour (for time-based analysis)
route (source → destination)
Removed duplicates and corrected data types

📊 Exploratory Data Analysis (EDA)

Key Analysis Performed:
Average ride distance and duration
Service-wise revenue analysis
Ride status distribution (Completed vs Cancelled)
Peak demand time analysis
Most frequent routes
Cancellation rate by service and location

📈 Key Insights

📌 Majority of rides are successfully completed, indicating reliable service
📌 Economy service generates the highest revenue and usage
📌 Peak ride demand occurs during evening hours (commute time)
📌 Certain pickup locations have higher cancellation rates
📌 Most rides are short-distance urban trips

📊 Visualizations

Bar charts for service revenue and ride counts
Pie chart for ride status distribution
Line chart for demand trends by time
Histogram for ride duration
Scatter plot for distance vs fare

📁 Project Files

rapido_analysis.ipynb → Full EDA in Jupyter Notebook
cleaned_data.csv → Processed dataset

🎯 Project Outcome

This project demonstrates practical data analysis skills including:

Data cleaning and transformation
Exploratory data analysis
Data visualization
Business insight generation

🚀 Future Improvements

Build predictive model for ride demand
Analyze customer segmentation
Optimize pricing strategy using data

👤 Author

Nikita Apurva
