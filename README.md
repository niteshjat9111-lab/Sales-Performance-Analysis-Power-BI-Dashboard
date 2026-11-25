# Sales Performance Analysis & Power BI Dashboard

![Sales Dashboard Preview](Screenshot%202026-11-25%20165934.png)

## Project Overview
An end-to-end data analysis and business intelligence project built on raw sales data (`messy_sales_data`). The goal is to clean messy records and missing values in **Microsoft Excel**, model the dataset, and build an interactive **Power BI** dashboard to monitor revenue, order fulfillment, payment preferences, category performance, and regional trends.

## Data Cleaning & Preparation (Excel)
- **Handled Null & Missing Values:** Filled or standardized missing entries across key columns (`payment_mode`, `discount_pct`, `quantity`) so aggregations and visuals remain accurate.
- **Standardized Formatting:** Cleaned text casing, date formats (`order_date`), status labels (`order_status`), payment modes (`payment_mode`), and city names (`clean_city`).
- **Quality Verification:** Validated numeric revenue fields prior to loading into Power BI Desktop.

### Before Cleaning (Raw Messy Data)
![Raw Messy Excel Data](Screenshot%202026-11-25%20171554.png)

### After Cleaning (Standardized Excel Data)
![Cleaned Excel Data](Screenshot%202026-11-25%20171610.png)

## Interactive Dashboard & Visuals
- **KPI Cards:** Total **Revenue** (`20.56K`) and **Delivered Revenue** (`20.56K`) for quick executive tracking.
- **Revenue by Category:** Comparison across **Electronics**, **Clothing**, **Home & Kitchen**, and **Stationery**.
- **Revenue by Payment Mode:** Donut chart breaking down Credit Card, Debit Card, Cash on Delivery, UPI, and Net Banking.
- **Revenue Trend Over Time:** Timeline tracking daily revenue movement across October dates.
- **Order Status & City Breakdown:** Cross-filtering across order status (*Delivered*, *Pending*, *Returned*) and cities (*Ahmedabad*, *Bengaluru*, *Chandigarh*, *Chennai*, *Dehradun*).

## Key Insights & Recommendations
- **Category Leadership:** **Electronics** generates the highest revenue share among product categories, followed by Clothing, Home & Kitchen, and Stationery.
- **Payment Diversity:** Multiple digital and cash channels contribute to revenue, supporting continued multi-mode checkout options.
- **Fulfillment Tracking:** Monitoring delivered versus pending and returned orders highlights opportunities to reduce unfulfilled volume.

## Tools Used
- **Microsoft Excel:** Data cleaning, null value handling, standardization
- **Power BI Desktop:** Data modeling, DAX measures, interactive report design
