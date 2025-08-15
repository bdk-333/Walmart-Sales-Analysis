# Walmart Sales Analysis & Forecasting

## Introduction

This project explores Walmart's sales data [Link to dataset](https://www.kaggle.com/datasets/yasserh/walmart-dataset "Walmart Dataset") to try to understand business patterns, define key performance indicators (KPIs), detect anomalies, and forecast future sales.

---

## Project Plan

1. **Data Cleaning & Initial Exploration**  
   Prepare and validate the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**  
   Visualize and summarize sales trends, patterns, and relationships.
3. **KPI Calculation**  
   Define and compute business metrics like total sales and growth rates.
4. **Sales Forecasting**  
   Predict missing months (Nov/Dec 2012) using Prophet.

---

## Tools & Methodology

- **Python** (pandas, matplotlib, seaborn)
- **Prophet** for time series forecasting
- Jupyter Notebooks for step-by-step analysis

---

## File Summaries & Key Insights

### 01_data_cleaning.ipynb

- Loaded and cleaned the raw sales data.
- Checked for missing values and duplicates.
- Handled incorrect datatypes of features and basic feature engineering.

### 02_exploratory_data_analysis.ipynb

- **Univariate Analysis**: Visualized each feature in the dataset using Histogram, Boxplot and Countplot (Frequency bar plot).
- **Multivariate Analysis**: Visualized Correlation between numeric features, and other plots to analyze multiple features together to see any patterns.
- Compared sales across months, holidays, and holiday events.
- Found clear seasonality: sales spike in Nov-Dec.

### 03_kpi_definition_calculation.ipynb

- Calculated total weekly sales, average sales per store, and growth rates.
- Analyzed top performing stores and their sales in months of highest sales.
- Analyzed year-over-year and month-over-month percentage changes.

### 04_sales_forecasting.ipynb

- Used Prophet to forecast sales for November and December 2012 (missing in the dataset).
- The model predicted strong sales increases for these months, in line with previous years' holiday trends.
- Visualized forecast results and highlighted expected peaks for Thanksgiving and Christmas.

---

## Conclusion

This project provided me with hands-on experience with data cleaning, EDA, KPI analysis, anomaly detection, and time series forecasting. The analysis confirmed expected retail patterns, such as holiday sales spikes and seasonal trends.

However, I think that if the data had more features like region, some detail about the products sold and their categories, more years, then this project could have been even better for learning as well as showcasing skills in data analysis.

---

## Future Work & Ideas

- Add more advanced anomaly detection methods (e.g., Isolation Forest).
- Build an interactive dashboard for real-time KPI tracking.
- Try other forecasting models and compare results.
- Explore store-level segmentation to find natural grouping among the stores.

---
