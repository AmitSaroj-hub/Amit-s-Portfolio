# Amit's Portfolio Projects
## Following are my Projects

# Project1: National Sales Intelligence Dashboard – Mantra Data Labs Case Study

##  Project Objective
This project showcases a dynamic sales performance dashboard built using Microsoft Excel for a national distributor. The goal was to transform three years of raw transactional data (2022–2024) into actionable insights across product categories, regions, and sales channels. The dashboard enables business stakeholders to monitor trends, evaluate brand growth, and assess promotional effectiveness.

---

##  Dataset Used
**Source:** Provided by Mantra Data Labs  
**Period Covered:** 2022–2024  
**Link:** https://docs.google.com/spreadsheets/d/1lzpXoAgfDlAW0IUsl3DnTAI6eDoPvkY6/edit?gid=2066689394#gid=2066689394

**Key Columns:**
- `date`, `sku`, `brand`, `segment`, `category`, `pack_type`
- `channel`, `region`, `price_unit`, `units_sold`, `delivered_qty`, `stock_available`, `delivery_days`, `promotion_flag`
- Derived: `Year`, `Month`, `MonthName`, `revenue`

---

## 📌 Key Questions (KPIs)
1. Total Revenue Generated  
2. Units Sold Across Time  
3. Delivered Quantity vs Stock Availability  
4. Average Price Per Unit  
5. Revenue Share by Channel  
6. Brand and Category Performance  
7. Promotional vs Non-Promotional Sales  
8. Regional Contribution to Revenue  
9. Monthly Sales Trends  

---

##  Project Process
1. **Data Import & Transformation**
   - Loaded raw sales data into Power Query.
   - Derived four analytical columns:
     - `Year`, `Month`, `MonthName` from the `date` column.
     - `Revenue` by multiplying `price_unit` with `units_sold`.

2. **Data Cleaning**
   - The dataset was mostly clean, requiring minimal preprocessing.

3. **PivotTable Creation**
   - Built PivotTables to analyze revenue, units sold by Year, Channel, Month, Category, Pack Type, and Promotion Flag.

4. **Dashboard Design**
   - Inserted appropriate charts (line, bar, pie) and slicers.
   - Customized layout and formatting for clarity and professionalism.
   - Created a dynamic, interactive dashboard that updates with new data.

---

## 📈 Dashboard Preview
![Sales Dashboard](Add your dashboard image link here)

---

##  Project Insights
- **Balanced Channel Performance:** Revenue is evenly distributed across Discount, E-commerce, and Retail channels (~33% each).  
- **Regional Strength:** PL-Central and PL-South slightly outperform PL-North in revenue contribution.  
- **Promotions Matter:** Promoted products show strong monthly spikes, indicating effective campaign execution.  
- **Top Categories:** Milk and Juice dominate both unit sales and revenue, followed by Yogurt and SnackBar.  
- **Consistent Growth:** Monthly trends show steady growth in both revenue and units sold, with seasonal peaks.  

---

## ✅ Final Conclusion
This project demonstrates how Excel can be leveraged to build a professional-grade dashboard that empowers decision-makers with real-time insights. By integrating slicers, KPIs, and visual analytics, the dashboard supports strategic planning across assortment, promotions, and regional execution. It also highlights Amit’s ability to clean, transform, and visualize complex data in a business-friendly format.
