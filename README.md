📊 Super Store Sales Dashboard
📌 Overview
This Power BI dashboard provides an in-depth analysis of superstore sales, covering key metrics such as sales, profit, quantity sold, and sales forecasts. It also includes insights into sales trends, customer segments, shipping modes, and payment methods, helping businesses optimize operations.

🚀 Features
- Sales & Profit Analysis: Breakdown by category, sub-category, and state.
- Shipping Mode Analysis: Insights into preferred delivery methods.
- Sales Forecasting: 15-day predictive insights based on historical trends.
- Geographical Sales Distribution: Interactive map showing sales distribution.
- Segment & Payment Insights: Understanding customer segments and payment preferences.
  
🔍 Data Cleaning Steps

Handling Missing Values:
- Removed null or blank entries in critical fields such as Order Date, Sales, Profit, and State.
- Filled missing values in categorical columns using mode imputation.
  
Data Type Correction:
- Converted Order Date and Ship Date to the correct datetime format.
- Ensured numerical fields (Sales, Profit, Quantity) are in the correct data type.
  
Removing Duplicates:
- Checked and eliminated duplicate rows to ensure data consistency.
  
Outlier Detection & Treatment:
- Used statistical methods (IQR, Z-score) to detect extreme values in Sales and Profit.
- Capped extreme values to avoid skewed analysis.
  
Standardizing Text Data:
- Cleaned inconsistent text formatting in State, Category, and Sub-Category columns.
- Removed extra spaces, special characters, and corrected spelling errors.
  
Feature Engineering:
- Created a Month-Year column for trend analysis.
- Derived a Profit Margin metric for better profitability insights.
  
📂 Dataset Used
- Source: Superstore sales dataset
  
🛠️ Tools Used
- Power BI for visualization and dashboard creation.
- Excel/Python (Pandas, NumPy, Seaborn) for data preprocessing and cleaning.
  
📈 Insights & Takeaways
- California has the highest sales across all states.
- Home Office & Corporate segments contribute significantly to sales.
- Standard shipping is the most used shipping mode.
- Sales tend to peak in Q4 (October - December), indicating seasonal trends.
Forecast suggests a rise in sales for the next 15 days, indicating business growth potential.
📢 Future Improvements
- Integrate real-time sales data for live tracking.
- Implement customer churn analysis for retention strategies.
- Apply machine learning models to improve forecasting accuracy.
