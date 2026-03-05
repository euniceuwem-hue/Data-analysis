Electronic Sales Data Analysis (Power BI)
Project Overview
This project analyzes the Electronic Sales Dataset using Microsoft Power BI to uncover trends, measure performance, and generate business insights.
The analysis focuses on sales performance over time, comparing current performance with previous periods using Time Intelligence calculations.
The goal of this project is to demonstrate the ability to perform data transformation, data modeling, and analytical reporting to support data-driven decision making.

Project Objectives

Extract, transform, and load the Electronic Sales dataset.
Build a Date Table using DAX for time-based analysis.
Perform data modeling by creating relationships between tables.
Develop Time Intelligence Measures for analyzing sales performance.
Build a Power BI dashboard that provides insights across multiple dimensions such as Channel, Product Category, and Zone.
Analyze sales trends, profit performance, and profitability over time.

Tools & Technologies
Microsoft Power BI
Power Query for data transformation
DAX (Data Analysis Expressions) for calculated measures
Data Modeling for relational analysis
Data Visualization for reporting and dashboard creation

Data Preparation (ETL Process)
Extract
The Electronic Sales dataset was imported into Power BI using the Get Data feature.
Transform
Using Power Query, the dataset was cleaned and prepared by:
Removing blank or irrelevant rows
Correcting column data types
Ensuring the Order Date column is formatted as a Date field
Preparing the dataset for time-based analysis

Load
After transformation, the cleaned dataset was loaded into Power BI for modeling and analysis.
Date Table Creation (DAX)
A Date Table was created using DAX to enable Time Intelligence calculations.

Data Modeling
A relationship was created between:
Date Table → Sales Table

Date Table[Date] → Sales[Order Date]

This relationship enables accurate time-based calculations and trend analysis.

Time Intelligence Measures

All calculations were created inside a separate Measure Table for better organization.

Total Sales

Measures the total revenue generated.

Sales Year-To-Date (YTD)

Calculates cumulative sales from the beginning of the year up to the current date.

Sales Quarter-To-Date (QTD)

Calculates cumulative sales within the current quarter.

Same Period Last Year (SPLY)

Compares sales performance with the same time period in the previous year.

Sales Year-on-Year Variance

Measures the difference between current sales and sales from the previous year.

Sales Year-on-Year Variance %

Shows the percentage growth or decline in sales compared to the previous year.

Sales Last Month

Calculates total sales from the previous month for comparison with current performance.

Profit Analysis

Additional measures were created to evaluate profitability:

Total Profit

Profit Margin

Profit Margin shows the percentage of profit relative to total sales.

Dashboard & Visualizations

The Power BI report includes several visuals to analyze the dataset from multiple perspectives.

Sales Trend Analysis

Line charts showing sales performance over time.

Sales by Channel

Bar charts comparing revenue across different sales channels.

Sales by Product Category

Visualizations showing which product categories generate the highest revenue.

Sales by Zone

Regional analysis identifying top-performing zones.

Profit & Profit Margin Trends

Charts displaying profitability trends across years.

KPI Cards

Summary indicators showing:

Total Sales

Total Profit

Profit Margin

Year-on-Year Sales Performance

Key Insights

Some insights derived from the analysis include:

Sales performance shows noticeable variations across different years.

Certain sales channels generate significantly higher revenue than others.

Some product categories contribute more strongly to overall sales.

Profit margins vary across product segments and sales channels.

Regional differences exist in sales performance, highlighting stronger markets.

Project Outcome

This project demonstrates how Power BI can transform raw sales data into actionable business insights through:

Data cleaning and preparation

Data modeling

Time intelligence analysis

Interactive dashboards

The resulting report enables stakeholders to track sales performance, monitor profitability, and identify trends across multiple business dimensions.
