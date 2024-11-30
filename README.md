# BUSINESS-INSIGHTS-360

**Problem Statement:**
The sales director faces challenges in tracking sales and understanding the business's performance.This initiative aims to outpace competitors in the market and enable data-driven decision-making. The project is expected to address stakeholders' questions across various aspects and provides insights like sales quantity, revenue, profit, profit margin, top customers, top markets, and revenue trend.
I worked on this project as part of my Power BI course from Codebasics .

**Tech Stack**
*SQL
*Power BI Desktop
*Excel
*DAX
*DAX Studio (For Optimizing Report)

**What did I learn?**
*Basics of Power Bi
*Questions to be asked before the project
*Stakeholder Management, Stakeholder Mapping Analysis
*Importing data from SQL , Excel
*ETL (Extract,Transform,Load)
*Creating measures using DAX 
*Creating Calculated Columns
*Data Modelling [Star Schema, Snowflake Schema]
*Using Bookmarks to switch between visuals
*Creating tooltip
*Page Navigation with buttons
*Creating date table using M language
*Dynamic Titles based on applied filters
*Choosing the right visuals
*Power Bi Services 
*Publishing the dashboard to Power Bi Services
*Optimizing Report Using DAX studio
*Query folding
*Data validation techniques 
*Supply Chain Basics

**Business terms** : 
*Gross Price
*Pre-invoice deductions
*Net Invoice Sales
*Post-invoice  Deductions
*Net Sales
*Cost of Goods Sold (COGS)
*Gross Margin
*YTD (Year To Date)
*YTG (Year To Go)
*Net Error
*Abs Error
*Forecast Accuracy

**Knowing The Data **
Understanding the dataset before starting data analysis is extremely important, as it lays the foundation for effective and accurate insights. 
Dimension Table : A dimension table contains descriptive attributes (also known as metadata) that provide context to the facts in the fact table. 
Fact Table : A fact table contains quantitative data or metrics that can be measured and analyzed. It forms the core of a star schema and is often surrounded by dimension tables.
In this project we have 2 databases gdb041,gdb056

gdb041:
dim_customer : This table contains customer_code,customer,platform,(Brick & mortar , online store) , Channel(Retailer,Direct,Distributor)
dim_market : This table contains sub_zone, region(APAC,EU,LATAM,NA),market(ex:India,China,Japan)
dim_product : This table contains product_code,division,segment,category product, variant.
fact_forecast_monthly : This table contains data related to predictions or forecasts for a specific period, broken down by month. 
fact_forecast_sales : This table  aggregated sales data for analysis on a monthly basis.

gdb056:
freight_cost  : This table contains travel cost, other costs for each market within the fiscal year.
gross_price : This table contains gross_price with fiscal_year and product_code
manufacturing_cost : This table contains manufacturing costs.
post_invoice_deductions : This table contains post invoice deductions and other deductions.
pre_invoice_deductions : This table contains pre invoice deductions for each customer.





               




















