# 🚴 Bike Sales Performance & Business Intelligence Dashboard

## 📊 Project Overview
This project delivers a comprehensive, end-to-end Business Intelligence solution designed to transform raw, transactional retail data from a global bicycle distributor into actionable operational insights. By engineering a robust data pipeline within **Power BI**, this dashboard empowers executives, regional managers, and inventory stakeholders to track high-level revenue health, monitor brand popularity, and identify top-performing retail locations.

### 🔑 Key Business Questions Answered:
1. Which retail outlets and specific brands are driving the highest revenue?
2. What are the core drivers behind our top-performing storefronts?
3. How can inventory and marketing strategies be optimized based on product performance?

---

## 📸 Dashboard Preview & Data Highlights
*Since a live web-publishing link requires a premium tenant license, the complete multi-page report structure is documented below via high-resolution snapshots. To interact with the slicers, tooltips, and dynamic filters, please download the `.pbix` file from this repository.*

### 🏪 Top Performing Entities & Revenue Leaders
The dashboard successfully isolates critical performance outliers across stores and manufacturing brands:

* **Highest Single Store Revenue:** **Baldwin Bikes** emerged as the undisputed top-performing retail location, driving an exceptional **$5.21 Million** in total sales.
* **Highest Performing Brand:** **Trek** dominated the product distribution network, capturing the highest market share with a total standalone revenue of **$4.60 Million**.

<img src="C:\Users\SUHAIL ALAM\Pictures\Screenshots\Screenshot 2026-05-27 125637.png" alt="Bike Sales Analysis Dashboard Executive Overview" width="100%">

---

## 🛠️ Technical Stack & Skills Demonstrated
* **Business Intelligence Tool:** Microsoft Power BI Desktop
* **Data Extraction & ETL:** Power Query (Advanced M Code filtering, column profiling, data type standardization)
* **Analytical Calculations:** Custom DAX (Data Analysis Expressions) for KPIs and explicit measures
* **UI/UX Design:** High-contrast corporate color palettes, conditional formatting indicators, streamlined navigation, and clutter-free KPI card layouts.

---

## 💡 Strategic Business Insights & Recommendations
* **Capitalize on Store Excellence:** Baldwin Bikes generates a critical baseline percentage of overall retail profits. Conducting an operational audit on Baldwin’s regional demographic layout, foot-traffic strategy, and product mix can provide a blueprint for scaling lower-performing storefronts.
* **Optimize Inventory Around Brand Equity:** Because **Trek** commands an impressive **$4.60M** in revenue, marketing expenditures should prioritize high-margin Trek bundles, while ensuring supply chain pipelines minimize out-of-stock scenarios for key Trek models during peak sales quarters.
* **Cross-Selling Frameworks:** Align cross-selling strategies by placing high-margin accessories and maintenance packages alongside anchor bike sales from premium brands to maximize the average transaction order value (AOV).

---

## 📂 Repository Structural Layout
```text
├── Data/
│   ├── Bike_Sales_Dataset.csv       # Raw clean datasets utilized for modeling
│   └── Regional_Lookups.xlsx        # Dimension mapping source data
├── Images/
│   └── overview_tab.png             # High-resolution screenshot of the dashboard
├── Bike_Sales_Dashboard.pbix        # Comprehensive local Power BI Desktop workbook file
└── README.md                        # Project documentation handbook
