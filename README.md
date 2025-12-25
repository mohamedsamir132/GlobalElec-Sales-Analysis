# Global Electronics Sales Dashboard (Power BI)

## 📊 Project Overview
This business intelligence project analyzes sales data for "Global Electronics," a consumer electronics retailer, to identify revenue trends, high-value customers, and underperforming products.

The goal was to transform raw sales data into actionable insights for three key stakeholders: the **C-Suite (Executive)**, the **Product Management Team**, and the **Marketing Team**.

**Live Dashboard:** [Click here to view the interactive report](PASTE_YOUR_PUBLISH_TO_WEB_LINK_HERE)

## 📈 Key Performance Indicators (KPIs)
* **Total Revenue:** $9.29 Million
* **Total Profit:** $5.45 Million
* **Profit Margin:** 58.58%
* **Avg Delivery Speed:** 4.5 Days (Beating the 5-day target)

## 🛠️ Tools & Technologies
* **Power BI:** Data visualization, DAX (Data Analysis Expressions), and Data Modeling (Star Schema).
* **Python (Pandas):** Initial data cleaning, handling null values in delivery dates, and currency standardization.
* **SQL Logic:** Utilized for data transformation and relationship management.

## 📷 Dashboard Views

### 1. Executive Dashboard (C-Suite)
*Designed for quick decision-making, focusing on high-level trends and financial health.*
![Executive Dashboard](Screenshots/Executive_Dashboard.png)
* **Key Insight:** Revenue has grown 12% Year-over-Year, with the US market driving the majority of profitability.
* **Feature:** A "PnL Waterfall Chart" visualizes exactly how revenue converts to net profit.

### 2. Products Dashboard (Manager View)
*Focused on inventory optimization and profitability analysis.*
![Products Dashboard](Screenshots/Products_Dashboard.png)
* **Key Insight:** Pareto Analysis (80/20 Rule) revealed that **28% of products generate 80% of revenue**.
* **Action:** Identified a "Kill List" of 15 products with negative profit margins to be discontinued.

### 3. Marketing Dashboard (Marketing View)
*Focused on customer demographics and geographic targeting.*
![Marketing Dashboard](Screenshots/Marketing_Dashboard.png)
* **Key Insight:** The core customer demographic is **Males aged 30-50** living in major metropolitan areas.
* **Feature:** Interactive map drilling down into specific high-value cities.

## 🧠 Business Recommendations
Based on the analysis, the following actions are recommended:
1.  **Inventory Optimization:** Discontinue the bottom 10% of products (identified in the "Kill List") to reduce warehouse costs.
2.  **Marketing Strategy:** Shift ad spend from broad targeting to "High-Value Cities" identified in the heatmap (e.g., New York, London).
3.  **Operational Efficiency:** Maintain the current logistics partner as delivery times (4.5 days) are meeting targets, but investigate "Physical Store" data gaps.

## 📂 File Structure
* `Data/`: Contains the raw CSV files (Sales, Products, Customers).
* `Dashboard/`: The final Power BI file (`GlobalElec_Analysis.pbix`).
* `Screenshots/`: Images used in this README.
