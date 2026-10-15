# 💳 Credit Card Fraud Risk Analysis | Power BI Dashboard

## 📌 Project Overview

The **Credit Card Fraud Risk Analysis Dashboard** is an interactive Power BI project designed to analyze fraudulent credit card transactions, assess fraud risk, and identify patterns across transaction categories, geographic locations, merchants, and time.

The dashboard helps users monitor fraud-related KPIs, explore transaction amounts by fraud type and risk level, and identify locations and periods with higher fraudulent transaction counts.

## 🎯 Project Objectives

- Analyze fraudulent transactions and their associated transaction amounts.
- Monitor the overall fraud rate and critical-risk transactions.
- Identify fraud patterns across different transaction categories.
- Compare fraudulent transaction counts across states.
- Track monthly trends in fraudulent transactions.
- Identify the most prominent fraud type.
- Enable interactive analysis using filters for fraud type, state, and merchant.

## 🛠️ Tools & Technologies

- **Power BI** – Interactive dashboard development and data visualization
- **DAX** – KPI calculations and analytical measures
- **Power Query** – Data transformation and preparation, where applicable
- **Data Visualization** – KPI cards, bar charts, donut charts, column charts, and line charts

## 📊 Dashboard Features

### 1. Key Performance Indicators (KPIs)

The dashboard includes the following measures:

- **Fraud Rate %** – Displays the calculated fraud rate.
- **Fraudulent Transactions** – Shows the number of transactions classified as fraudulent.
- **Critical Risk Transactions** – Tracks transactions categorized as critical risk.
- **Fraudulent Transaction Amount** – Measures the amount associated with fraudulent transactions.
- **Top Fraud Type** – Highlights the leading fraud type according to the measure's calculation.

### 2. Fraud Type Analysis

A bar chart compares **total transaction amounts by fraud type**, with transaction category used to break down the results.

**Purpose:** Understand how transaction amounts are distributed across fraud types and categories.

### 3. Fraud Risk Distribution

A donut chart displays **total transaction amount by fraud risk level**.

**Purpose:** Compare the transaction amounts associated with different risk classifications.

### 4. State-Wise Fraud Analysis

A column chart compares fraudulent transaction counts across states.

**Purpose:** Identify states contributing higher numbers of fraudulent transactions and investigate potential geographic patterns.

### 5. Monthly Fraud Trend

A line chart tracks fraudulent transactions over time at the monthly level.

**Purpose:** Identify changes in fraud activity, emerging patterns, and months that may require further investigation.

### 6. Interactive Filters

The dashboard includes dropdown slicers for:

- Fraud Type
- State
- Merchant Name

These filters allow users to explore specific segments and investigate fraud patterns interactively.

## 🔍 Business Questions Addressed

1. What is the overall fraud rate?
2. How many fraudulent and critical-risk transactions are recorded?
3. What is the total amount associated with fraudulent transactions?
4. Which fraud types account for higher transaction amounts?
5. How does fraud risk vary by transaction amount?
6. Which states have higher fraudulent transaction counts?
7. How do fraudulent transactions change month over month?
8. How can fraud patterns be explored for individual merchants?

## 💼 Business Value

This dashboard can support fraud-monitoring and risk-analysis activities by helping business teams:

- Monitor key fraud indicators in one place.
- Identify transaction categories and locations that deserve further investigation.
- Track changes in fraudulent transaction activity over time.
- Compare risk classifications and transaction amounts.
- Investigate specific merchants and fraud types through interactive filtering.
- Support data-driven decisions about where to prioritize fraud reviews.

**Note:** The dashboard supports fraud analysis and investigation. It does not, by itself, establish the cause of fraud or predict future fraud unless additional predictive modeling is implemented.

## 📈 Analytical Approach

The project organizes transaction data into business-focused views:

1. **KPI monitoring:** Review the main fraud indicators.
2. **Category analysis:** Compare transaction amounts across fraud types and categories.
3. **Risk analysis:** Examine amounts associated with risk classifications.
4. **Geographic analysis:** Compare fraudulent transaction counts across states.
5. **Trend analysis:** Review monthly changes in fraudulent transactions.
6. **Interactive investigation:** Apply slicers to analyze selected merchants, states, and fraud types.

## 🚀 Skills Demonstrated

- Power BI dashboard development
- DAX measures and KPI reporting
- Data visualization and storytelling
- Fraud risk and transaction analysis
- Time-series trend analysis
- Geographic and category-based analysis
- Interactive report design
- Business-focused analytical thinking

## 📁 Project File

- `Credit Card Fraud Risk Analysis.pbix` – Power BI report containing the dashboard visuals, measures, and interactive filters.

## ▶️ How to Use the Dashboard

1. Download the `.pbix` file from this repository.
2. Open it using Microsoft Power BI Desktop.
3. Review the KPI cards to understand the main fraud indicators.
4. Explore the charts to compare fraud types, risk levels, states, and monthly trends.
5. Use the dropdown slicers to investigate particular fraud types, states, or merchants.

## 👨‍💻 Conclusion

The Credit Card Fraud Risk Analysis Dashboard demonstrates how Power BI can transform transaction data into an interactive fraud-monitoring report. By combining KPI cards, risk distribution, category analysis, state-wise comparisons, and monthly trends, the project provides a structured way to explore potential fraud patterns and support further investigation.

---

**Project Type:** Data Analytics | Business Intelligence  
**Domain:** Banking & Financial Services  
**Primary Tool:** Microsoft Power BI  
**Author:** Shahnawaj Siddique
