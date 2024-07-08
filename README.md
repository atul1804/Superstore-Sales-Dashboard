# Superstore Sales Analysis Project

## Overview
This project utilizes Power BI to analyze Superstore sales data and create interactive dashboards. The data is sourced from an Excel file and various DAX queries have been used to derive insights. The project includes three main dashboards: Overall Sales Data, Customer-Centric Analysis, and Profit Analysis.

## Contents
- [Project Description](#project-description)
- [Data Source](#data-source)
- [DAX Queries](#dax-queries)
- [Dashboards](#dashboards)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description
The Superstore Sales Analysis Project provides a comprehensive analysis of sales data through three interactive dashboards:
1. **Overall Sales Data**: Visualizes key sales metrics and trends.
2. **Customer-Centric Analysis**: Focuses on customer behavior and segmentation.
3. **Profit Analysis**: Analyzes profit margins and performance.

## Data Source
The data for this project is stored in an Excel file named `superstore_sales_data.xlsx`. The Excel file contains various attributes related to sales, including:
- Order Date
- Ship Date
- Sales
- Quantity
- Discount
- Profit
- Product Category
- Customer Information
- Region

## DAX Queries
DAX (Data Analysis Expressions) is used to create custom calculations and aggregations in Power BI. Some of the key DAX queries used in this project include:

1. **Total Sales Calculation**:
   ```dax
   Total Sales = SUM('Sales Data'[Sales])
