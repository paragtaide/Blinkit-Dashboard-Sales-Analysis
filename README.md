# 🛒 Blinkit Sales & Performance Analysis

## 📌 Project Overview
This project provides a deep-dive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution. Following a formal business requirement process, I developed an interactive Power BI dashboard to track $1.20M in total sales, identifying key growth drivers across various outlet sizes, locations, and product categories.

## 🖼️ Dashboard Preview
![Blinkit Dashboard Summary](05%20Blinkit_Dashboard_Summary.png)

## 🎯 Business Requirements & KPIs
Guided by the formal requirements outlined in `Blinkit_Business_Requirements.pptx`, the dashboard tracks the following primary metrics:
* **Total Sales:** Overall revenue generated ($1.20M).
* **Average Sales:** Revenue per item sold ($141).
* **Number of Items:** Total count of unique products in inventory (8,523).
* **Average Rating:** Average customer satisfaction score (3.9/5.0).

## 🚀 Key Business Insights
* **Consumer Preference:** 'Regular' fat products significantly outperform 'Low Fat' alternatives, contributing $776K to total revenue.
* **Geographic Performance:** Tier 3 locations are the primary revenue drivers, showing higher sales volume compared to Tier 1 and Tier 2 cities.
* **Outlet Maturity:** Outlets established in 2018 reached a peak performance of $204K, demonstrating the success of newer outlet strategies.
* **Inventory Distribution:** Fruits, Vegetables, and Snack Foods represent the highest transaction volumes, serving as the core categories for the platform.

## 🛠️ Technical Stack
* **Database:** MySQL (Data exploration, standardization, and KPI validation)
* **Visualization:** Power BI Desktop
* **ETL & Data Cleaning:** Power Query (M Language) used for handling inconsistent labeling (LF/reg/low fat)
* **Data Modeling:** Star Schema architecture for optimized cross-filtering
* **Documentation:** Microsoft PowerPoint (Business Requirement Analysis)

## 📁 Repository Structure
* **`01 Blinkit_Sales_Analysis.pbix`**: The final interactive Power BI report.
* **`02 Blinkit_SQL_Validation.sql`**: SQL scripts used to clean data and verify dashboard totals.
* **`03 Blinkit_Grocery_Data.xlsx`**: Raw transactional dataset.
* **`04 Blinkit_Business_Requirements.pptx`**: Detailed business requirement documentation (BRD).
* **`Blinkit_Dashboard_Summary.png`**: High-resolution preview of the final dashboard.

## ⚙️ Project Workflow
1.  **Requirement Analysis:** Defined project scope and KPIs based on the `Blinkit_Business_Requirements.pptx`.
2.  **SQL Engineering:** Used SQL to standardize the `Item_Fat_Content` field and performed exploratory data analysis (EDA).
3.  **Data Modeling:** Built a relationship-based model (Star Schema) to ensure high-performance filtering.
4.  **DAX Development:** Created custom measures for Average Rating, Sales Distribution, and Tier-based performance.
5.  **Validation:** Cross-referenced all Power BI visual totals with results from `Blinkit_SQL_Validation.sql` to ensure 100% data accuracy.

---
**Developed by:** Parag Taide  
**LinkedIn:** https://www.linkedin.com/in/paragtaide/
