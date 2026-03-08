# POWER BI DASHBOARD — RETAIL STORE SALES/PERFORMANCE ANALYSIS

Welcome to my Power BI project wiki!  

In this project, I built an interactive Power BI dashboard to analyze retail store sales data representing a large-scale retail company similar to Walmart. The dashboard helps understand overall sales performance, profitability, customer segments, and product trends, with interactive slicers for easy exploration, along with a sales forecasting view to analyze historical trends and predict the next 15 days of sales using interactive visuals and slicers.

---

# ◾ MY GOAL

My goal was to analyze retail sales data using Power BI to identify key business insights such as:

- Overall sales, profit, and quantity performance  
- Monthly sales and profit trends  
- Best- and worst-performing product categories and sub-categories  
- Regional and state-level sales behavior  

---

# ◾ DATA USED (RETAIL TRANSACTION DATA)

The dataset contains real-world retail information, including:

### Order Details
- Order ID  
- Order Date  
- Ship Date  

### Customer Information
- Consumer  
- Corporate  
- Home Office segments  

### Geographic Data
- Country  
- Region  
- State  
- City  

### Product Details

- Category (Office Supplies, Furniture, Technology)  
- Sub-Category (Phones, Chairs, Binders, Accessories, etc.)  
- Sales Amount  
- Profit  
- Quantity Sold  
- Ship Mode (Standard, Second Class, First Class, Same Day)  
- Payment Mode  

This type of data is commonly analyzed by large retail companies like Walmart to track business performance and profitability.

---

# ◾ PREPARED AND CLEANED DATA

- Verified and corrected data types (dates, numeric fields, categories)  
- Checked for consistency across geographic and product fields  
- Organized data for accurate aggregations and visuals in Power BI  

---

# ◾ CREATED CORE MEASURES (DAX)

Created a dedicated **Measures table** and built key DAX measures, including:

- Total Sales  
- Total Profit  
- Total Quantity  

These measures were used across KPI cards and charts to ensure consistent calculations.

---

# ◾ BUILT DASHBOARD (VISUALS + SLICERS)

Designed a **clean, one-page dashboard** including:

- Top KPI Cards showing Total Sales, Total Profit, and Quantity  
- Monthly Sales YoY line chart to analyze sales trends over time  
- Monthly Profit YoY line chart to track profitability trends  
- Sales by Category bar chart (Office Supplies, Furniture, Technology)  
- Sales by Sub-Category bar chart for detailed product analysis  
- Sales by Segment donut chart (Consumer, Corporate, Home Office)  
- Sales by Payment Mode donut chart  
- Sales by Ship Mode bar chart  
- Sales by Order Date  

Interactive slicers were added for:

- Region (Central, East, South, West) using button-style tabs  
- State-level selection using a map-like button slicer for detailed filtering  

All slicers update the entire dashboard dynamically.

---

# ◾ TESTED INTERACTIVITY

- Verified that Region and State slicers correctly filter all visuals, including historical trends and forecast views  
- Ensured KPI cards, charts, and the 15-day sales forecast update consistently with slicer selections  
- Checked unit formatting (K for thousands, M for millions) across all visuals, including forecast values  
- Validated that zoomed-in trend and forecast visuals respond accurately to user interactions  

---

# ◾ KEY FINDINGS

- Technology and Office Supplies contribute the highest share of total sales  
- The Consumer segment generates the largest portion of revenue  
- Sales and profit exhibit noticeable monthly and daily fluctuations, reflecting seasonality and demand variability  
- Shipping mode and payment method significantly impact overall sales performance  
- Regional and state-level analysis highlights performance differences across locations  
- Historical sales trends show an overall upward movement, which supports the short-term forecast  
- The 15-day sales forecast indicates moderate growth with variability, helping anticipate near-term demand and planning needs  

---

# ◾ SKILLS DEMONSTRATED

- Power BI dashboard development and layout design  
- DAX measures and KPI creation  
- Retail sales, profit, and customer segment analysis  
- Time-series trend analysis and short-term sales forecasting  
- Data cleaning and preparation  
- Interactive reporting using slicers and filters  
- Business-focused data storytelling and decision support  

---

## 📊 Tools Used
**Power BI, DAX**

## 📁 Domain
**Retail Analytics / Business Intelligence**

---

