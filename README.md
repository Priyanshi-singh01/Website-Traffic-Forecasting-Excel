# YouTube Channel Views Forecasting (Excel)
This project analyzes historical **YouTube channel view data (2022–2025)** and applies multiple forecasting techniques in **Microsoft Excel** to predict future view trends.  
The goal of this project is to compare different forecasting methods and understand their effectiveness on real-world time-series data.
---

## 📊 Project Objective
To analyze YouTube channel views over time and forecast future trends using multiple Excel-based forecasting techniques.

## Dataset
- Source: YouTube Channel Views
- Time period: 2022–2025
- Metric: Total Views
- Missing values present in historical data

## Key Insights
- ETS forecasting captured view seasonality and produced the most reliable results.
- Polynomial trendline was helpful for understanding non-linear growth patterns.
-  Comparing multiple methods improved confidence in forecasted YouTube views.

## Forecasting Techniques Used
This project applies three different forecasting approaches in Microsoft Excel to predict future website traffic:

1. **FORECAST Function**
   - Linear statistical forecasting based on historical data.
   - Useful for simple trend-based predictions.
     
<img width="204" height="685" alt="Screenshot 2025-12-30 124236" src="https://github.com/user-attachments/assets/ebddb7b9-a9ab-4cc3-977a-1933182b54ee" />

2. **Polynomial Trendline (3rd Order)**
   - Applied using Excel line charts.
   - Helps visualize non-linear patterns in website traffic.
   - Used for comparison and pattern understanding, not for precise forecasting.
     
   <img width="1001" height="487" alt="Screenshot 2025-12-30 124214" src="https://github.com/user-attachments/assets/3d8beff8-e702-4dcb-9a14-0af3ab3e3c46" />

3. **Forecast Sheet (ETS)**
   - Uses Exponential Triple Smoothing.
   - Automatically detects seasonality and trends.
   - Generates confidence intervals for more accurate forecasting.
     <img width="1018" height="480" alt="Screenshot 2025-12-30 124134" src="https://github.com/user-attachments/assets/f68c5bc0-93ef-40ae-b166-29406ced7f75" />

## 👩‍💻 About the Project
Developed by **Priyanshi Singh** as part of a data analytics learning portfolio, focusing on Excel-based time series forecasting.
