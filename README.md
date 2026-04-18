# 📦 Retail Sales Forecasting & Inventory Optimization System

A data science project that analyzes retail sales data, forecasts future demand using Machine Learning, and generates inventory optimization recommendations.

## 📊 Project Overview

| Item | Details |
|---|---|
| Dataset | Synthetic — 525 weekly records, 5 products, 2 years |
| Models Used | Linear Regression |
| Best R² Score | 0.923 (Rice 5kg) |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn |

## 🔍 What This Project Does

- Generates realistic retail sales data with seasonality and trend
- Performs full EDA across 5 product categories
- Trains individual forecasting models per product
- Calculates **safety stock** and **reorder points** using industry formulas
- Flags which products need immediate restocking

## 📈 Output Charts

### Sales Trend
![Sales Trend](chart1_sales_trend.png)

### Forecast Results
![Forecast](chart4_forecast_results.png)

### Inventory Optimization
![Inventory](chart5_inventory.png)

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression)

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open `Retail_Sales_Forecasting.ipynb` in Jupyter and run all cells.

## 📁 Files

| File | Description |
|---|---|
| `Retail_Sales_Forecasting.ipynb` | Main notebook — all code |
| `retail_sales.csv` | Generated sales dataset |
| `inventory_report.csv` | Reorder recommendations output |
| `chart1_sales_trend.png` | Weekly sales trend chart |
| `chart4_forecast_results.png` | Actual vs predicted forecast |
| `chart5_inventory.png` | Inventory health dashboard |
