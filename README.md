# Sales and Finance Analysis

This project provides sales and finance analysis reports based on data provided by Atliq Hardwares. This project utilizes Excel spreadsheets enhanced with **Power Pivot** for data analysis and report generation.

## Description

This project offers valuable insights into Atliq Hardwares' sales and financial performance through pre-built Excel reports. Leveraging the power of Power Pivot, the spreadsheets are designed to efficiently process and analyze datasets, providing key performance indicators (KPIs), trends, and visualizations to support informed business decisions. The reports cover a range of analyses, from sales performance by product category to detailed financial summaries.

## Usage

1. **Data Input Format:** The project requires input data in a specific format. The data is structured according to the following schema (illustrated in [Data_Model.png](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/Data_Model.png)):

*   **dim_customer (Customer Dimensions):**
    *   customer_code (Text): Unique identifier for each customer.
    *   customer (Text): Name of the customer.
    *   market (Text): Market segment the customer belongs to.
    *   platform (Text): Platform used by the customer (e.g., Online, Retail).
    *   channel (Text): Sales channel used by the customer.

*   **fact_sales_monthly (Monthly Sales Facts):**
    *   date (Date): Date of the sales transaction.
    *   product_code (Text): Unique identifier for each product.
    *   customer_code (Text): Unique identifier for the customer.
    *   Qty (Number): Quantity of products sold.
    *   net_sales_amount (Currency): Net sales amount.
    *   freight_cost (Currency): Freight cost associated with the sales.
    *   manufacturing_cost (Currency): Manufacturing cost of the products sold.
    *   cogs (Currency): Cost of Goods Sold.
    *   Netsales (Currency): Net Sales (Please clarify if different from net_sales_amount).
    *   NetSales19 (Currency): Net Sales for 2019.
    *   NetSales20 (Currency): Net Sales for 2020.
    *   NetSales21 (Currency): Net Sales for 2021.
    *   21 vs 20 (Percentage): Percentage change in sales between 2020 and 2021.
    *   target21 (Currency): Sales target for 2021.
    *   2021-target (Currency): Achieved sales against 2021 target.
    *   2021-target% (Percentage): Percentage of 2021 target achieved.
    *   total_cogs (Currency): Total Cost of Goods Sold.
    *   Gross_Margin (Currency): Gross Margin.
    *   GM% (Percentage): Gross Margin Percentage.

*   **dim_market (Market Dimensions):**
    *   market (Text): Name of the market.
    *   sub_zone (Text): Sub-zone within the market.
    *   region (Text): Region the market belongs to.

*   **dim_product (Product Dimensions):**
    *   product_code (Text): Unique identifier for each product.
    *   division (Text): Division the product belongs to.
    *   segment (Text): Segment the product belongs to.
    *   category (Text): Category of the product.
    *   product (Text): Name of the product.
    *   variant (Text): Variant of the product.

*   **dim_date (Date Dimensions):**
    *   date (Date): Date.
    *   month (Text): Month name.
    *   FY (Text): Fiscal Year.
    *   Month Name (Text): Full month name.
    *   Fiscalmonth_no (Number): Fiscal month number.
    *   quarter (Text): Quarter of the year.

*   **ns_targets_2021 (2021 Target Data):**
    *   market (Text): Market.
    *   date (Date): Date (Please clarify the purpose of the date here).
    *   ns_target (Currency): Net Sales Target.

2. **Data Acquisition:** The complete dataset used for these reports is proprietary and cannot be shared publicly. To obtain access to the data, please contact Sparsh Goel at sparshgoel21@gmail.com.

3. **Opening the Reports:** The reports are available in PDF format in this repository. Download the relevant report files to view them. 
4. **Navigating the Reports:** The following reports are available:

*   **Net Sales Performance:** [Net Sales Performance](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/India_Net_Sales_Performance.pdf) - This report shows net sales performance specifically for the India market, likely broken down by customer or other dimensions. 

*   **Market Performance vs Target:** [Market Performance](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/Market_Performance.pdf) - This report compares sales performance against targets for different markets (likely countries or regions). 

*   **Top & Bottom performing Products:** [Top & Bottom Performing Products](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/Top%20%26%20Bottom%20Performing%20Products.pdf) - This report identifies the top 5 and bottom 5 products. 


*   **Top 5 Countries:** [Top 5 Countries](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/Top%205%20Countries.pdf) - This report shows the top 5 countries based on sales performance. 

*   **Division Performance:** [Division Report](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/Division%20Report.pdf) - This report analyzes sales performance by division within the company.
*   **P&L by Fiscal Year:** [P&L Metric By Fiscal Year](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/P%26L%20Metric%20By%20Fiscal%20Year.pdf) - This report shows Profit & Loss metrics (revenue, costs, margin) by fiscal year. 

*   **P&L by Market:** [P&L Metric By Market](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/P%26L%20Metric%20By%20Market.pdf) - This report shows Profit & Loss metrics by market (likely country or region). 

*   **P&L Metrics by Fiscal Month:** [P&L Metrics By Fiscal Month](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/P%26L%20Metrics%20By%20Fiscal%20Month.pdf) - This report shows Profit & Loss metrics broken down by fiscal month. 
*   **GM% by Quarters:** [GM% By Quarters](https://github.com/Codersparsh21/Sales-Finance-Analytics/blob/main/GM%25%20By%20Quarters.pdf) - This report shows Gross Margin Percentage (GM%) broken down by quarter. 
5. **Interacting with the Reports:** The reports are provided in PDF format for viewing. 

6. **Updating the Data:** To update the underlying data for the reports, please contact Sparsh Goel at sparshgoel21@gmail.com.

## Contributing

While this project primarily uses Excel , if you have suggestions for improvements or find any issues, please feel free to open an issue.

## Contact

Sparsh Goel - sparshgoel21@gmail.com
