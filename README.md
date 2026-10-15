# Power-bi-finance-dashboard
Power BI finance dashboard project showcasing analytical skills
# Finance Dashboard Portfolio Project

## Overview
A comprehensive financial analysis dashboard built in Power BI Desktop using publicly available sales transaction data from Kaggle. The project demonstrates data modeling, DAX formula development, and analytical visualization techniques for financial performance analysis.

Dataset
Source: Kaggle (public sales transaction dataset)
Period: 2023 sales data
Records: 2,000+ transactions
Dimensions: 4 regions, 4 product categories, 2 sales channels
Note: This is a synthetic/public dataset used for portfolio demonstration purposes
Key Metrics
Total Revenue: £70.33M
Total Profit: £6.49M
Average Profit Margin: 9.22% (weighted: SUM(Profit) ÷ SUM(Revenue))
Technical Implementation
Calculated Columns
Revenue = Unit_Price × Quantity_Sold
COGS = Unit_Cost × Quantity_Sold
Profit = (Unit_Price − Unit_Cost) × Quantity_Sold
Profit_Margin = Profit ÷ Revenue
DAX Measures
Total Revenue = SUM([Revenue])
Total Profit = SUM([Profit])
Avg Margin % = DIVIDE(SUM([Profit]), SUM([Revenue]), 0)
Visualizations
KPI Cards: Headline metrics (Revenue, Profit, Margin %)
Revenue Trend: Monthly revenue Jan 2023–Jan 2024 (line chart)
Revenue by Region: North £18M, East/West £17M, South £16M (column chart)
Revenue by Product Category: Balanced across Clothing, Furniture, Electronics, Food (column chart)
Profit Margin by Region: All regions 9-10% (column chart)
Business Insights

The dashboard reveals a company-wide profitability pattern:

Overall performance: 9.22% margin is healthy for most sectors
Regional consistency: All regions show similar margins (9-10%), suggesting a standardized cost and pricing structure across the business
Revenue volatility: Stable performance through 2023 with a sharp decline in Dec 2023–Jan 2024, indicating operational or market challenges
Category distribution: Revenue is balanced across product lines, ruling out product mix as a primary driver of margin variation
Skills Demonstrated
Data modeling and calculated column design
DAX measure development (weighted vs. simple averages)
Financial analysis and margin calculation
Multi-dimensional visualization design
Problem-solving (diagnosed and corrected revenue calculation error during development)
