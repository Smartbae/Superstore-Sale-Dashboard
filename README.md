# SUPERSTORE SALES DASHBOARD

### Project Overview

This data analysis project aims to provide insights into the sales performance of Superstore over the past years. By analysing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding on the company's performance.


![power BI sales dashboard](https://github.com/user-attachments/assets/9bd0ab7a-8c14-4b9b-8d15-43aae3f76ced)


### Data Source

Sales Data: The primary data source use for this analysis is the "Superstore.csv" file containing detailed information about each sale made by the company.

### Tools

- PowerBI - Data Cleaning [Download Here](https://powerBI.com)
- PowerBI - Data Analysis
- PowerBI - Vsualization

### Data Cleaning/Preparation

In the initial data cleaning preparation phase, the following steps where taken:
1. Data loading and Inspection
2. 4 new tables where created
3. Data cleaning and formating

### Exploratory Data Analysis (EDA)

EDA involves exploring the sales data to answer the following questions:

- Total sales
- Total customer
- Total quantity
- Total transactions
- Sales by category
- Sales by month

### Data Analysis

Include some interesting code/features worked with

```PowerBI
Total Quantity = SUM('Superstore (1)'[Quantity])
Total Transactions = COUNTA('Superstore (1)'[Order ID])
```

### Results/Findings

The analysis result are summarised as follows:
1. Sales by category; Technology has the highest sales while technology has the lowest sales.
2. Sales by month; November has the highest sales while February has the lowest sales.
3. Total sales made was $733.22k.
4. Total customers was 793.
5. Total quantity was 12k.
6. Total transactions was 3312.

### Recommendations

Based on the analysis, we recommend the following actions:
- Increase product supply during peak months to meet demands
- Identify reasons for low sales in February and high sales in November and other peak month so as to better leverage on peak month strategy on every month.
- Invest in marketing and promotion during peak months.
  
