# SQL-Sales-Product-Analytics_Report

Create Database and Schemas

Script Purpose:
    This script creates a new database named 'DataWarehouseAnalytics' after checking if it already exists. 
    If the database exists, it is dropped and recreated. Additionally, this script creates a schema called gold.










1: Product Report

Purpose:
    - This report consolidates key product metrics and behaviors.

Highlights:
    1. Gathers essential fields such as product name, category, subcategory, and cost.
    2. Segments products by revenue to identify High-Performers, Mid-Range, or Low-Performers.
    3. Aggregates product-level metrics:
       - total orders
       - total sales
       - total quantity sold
       - total customers (unique)
       - lifespan (in months)
    4. Calculates valuable KPIs:
       - recency (months since last sale)
       - average order revenue (AOR)
       - average monthly revenue


<img width="1587" height="313" alt="imaGE DE" src="https://github.com/user-attachments/assets/edab7be5-6b79-42ee-a0a8-64ad51024380" />

This SQL view was useful for generating a comprehensive product performance report by aggregating key sales metrics across products. It enabled segmentation into performance tiers (High, Mid, Low) and helped calculate crucial KPIs like average order revenue and monthly revenue. Such insights support data-driven decisions in pricing, inventory, and marketing strategies.

Keypoints from report:

1) The avg_selling_price and avg_order_revenue are identical across each product, suggesting a stable price point per unit sold, particularly for top performers (e.g., 3,575 for Mountain Bikes, 3,578 for Road Bikes).

2) Despite relatively short lifespans (11–12 months), these products show high avg_monthly_revenue (e.g., over 90,000/month for Road-150 series), indicating strong early demand or seasonal popularity.