# 📊 VISUALIZATIONS

---

## 1️⃣ KPI CARDS (TOP METRICS)

### Profit Card – 175K  
Shows total profit generated across all selected filters (region, state, category).

Image

---

### Sales Card – 2M  
Displays total revenue from retail transactions.

Image

---

### Quantity Card – 22K  
Represents the total number of products sold.

Image

---

## 2️⃣ SALES BY PAYMENT MODE (DONUT CHART)

Purpose: Understand how customers pay.

Image

- COD – 42.62%  
- Online – 35.38%  
- Cards – 21.99%  

Insight: Cash on Delivery dominates, indicating customer preference and potential logistics impact.

---

## 3️⃣ MONTHLY SALES YoY (LINE / AREA CHART)

Purpose: Track sales trends over time (2019 vs 2020).

Image

- X-axis: Months  
- Y-axis: Sales  

Two lines compare year-over-year performance.

Insight: Sales show steady growth with strong peaks toward year-end, highlighting seasonal demand.

---

## 4️⃣ SALES BY SEGMENT (DONUT CHART)

Customer Contribution to Sales:

Image

- Consumer – 48.09%  
- Corporate – 32.55%  
- Home Office – 19.35%  

Insight: Consumer segment drives nearly half of total sales, making it the primary target group.

---

## 5️⃣ MONTHLY PROFIT YoY (LINE CHART)

Purpose: Analyze profitability trends over time.

Image

Highlights profit fluctuations and identifies months with high or low margins.

Insight: Profit does not always follow sales exactly, indicating cost and discount effects.

---

## 6️⃣ SALES BY CATEGORY (BAR CHART)

Category Performance:

Image

- Office Supplies – 0.6M  
- Technology – 0.5M  
- Furniture – 0.5M  

Insight: Office Supplies generate the highest revenue among categories.

---

## 7️⃣ SALES BY SHIP MODE (HORIZONTAL BAR CHART)

Logistics Performance:

Image

- Standard Class – 0.50M  
- Second Class – 0.17M  
- First Class – 0.11M  
- Same Day – 0.05M  

Insight: Standard shipping is most used, showing cost-efficient delivery preference.

---

## 8️⃣ SALES BY SUB-CATEGORY (BAR CHART)

Top Sub-Categories:

Image

- Phones – 0.20M  
- Chairs – 0.18M  
- Binders – 0.17M  
- Storage – 0.15M  
- Accessories – 0.12M  

Insight: Phones and Chairs are high-revenue products, useful for inventory and marketing focus.

---

## 9️⃣ REGION SLICER (BUTTON TABS)

Image

Central | East | South | West

Allows users to instantly filter the entire dashboard by region.

---

## 🔟 STATE SLICER (MAP-LIKE BUTTON SLICER)

Image

- Replaces traditional map visuals  
- States displayed as rounded buttons  
- Multi-row tile layout  

Insight: Provides map-style geographic filtering without map dependency issues, improving usability and performance.

---

## 11️⃣ SALES BY ORDER DATE (LINE GRAPH)

Purpose: Analyze historical daily sales trends and predict short-term future sales performance.

Image

- Displays daily sales data from 2019 to 2021  
- Green line represents actual historical sales  
- Orange line with shaded region represents the 15-day sales forecast  
- Upper chart shows long-term sales behavior  
- Lower chart provides a zoomed-in recent view for more accurate forecasting  

Insight:

- Sales exhibit high day-to-day variability, common in large-scale retail operations  
- Overall trend shows gradual growth, especially toward late 2020  
- Forecast indicates moderate sales continuation with fluctuations, helping anticipate near-term demand  
- Shaded forecast range highlights uncertainty, allowing better risk-aware planning  

Business Value:

This visualization supports inventory planning, staffing decisions, and demand forecasting, enabling proactive decision-making rather than reactive responses.

---

# ✔ TESTED INTERACTIVITY

✔ All slicers update KPIs and visuals instantly  
✔ Region + State filters work together  
✔ Clean layout ensures easy storytelling  

---

# 🧠 SKILLS DEMONSTRATED

- Power BI Dashboard Design & Storytelling  
- DAX Measures & KPI Creation  
- Retail Sales & Profit Analysis  
- Interactive Slicers (Region & State)  
- Data Modeling & Formatting  
- Business-focused insights  
