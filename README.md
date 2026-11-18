# Online Retail Sales Analysis

## Project Overview

This project analyzes an online retail transactional dataset to understand sales performance, product performance, customer purchasing behavior, geographic markets, and sales trends.

The goal was to transform raw transaction data into meaningful business insights and actionable recommendations through data cleaning, exploratory data analysis, visualization, and reporting.

## Business Objectives

- Evaluate overall sales performance.
- Identify high-revenue and high-volume products.
- Analyze customer purchasing behavior and repeat purchases.
- Explore revenue performance across countries.
- Understand monthly sales trends.
- Provide data-driven recommendations to support business decisions.

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Power BI
- Data Visualization
- Microsoft Excel (where applicable)

## Dataset

The project uses the Online Retail dataset from the UCI Machine Learning Repository.

The dataset contains transactional records from an online retail business, including invoice numbers, product codes, product descriptions, quantities, transaction dates, unit prices, customer identifiers, and countries.

Dataset source: https://archive.ics.uci.edu/dataset/352/online+retail

## Project Workflow

### 1. Data Understanding & Exploration

- Reviewed the dataset structure and business meaning of each column.
- Examined data types and the transaction date range.
- Identified missing values, duplicates, cancelled invoices, negative quantities, and invalid unit prices.
- Investigated unusual records before deciding how to handle them.

### 2. Data Cleaning & Preparation

- Removed exact duplicate records.
- Investigated cancellation transactions and unusual negative-quantity records.
- Identified zero-price and negative-price records.
- Preserved missing customer identifiers and product descriptions where appropriate for the prepared dataset.
- Converted and validated data types.
- Created a Revenue column using Quantity × UnitPrice.
- Prepared a valid-sales dataset for sales analysis.

### 3. Sales Performance Analysis

Analyzed:

- Total revenue
- Total orders
- Total units sold
- Average order value
- Monthly sales performance
- Product performance
- Customer performance
- Country-level sales

### 4. Customer Analysis

- Identified customers with available customer IDs.
- Compared one-time and repeat customers.
- Analyzed customer revenue and purchasing frequency.
- Examined customer revenue concentration.

### 5. Product Analysis

- Ranked merchandise by revenue and quantity sold.
- Examined product purchasing patterns.
- Applied Pareto analysis to understand revenue concentration across products.

### 6. Geographic Analysis

- Compared sales performance across countries.
- Evaluated the United Kingdom's contribution to overall revenue.
- Identified international markets with potential business opportunities.

### 7. Dashboard & Reporting

- Developed an interactive Power BI dashboard.
- Created a professional analytical report.
- Prepared a presentation summarizing key findings, insights, and recommendations.

## Key Results

| KPI | Result |
|---|---:|
| Original dataset records | 541,909 |
| Valid sales records analyzed | 524,878 |
| Total revenue | £10,642,110.80 |
| Total orders | 19,960 |
| Total units sold | 5,572,420 |
| Average order value | £533.17 |
| Identified customers | 4,338 |
| Repeat customers | 2,845 |
| Repeat customer rate | 65.58% |

## Key Insights

- The United Kingdom contributed approximately 84.59% of total revenue.
- November 2011 recorded the highest monthly revenue, approximately £1.50 million.
- February 2011 recorded the lowest monthly revenue, approximately £522,545.56.
- REGENCY CAKESTAND 3 TIER was the highest-revenue merchandise product, generating approximately £174,156.54.
- PAPER CRAFT, LITTLE BIRDIE recorded the highest quantity sold at 80,995 units, largely associated with a single large transaction.
- Approximately 65.58% of identified customers were repeat customers.
- Product and customer revenue were concentrated among a relatively small portion of the respective groups.

## Pareto Analysis

### Product Revenue Concentration

- Merchandise products analyzed: 3,919.
- The top 20% of products contributed approximately 78.84% of merchandise revenue.
- 825 products, approximately 21.05%, accounted for 80% of merchandise revenue.

### Customer Revenue Concentration

- Identified customers analyzed: 4,338.
- The top 20% of identified customers contributed approximately 74.68% of identified-customer revenue.
- 1,130 customers, approximately 26.05%, accounted for 80% of identified-customer revenue.

## Business Recommendations

1. **Improve Product & Inventory Planning**  
   Prioritize high-revenue products, monitor demand patterns, and improve inventory planning while investigating unusual one-time bulk purchases.

2. **Develop Selected International Markets**  
   Explore opportunities in international markets using country-level revenue and order performance to guide market prioritization.

3. **Strengthen Customer Retention**  
   Develop customer retention initiatives, repeat-purchase campaigns, and targeted engagement strategies to support long-term customer value.

## Limitations

- The dataset covers approximately one year of transactions.
- Some records do not contain customer identifiers, limiting customer-level analysis.
- Revenue analysis does not represent profit because product costs and operating expenses were not available.
- Returns and unusual transactions required careful interpretation.
- The unusually high quantity of one product was associated with a single large transaction and should not automatically be treated as recurring demand.

## Deliverables

- Jupyter Notebook containing data exploration, cleaning, and analysis.
- Cleaned dataset (subject to dataset redistribution permissions).
- Power BI sales dashboard.
- Professional analytical report.
- Project presentation.

## What I Learned

Through this project, I strengthened my skills in data understanding, data cleaning, Pandas, exploratory data analysis, business KPI calculations, product and customer analysis, Pareto analysis, dashboard development, and communicating data-driven business recommendations.

---

**Project Category:** Data Analysis / Business Intelligence  
**Tools:** Python, Pandas, Jupyter Notebook, Power BI  
**Dataset:** UCI Online Retail
