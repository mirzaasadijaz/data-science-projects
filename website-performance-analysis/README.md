# Website Performance Analysis 📊
This repository contains a data analysis project focused on evaluating website traffic and user engagement metrics. Using Python, the project processes raw export data to visualize trends in user sessions, engagement rates, and peak activity hours.

# 🚀 Project Overview
The goal of this analysis is to understand how users interact with the website over time. By correlating Sessions with Engagement Rates, the project seeks to identify high-traffic periods and determine the quality of user interaction during those times.

# 📊 Key Features & Analysis
Data Preprocessing: - Loading raw CSV data (data-export (1).csv).

Handling timestamp data to extract hourly trends (Date Hour).

Metric Aggregation: - Grouping data by time intervals to calculate average performance metrics.

Analyzing key KPIs: Sessions (traffic volume) and Engagement rate (user quality).

Time-Series Visualization:

Dual-Axis Plotting: A comprehensive line chart comparing "Engagement Rate" (purple) against "Sessions" (orange) on the same timeline to reveal correlations between traffic spikes and user attention.

Identification of peak hours for website activity.

# 🛠️ Tools & Libraries
Python 3

Pandas: For data manipulation and time-series aggregation.

Matplotlib & Seaborn: For plotting complex, dual-axis charts.

NumPy: For numerical operations.

# 📈 Insights Preview
The analysis highlights specific hours where session counts spike, allowing for better server resource management or targeted content scheduling.

The comparison between sessions and engagement rate helps determine if high traffic sources are actually bringing in valuable, engaged users.
