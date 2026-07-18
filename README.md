# Global Superstore Sales Analysis — Python EDA

An exploratory data analysis of the Global Superstore dataset, using Python and Pandas to clean raw sales data and answer key business questions around sales trends, profitability, product performance, discounting, and shipping behaviour.

---

## Table of Contents
- [Overview](#overview)
- [Skills](#skills)
- [About This Project](#about-this-project)
- [Data Cleaning & Feature Engineering](#data-cleaning--feature-engineering)
- [Business Questions & Findings](#business-questions--findings)
- [Limitations](#limitations)
- [How to Use](#how-to-use)
- [Author](#author)

---

## Overview
This project analyses multi-year sales data from the Global Superstore dataset to uncover trends in revenue, profitability across markets, category performance, the impact of discounting on margins, and shipping preferences — translating the findings into business recommendations.

## Skills
Python · Pandas · Matplotlib · EDA · Data Cleaning · Data Visualisation

## About This Project
Raw sales data was cleaned and prepared for analysis by parsing date columns, removing duplicates, and dropping null-heavy columns before answering five core business questions using groupby aggregations and visualisations.

## Data Cleaning & Feature Engineering
- Parsed date columns for accurate time-based analysis
- Removed duplicate records
- Dropped null-heavy columns (Postal Code)
- Engineered new features: **Order Year**, **Order Month**, and **Shipping Days**, enabling time-based trend analysis and logistics/delivery performance analysis

## Business Questions & Findings

### 1. Which year had the highest sales?
Sales grew consistently year-on-year, with **2014 recording the highest sales at $4.3M** — indicating strong business momentum across the entire period.

### 2. Which market is most profitable?
**APAC led with $436K in profit**, followed by **EU ($373K)**. **Canada was the least profitable market at $17K**.
> **Recommendation:** The data suggests reallocating marketing and inventory budget toward APAC. Canada's low margin warrants a deeper review of its product mix and pricing strategy.

### 3. Which category drives the most revenue?
**Technology led at $4.7M**, followed by **Furniture ($4.1M)** and **Office Supplies ($3.8M)**.
> **Recommendation:** The data suggests prioritising Technology in promotional planning. Office Supplies shows room for growth through targeted campaigns.

### 4. Does discount lead to loss in profit?
**Yes.** Orders with discounts above 40% consistently showed negative profit across all markets.
> **Recommendation:** The data suggests introducing a discount cap of 30–35% to protect margins on high-discount orders.

### 5. Which ship mode is used the most?
**Standard Class dominated with 59% of all orders.** Same Day delivery was the least used at 5%.
> **Recommendation:** The data suggests exploring incentives to shift customers toward faster shipping tiers to improve overall margins.

## Limitations
- Dataset covers 2011–2014 only and may not reflect current market behaviour.

## How to Use
1. Clone this repository
2. Open the notebook in Jupyter or Google Colab
3. Run all cells to reproduce the data cleaning, feature engineering, and analysis

## Author
**Nischal Danavandi**
