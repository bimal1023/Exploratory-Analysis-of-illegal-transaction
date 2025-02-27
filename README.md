# Global Black Money Transactions Analysis

## Overview
The **Global Black Money Transactions** dataset provides insights into illegal financial transactions across various countries. This project analyzes transaction patterns, identifies anomalies, and uncovers trends in **tax evasion, money laundering, and financial fraud** using **R programming**.

## Dataset Information
The dataset consists of **15,000 transactions** with **15 attributes**, including:
- **Country:** Where the transaction occurred.
- **Transaction Type:** Offshore transfers, cash withdrawals, cryptocurrency, etc.
- **Amount (USD):** Transaction value.
- **Industry:** Sector associated with the transaction.
- **Risk Score:** Probability of money laundering.
- **Tax Haven Country:** Whether the transaction involved a tax haven.

## Key Analyses Performed
1. **Exploratory Data Analysis (EDA)**
   - Identified **top countries involved** in black money transactions.
   - Analyzed **most common transaction types**.
   - Visualized **distribution of transaction amounts**.

2. **Data Visualization**
   - **Bar charts**: Number of transactions by country.
   - **Heatmaps**: Transaction amounts by country and type.
   - **Violin plots**: Comparison of black money transactions in Finance vs. Real Estate.

3. **Statistical Analysis**
   - **t-tests** comparing financial transactions across industries.
   - **Correlation analysis** between risk scores and transaction amounts.

4. **Key Findings**
   - **China** had the highest number of transactions.
   - **Panama, Switzerland, and Singapore** were frequent tax haven destinations.
   - **80% of illegal transactions were not reported** to authorities.

## Technologies Used
- **Programming Language:** R
- **Libraries:** ggplot2, dplyr, tidyr, readr, lubridate
- **Tools:** RStudio, Git/GitHub

## Future Work
- Implement machine learning models for anomaly detection.
- Integrate real-time financial transaction data for enhanced monitoring.
- Develop an interactive R Shiny dashboard for data visualization.

