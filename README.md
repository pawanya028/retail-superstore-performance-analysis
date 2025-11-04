# 📊 Superstore Sales Performance Analysis (Power BI Project)

## 📝 Project Overview
This project is an **end-to-end Power BI dashboard** analyzing sales, profit, customers, and operations using the **Superstore dataset**.  
It demonstrates my skills in **Power Query (ETL), Data Modeling, DAX calculations, and Interactive Dashboard Design**.  

The objective was to **convert raw transactional data into actionable business insights** for executives, sales teams, and operations.

---

## ⚙️ Skills Showcased

### 🔹 Data Cleaning & Transformation (Power Query)
- Fixed incorrect **data types** (Dates, Currency, Text).  
- Created calculated columns:
  - Year, Quarter, Month, Order Month Key  
  - Profit Margin %  
  - Ship Days (Order to Delivery)  
  - Discount Bands  
- Merged returns dataset to create **Return Flag**.  

### 🔹 Data Modeling
- Built a **Star Schema**:
  - **Fact Table**: Orders  
  - **Dimension Tables**: Customer, Product, Date, Geography  
- Created a custom **Date Table** for time intelligence.  
- Defined relationships for Customers, Products, Shipping SLA, and Dates.  

### 🔹 DAX Measures
- **Sales & Profit KPIs**: Total Sales, Total Profit, Profit Margin %, Order Count, AOV (Avg Order Value).  
- **Time Intelligence**: YoY Growth, MoM Growth, Running Totals.  
- **Operational KPIs**: On-Time %, Avg Ship Days, Return Rate.  
- **Contribution Metrics**: Sales Share %, Pareto 80/20 analysis.  

### 🔹 Dashboard Design
- **Page 1 – Executive Overview:** Sales, Profit, YoY trends, Sales by Region & Category.  
- **Page 2 – Product & Category Deep Dive:** Profitability, Discounts, Top/Bottom Products.  
- **Page 3 – Geography & Operations:** State-wise Sales, Delivery KPIs, City Leaderboard.  
- **Page 4 – Customer Insights:** Segmentation, Retention, Pareto Analysis, Top Customers.  

---

## 📷 Dashboard Preview

### Page 1 – Executive Overview  
![Overview](Images/page1_overview.png)

### Page 2 – Product & Category Analysis  
![Products](Images/page2_products.png)

### Page 3 – Geography & Operations  
![Geography](Images/page3_geo.png)

### Page 4 – Customer Insights  
![Customers](Images/page4_customers.png)

---

## 🚀 Key Insights
- Sales totaled **$2.3M** with an average **12% profit margin**.  
- **Pareto Analysis:** Top 20% of customers contribute ~48% of sales.  
- **Furniture Sub-category Chairs** had high sales but negative profit → excessive discounting issue.  
- **Standard Class shipping** achieved the highest on-time delivery rate.  
- **California & New York** were the largest contributors to sales, while **Arizona** had unusually high return rates.  

---

## 📌 Files in this Repository
- `Superstore_Sales_Performance_Dashboard.pbix` → Full interactive dashboard.  
- `Superstore_sales_data.csv` → Raw dataset.  
- `images/` → Dashboard screenshots for quick viewing.  

---

## 🎯 What I Learned
- Designing dashboards for different audiences (**executives vs analysts**).  
- Using **visual storytelling** (Pareto analysis, Top/Bottom products).  
- Applying best practices in **Power Query, Data Modeling, and DAX**.  
- Importance of **clean data** for accurate insights.  

---

## 👤 Author
👨‍💻 Created by **Pawan**    
📧 Email:[ pawanya28@gmail.com ] 
-🔗 [LinkedIn Profile](www.linkedin.com/in/pawan-yadav-b59826383) 
