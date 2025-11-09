# Bakery Sales & Revenue Interactive Dashboard  
**(Built 100% in Power BI)**  

## Project Objective  
Create a fully interactive Power BI dashboard for **"The Grand American Bakery & Pastry House"** that tracks sales, costs, and profit across Years, Quarters, States, Customers, and Cookie Types — with real-time filtering via slicers to skyrocket profitability!  

## Dataset Used  
[Download Full Dataset (excel files)](https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/tree/main/Dataset)  

## Questions (KPIs) Answered Instantly  
- Total Revenue = $4.7M | Total Profit = $2.7M across 2019-2020  
- #1 Cookie = **Chocolate Chip** → $1.7M (37% of total revenue)  
- VIP Customer = **ACME Bites** → $830K profit  
- Top 5 States generate 92% of revenue  
- Monthly & quarterly trends (interactive line chart)  
- Revenue split by customer (Donut + Map)  

## Dashboard Interaction (Click any slicer → everything updates live)  
[Main Dashboard](https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/blob/main/Bakery_Main_Dashboard.png)  
[Chocolate Chip Deep-Dive](https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/blob/main/Chocolate_Chip_Dashboard.png)  
[ACME Bites Customer Focus](https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/blob/main/ACME_Bites_Dashboard.png)  

## Process (Pro Level – Step by Step)  
1. **Data Collection** → 4 tables (Orders, Customers, Products, Locations)  
2. **Data Cleaning** → Power Query (removed duplicates, fixed data types, filled nulls)  
3. **Data Modeling** → Star Schema + Active Relationships  
4. **DAX Measures** →  
   ```dax
   Total Revenue = SUM(Orders[Revenue])  
   Total Cost = SUM(Orders[Cost])  
   Total Profit = [Total Revenue] - [Total Cost]  
   Profit % = DIVIDE([Total Profit], [Total Revenue])

 Interactive Slicers → Year, Quarter, State, Customer Name, Cookie Type
Visuals → Line Chart, Bubble Map, Donut Chart, Bar Chart, KPI Cards, Sparkline
Design → Warm pastel theme + bakery photos + custom tooltips

Dashboard Screenshots (Click to enlarge)
<img src="https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/blob/main/Bakery_Main_Dashboard.png" alt="Main Dashboard">
<img src="https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/blob/main/Chocolate_Chip_Dashboard.png" alt="Chocolate Chip Focus">
<img src="https://github.com/YOUR-USERNAME/Bakery-Sales-Revenue-PowerBI-Dashboard/blob/main/ACME_Bites_Dashboard.png" alt="ACME Bites Deep Dive">

## Key Insights That Will Change Your Strategy

Chocolate Chip dominates with $1.7M revenue
ACME Bites single-handedly delivers $830K profit → give them VIP treatment!
Huge Q4 2019 spike, then 2020 drop (COVID impact visible instantly)
Only 5 states = 92% revenue → double down marketing there
White Chocolate & Oatmeal = low margin → consider price increase or discontinuation

## Final Conclusion :
This isn’t just a report… it’s a real-time profit machine.
One click on any slicer and you instantly see where to produce more, where to cut losses, and which customer deserves a golden cookie!
