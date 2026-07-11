# Financial-Performance-Analysis

## Project Overview

This project analyzes the financial performance of a business using more than 60,000 transaction records.

The main objective of the project was to understand how the business performed across different years, business segments, regions, and product categories.

The analysis focuses on revenue, profitability, operating costs, and profit margins to identify the major factors affecting overall financial performance.

## Tools Used

- Power BI
- Power Query
- DAX
- Google Sheets

## Dataset

The project uses a synthetic financial dataset containing more than 60,000 transaction records from 2022 to 2025.

The dataset includes information about:

- Business segments
- Product categories
- Products
- Regions
- Customer types
- Sales channels
- Units sold
- Revenue
- Cost of Goods Sold (COGS)
- Gross profit
- Operating expenses
- Operating profit

## Data Cleaning and Transformation

Power Query was used to inspect, clean, and transform the raw dataset before analysis.

The main data preparation steps included:

- Inspecting data quality and column distributions
- Handling missing values
- Standardizing inconsistent text values
- Checking for duplicate transactions
- Correcting data types and percentage formatting
- Preparing the dataset for financial analysis

## DAX Measures

Several DAX measures were created to analyze financial performance, including:

- Total Revenue
- Total Gross Profit
- Total Operating Profit
- Operating Profit Margin %
- Total Transactions
- Total Units Sold
- COGS %
- Operating Expense %

## Dashboard Analysis

The Power BI dashboard was created to analyze:

- Revenue trends over time
- Revenue performance by business segment
- Operating profit margin trends
- Regional revenue performance
- Operating profit by product category
- Key financial and operating KPIs

## Key Insights

- Industrial Products showed the strongest improvement in operating profit margin between 2022 and 2025.

- The operating margin of Industrial Products increased by approximately 9.9 percentage points, mainly due to lower COGS and operating expense ratios.

- Consumer Electronics experienced revenue growth but declining profitability.

- The operating margin of Consumer Electronics declined by approximately 9.9 percentage points, primarily because COGS increased as a percentage of revenue.

- Office Solutions maintained relatively stable profitability during the analyzed period.

- Regional revenue performance varied, while operating profit margins remained relatively consistent across regions.

- Machinery, Tools, and Components were the leading product categories in terms of total operating profit.


## Project Files

- `Financial_Performance_Analysis.pbix` - Power BI dashboard file
- `Financial_Performance_Raw_Data.csv` - Raw dataset used for analysis
- `screenshots/dashboard.png` - Dashboard preview

## Conclusion

This project demonstrates the use of Power Query, DAX, and Power BI to transform raw financial data into meaningful business insights.

The analysis helped identify the business segments contributing to margin expansion and showed how increasing revenue does not always result in improved profitability when costs grow faster than revenue.
