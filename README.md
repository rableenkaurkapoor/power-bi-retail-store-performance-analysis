# POWER BI DASHBOARD — RETAIL STORE PERFORMANCE ANALYSIS

In this project, I built an interactive Power BI dashboard to analyze retail store sales data representing a large-scale retail company similar to Walmart. The dashboard helps understand overall sales performance, profitability, customer segments, and product trends, with interactive slicers for easy exploration, along with a sales forecasting view to analyze historical trends and predict the next 15 days of sales using interactive visuals and slicers.
<img width="975" height="539" alt="image" src="https://github.com/user-attachments/assets/20cc674f-1b50-40bb-a2a2-375edb5c7e2f" />
<img width="975" height="543" alt="image" src="https://github.com/user-attachments/assets/11418a5b-5b50-46f5-8aa4-924e3be1f3a6" />

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

## 1️⃣ KPI CARDS (TOP METRICS)

<img width="1212" height="181" alt="image" src="https://github.com/user-attachments/assets/66fcdf8a-8fa8-48ab-9451-17df02072353" />

### Profit Card – 175K  
Shows total profit generated across all selected filters (region, state, category).

### Sales Card – 2M  
Displays total revenue from retail transactions.

### Quantity Card – 22K  
Represents the total number of products sold.

---

## 2️⃣ SALES BY PAYMENT MODE (DONUT CHART)

Purpose: Understand how customers pay.

<img width="825" height="587" alt="image" src="https://github.com/user-attachments/assets/b023aa27-a545-4d01-ad01-bf46cdf36aa8" />


- COD – 42.62%  
- Online – 35.38%  
- Cards – 21.99%  

Insight: Cash on Delivery dominates, indicating customer preference and potential logistics impact.

---

## 3️⃣ MONTHLY SALES YoY (LINE / AREA CHART)

Purpose: Track sales trends over time (2019 vs 2020).

<img width="818" height="471" alt="image" src="https://github.com/user-attachments/assets/5062f5b4-2905-4eec-9b1d-9ff3cff895c6" />


- X-axis: Months  
- Y-axis: Sales  

Two lines compare year-over-year performance.

Insight: Sales show steady growth with strong peaks toward year-end, highlighting seasonal demand.

---

## 4️⃣ SALES BY SEGMENT (DONUT CHART)

Purpose: Customer Contribution to Sales

<img width="832" height="558" alt="image" src="https://github.com/user-attachments/assets/8978fa3b-4fef-459e-901a-64313f83b0ae" />

- Consumer – 48.09%  
- Corporate – 32.55%  
- Home Office – 19.35%  

Insight: Consumer segment drives nearly half of total sales, making it the primary target group.

---

## 5️⃣ MONTHLY PROFIT YoY (LINE CHART)

Purpose: Analyze profitability trends over time.

<img width="807" height="451" alt="image" src="https://github.com/user-attachments/assets/df104357-2ff2-4898-bbcb-76a959af301e" />

Highlights profit fluctuations and identifies months with high or low margins.

Insight: Profit does not always follow sales exactly, indicating cost and discount effects.

---

## 6️⃣ SALES BY CATEGORY (BAR CHART)

Category Performance:

<img width="502" height="591" alt="image" src="https://github.com/user-attachments/assets/3e652689-7ec3-4454-9d40-400b69247725" />

- Office Supplies – 0.6M  
- Technology – 0.5M  
- Furniture – 0.5M  

Insight: Office Supplies generate the highest revenue among categories.

---

## 7️⃣ SALES BY SHIP MODE (HORIZONTAL BAR CHART)

Logistics Performance:

<img width="497" height="662" alt="image" src="https://github.com/user-attachments/assets/e391b786-5a54-4167-9f2b-2bc37c06f664" />

- Standard Class – 0.50M  
- Second Class – 0.17M  
- First Class – 0.11M  
- Same Day – 0.05M  

Insight: Standard shipping is most used, showing cost-efficient delivery preference.

---

## 8️⃣ SALES BY SUB-CATEGORY (BAR CHART)

Top Sub-Categories:

<img width="562" height="637" alt="image" src="https://github.com/user-attachments/assets/36c5d847-4bcf-4afb-8192-86e189c0ecce" />

- Phones – 0.20M  
- Chairs – 0.18M  
- Binders – 0.17M  
- Storage – 0.15M  
- Accessories – 0.12M  

Insight: Phones and Chairs are high-revenue products, useful for inventory and marketing focus.

---

## 9️⃣ REGION SLICER (BUTTON TABS)

<img width="812" height="131" alt="image" src="https://github.com/user-attachments/assets/158b80be-1ffe-428b-b71c-0bdb37bf14dc" />

Central | East | South | West

Allows users to instantly filter the entire dashboard by region.

---

## 🔟 STATE SLICER (MAP-LIKE BUTTON SLICER)

<img width="485" height="640" alt="image" src="https://github.com/user-attachments/assets/9e21eeec-8b82-4246-b578-89f744341e57" />

- Replaces traditional map visuals  
- States displayed as rounded buttons  
- Multi-row tile layout  

Insight: Provides map-style geographic filtering without map dependency issues, improving usability and performance.

---

## 1️⃣1️⃣ SALES BY ORDER DATE (LINE GRAPH)

Purpose: Analyze historical daily sales trends and predict short-term future sales performance.

<img width="821" height="512" alt="image" src="https://github.com/user-attachments/assets/fcdbcb62-6c6e-4486-8046-42ac2d681d2b" />

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

## 🛠 Tools Used

- **Power BI** – Built an interactive dashboard to analyze retail sales performance, profitability, customer segments, and product trends using multiple visuals and slicers.

- **DAX (Data Analysis Expressions)** – Created core measures such as Total Sales, Total Profit, and Total Quantity to power KPI cards and ensure consistent calculations across visuals.

- **Power Query** – Performed basic data preparation including verifying data types, organizing fields, and preparing the dataset for accurate analysis and visualization.

- **Excel / CSV Dataset** – Used retail transaction data containing order details, customer segments, geographic information, and product sales records for analysis.

- **PowerPoint** – Recorded and presented the dashboard walkthrough explaining the visualizations, insights, and interactive features of the project.
