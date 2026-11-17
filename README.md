# Bike Sales Data Analysis

## Project Overview
This project analyzes bike-sharing data using SQL and Power BI to explore sales performance, revenue, profit, and rider trends.

The goal is to transform raw data into meaningful insights that help understand business performance.

## Tools & Technologies
- SQL
- Microsoft Power BI
- Microsoft Excel

## Dataset
The project uses three CSV files:
- `bike_share_yr_0.csv`
- `bike_share_yr_1.csv`
- `cost_table.csv`

## SQL Analysis
SQL was used to:
- Combine yearly bike-sharing datasets using `UNION ALL`.
- Use a Common Table Expression (CTE) to organize the data.
- Join the combined data with the cost table using `LEFT JOIN`.
- Calculate Revenue and Profit.

### Key Calculations

- **Revenue** = Riders × Price
- **Profit** = Revenue − COGS

## Power BI Dashboard
The dashboard presents insights about:
- Revenue and Profit
- Rider Trends
- Bike Sales Performance
- Business Performance Over Time

## Project Structure

- `Dataset/` – Contains the original CSV files.
- `SQL/` – Contains SQL queries used for analysis.
- `Dashboard/` – Contains the Power BI dashboard.
- `Images/` – Contains dashboard screenshots.

## Dashboard Preview

![Bike Sales Dashboard](Images/Dashboard_Screenshot.png)

## Author
Ziad Fouad
