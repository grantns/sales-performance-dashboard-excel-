# Sales Performance Analysis and Dashboard

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Primary Software and Built-in Tools Used](#primary-software-and-built-in-tools-used)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results or Findings](#results-or-findings)
- [Recomendations](#recomendations)
- [Limitations](#limitations)

### Project Overview
---

The primary objective of this project was to design and develop an interactive, comprehensive Sales Performance Dashboard within Excel. The dashboard consolidates raw transactional data to track, analyze, and visualize key sales performance metrics, profitability trends, and customer behaviors over a multi-year period (2022–2024). This tool empowers stakeholders to make data-driven decisions regarding regional focus, product offerings, and operational efficiency.

<img width="649" height="442" alt="sales dashboard" src="https://github.com/user-attachments/assets/4e130261-0c29-42b0-b542-f0721267fbdb" />



### Data Source
---
Sales Dashboard: The primary dataset used for this sales performance analysis and dashboard is the "sales_dashboard_csv", containing the detailed information about each sale made by the company.

### Primary Software and Built in Tools Used
---
- Microsoft Excel 
- Excel Power Query (ETL Tool) 
- PivotTables & PivotCharts 
- Slicers

### Data Cleaning
---
Excel Power Query was used to clean the raw transactional data. For a sales dataset like this to produce accurate visuals, the following four data cleaning steps were likely performed.
- Handling Missing or Incomplete Values
- Standardizing Categorical Labels
- Data Type Standardization
- Text Truncation and Formatting

### Exploratory Data Analysis
---
EDA involved exploring the sales data to answer key questions such as;

1. Which product categories are the most profitable, and are any underperforming?
2. What percentage of our orders fail to complete, and is it a systemic issue?
3. Which geographical locations are driving the majority of our profits?
4. What is our overall financial health, and are there seasonal patterns in our sales?

### Data Analysis
---
1. Data Aggregation & Summarization
   -   Summing up the entire revenue and profit columns.
   -   Counting the total distinct order IDs to calculate the 11,632 total orders. 

2. Profitability Margin & Ratio Calculations
   - Profit Margin Calculation: This required applying the financial formula for each transaction.
   - This analysis revealed that the business operates at an Average Profit Margin of 35.2%, proving the business model is highly lucrative despite operational hurdles.

3. Categorical & Geographical Ranking Analysis
   - Time-Series Analysis: Aggregating financial metrics by calendar month to analyze stability and verify that revenue and profit move in parallel without massive seasonal drops.
   - Pareto/Ranking Analysis: Sorting profits by City and Product Category from highest to lowest. This analysis isolated the critical few drivers of the business, proving that just two cities (Lisbon and London) command nearly 60% of all company profits.
  
**THE DATA ANALYSIS PROCESS IS SHOWN IN IMAGE BELOW:**
  
<img width="739" height="338" alt="Analysis" src="https://github.com/user-attachments/assets/8ae794b1-997d-4c55-b4ac-c51c88dfd048" />



### Results or Findings
---
- Strong Financial Foundations:
The business is highly lucrative, generating $15.55M in Total Revenue across 11,632 orders, while maintaining a very healthy Average Profit Margin of 35.2% (yielding $5.45M in Total Profit).
- High Revenue Stability:
The Revenue Trend By Month shows remarkable consistency throughout the year. There are no severe seasonal drops or massive holiday spikes; both revenue and profit lines remain stable and tightly correlated month-over-month.
- Geographic Profit Concentration:
Profits are heavily centralized in just two major hubs. Lisbon (30%) and London (29%) together drive nearly 60% of the company’s total profit. Meanwhile, Paris and Berlin are underperforming, combining for less than a quarter of total profits.
- Critical Operational Bottleneck:
The most alarming finding is the Order Status Breakdown. Only 33% of orders are successfully "Completed." The remaining 67% are trapped in "Pending" (34%) or have been "Cancelled" (33%). This represents a massive operational inefficiency in order fulfillment or payment processing that is likely leaving significant additional revenue on the table.

### Recomendations
---
- **Fix Order Pipeline**: Investigate the backend systems immediately to resolve why 67% of orders are failing to finish (stuck in "Pending" or "Cancelled").

- **Scale Top Hubs**: Reallocate marketing budget to double-down on Lisbon and London, which drive 59% of total profits.

- **Optimize Menu Mix**: Implement high-margin product bundling (e.g., pairing sides or chicken with beverages) to boost average order value.

### Limitations 
---
- While the dashboard successfully flags a critical operational failure that 67% of orders are Pending or Cancelled it lacks the granular data fields (such as cancellation reasons, payment failure codes, or delivery delay times) required to explain why this bottleneck is happening.





