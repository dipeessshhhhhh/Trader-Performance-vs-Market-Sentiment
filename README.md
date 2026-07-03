
# 📊 Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes the relationship between **Bitcoin Market Sentiment (Fear & Greed Index)** and **Hyperliquid trader performance**. The objective is to identify how different market sentiment conditions influence trading behavior, profitability, and overall trading strategies.

The analysis was completed as part of the **Data Science / Analytics Intern – Round 0 Assignment** for **Primetrade.ai**.

---

## Objective

The primary goals of this project are to:

* Analyze the relationship between market sentiment and trader performance.
* Compare trading behavior during Fear and Greed market conditions.
* Identify different trader segments based on trading activity and profitability.
* Generate actionable insights and strategy recommendations supported by data.

---

## Dataset

This project uses two datasets:

### 1. Bitcoin Fear & Greed Index

Contains daily market sentiment information.

**Columns include:**

* Date
* Classification (Fear / Greed / Neutral)
* Sentiment Value

### 2. Hyperliquid Historical Trader Data

Contains historical trade-level information.

**Key fields include:**

* Account
* Trade ID
* Coin
* Execution Price
* Trade Size
* Direction (Long / Short)
* Closed PnL
* Fees
* Timestamp

---

## Tools & Libraries

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Workflow

### 1. Data Preparation

* Loaded both datasets.
* Explored dataset dimensions.
* Checked missing values and duplicates.
* Standardized column names.
* Converted timestamps into daily dates.
* Merged both datasets using trade date.

---

### 2. Feature Engineering

The following features were created for analysis:

* Daily Closed PnL
* Win/Loss Indicator
* Average Trade Size
* Total Trades
* Position Type (Long / Short)
* Trade Frequency
* Sentiment Group
* Trader Performance Summary

---

### 3. Exploratory Data Analysis

The notebook investigates:

* Total PnL by Market Sentiment
* Win Rate across Sentiment Groups
* Trade Frequency
* Long vs Short Trading Behavior
* Average Trade Size
* Trader-Level Performance
* Frequency-Based Trader Segmentation
* Profitability-Based Trader Segmentation

---

## Visualizations

The notebook includes visualizations such as:

* Total PnL by Market Sentiment
* Win Rate by Sentiment
* Trade Count by Sentiment
* Long vs Short Trade Distribution
* Average PnL by Trader Segment

These charts provide evidence for identifying behavioral patterns under different market conditions.

---

## Key Metrics Analyzed

* Closed PnL
* Win Rate
* Trade Frequency
* Average Trade Size
* Long/Short Ratio
* Trader Profitability
* Trader Segmentation

---

## Methodology

1. Load and clean datasets.
2. Convert timestamps into a common daily format.
3. Merge trader and sentiment datasets.
4. Perform feature engineering.
5. Conduct exploratory data analysis.
6. Compare trader behavior across sentiment groups.
7. Segment traders based on trading frequency and profitability.
8. Generate actionable insights and recommendations.

---

## Deliverables

This repository contains:

* `Trader_Performance_Analysis.ipynb` – Complete Jupyter Notebook with code, analysis, and visualizations.
* `historical_data.csv` – Historical Hyperliquid trader dataset.
* `fear_greed_index.csv` – Bitcoin Fear & Greed Index dataset.

---

## Future Improvements

Potential enhancements include:

* Predict trader profitability using machine learning.
* Cluster traders into behavioral archetypes.
* Develop an interactive dashboard using Streamlit.
* Incorporate additional market indicators for deeper analysis.

---

## Conclusion

This project demonstrates a complete data analytics workflow, including data cleaning, feature engineering, exploratory data analysis, trader segmentation, visualization, and strategy-oriented insights. The analysis provides a structured approach to understanding how market sentiment may influence trading behavior and performance, offering a foundation for developing data-driven trading strategies.

---

**Author:** Dipesh Gosavi

**Assignment:** Data Science / Analytics Intern – Round 0 Assignment

**Organization:** Primetrade.ai
