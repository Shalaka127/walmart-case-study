# 🛒 Retail Sales Analysis & Forecasting  
### Walmart Store-Level Weekly Sales Case Study

---

## 📌 Project Overview

Retail businesses operating across multiple locations often struggle to **align inventory with fluctuating customer demand**. Poor demand forecasting can lead to **overstocking, stockouts, and revenue loss**.

This project analyzes **weekly sales data from multiple Walmart stores** to:
- Understand how **economic and environmental factors** affect sales
- Identify **top and low-performing stores**
- Detect **seasonal patterns**
- Forecast **future weekly sales** using time-series modeling

The project combines **Exploratory Data Analysis (EDA)**, **statistical analysis**, and **time-series forecasting** to generate **actionable business insights**.

---

## 🎯 Problem Statement

A retail store chain with multiple outlets across the country is facing challenges in managing inventory to match customer demand.

Using historical weekly sales data, the objective is to:

1. Analyze factors influencing weekly sales  
2. Identify trends and patterns across stores  
3. Evaluate store-wise performance  
4. Forecast future sales to support inventory planning  

---

## 📂 Dataset Description

- **Dataset Name:** `walmart.csv`
- **Number of Records:** 6,435
- **Number of Features:** 8
- **Granularity:** Weekly, store-level data

### Features

| Feature Name | Description |
|-------------|------------|
| Store | Store identifier |
| Date | Week of sales |
| Weekly_Sales | Sales for the given store and week |
| Holiday_Flag | Indicates whether the week includes a holiday |
| Temperature | Temperature on the day of sale |
| Fuel_Price | Fuel cost in the region |
| CPI | Consumer Price Index |
| Unemployment | Unemployment rate |

---

## 🧠 Key Questions Addressed

- Does **unemployment rate** impact weekly sales?  
- Do weekly sales show **seasonal trends**? If yes, why?  
- Does **temperature** influence customer spending?  
- How does **Consumer Price Index (CPI)** affect sales?  
- Which stores are **top-performing** and **underperforming**?  
- How significant is the gap between best and worst-performing stores?  
- Can we **forecast sales** accurately for the next 12 weeks?

---

## 🧪 Project Methodology

The project is structured into **modular notebooks**, each answering a specific business question.

### 1️⃣ Data Understanding & Cleaning
- Data loading and inspection  
- Datetime conversion  
- Missing value handling  
- Summary statistics  

### 2️⃣ Exploratory Data Analysis (EDA)
- Trend and seasonality analysis  
- Sales vs economic indicators  
- Holiday vs non-holiday comparison  
- Store-wise visualization  

### 3️⃣ Statistical Analysis
- Correlation analysis  
- Hypothesis testing  
- Impact assessment of CPI and unemployment  

### 4️⃣ Store Performance Analysis
- Top and bottom performing stores  
- Sales contribution analysis  
- Performance gap evaluation  

### 5️⃣ Sales Forecasting (Time Series)
- Stationarity testing  
- SARIMA model implementation  
- 12-week sales forecasting  
- Model evaluation using MAE and RMSE  

---

## 🔮 Forecasting Model Used

### ✅ Seasonal ARIMA (SARIMA)

**Why SARIMA?**
- Captures trend and seasonality  
- Well-suited for weekly time-series data  
- Highly interpretable  
- Academically and industry accepted  

Forecasts are generated with **confidence intervals** to support data-driven decision-making.

---
## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Environment:** Google Colab  
- **Libraries:**
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - statsmodels  
  - scikit-learn  

---

## 📊 Results & Insights

- Sales exhibit **clear seasonal patterns**, especially around holidays  
- Economic indicators like **unemployment and CPI** influence sales differently across stores  
- A small subset of stores contributes disproportionately to total revenue  
- SARIMA successfully forecasts short-term sales trends, aiding inventory planning  

---

## 📄 Report

A detailed analysis report is available in the `reports/` directory:
- Includes methodology, visuals, insights, and recommendations  
- Suitable for academic submission and business review  

---

## 🚀 Future Enhancements

- Incorporate external holiday calendars  
- Compare SARIMA with Prophet  
- Cluster stores based on sales behavior  
- Build an interactive dashboard (Power BI / Tableau)  

---

