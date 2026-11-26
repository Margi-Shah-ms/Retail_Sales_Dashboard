# 📊 Retail Sales Performance Dashboard & Executive Analytics

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Dashboard-blue?style=for-the-badge&logo=analytics)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-Pivot_Tables-orange?style=for-the-badge)
![License](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

An end-to-end interactive **Retail Sales Performance Analysis** and **Executive Dashboard** built in Microsoft Excel. This project transforms raw, unstructured sales transaction data (**9,994 line items** across **5,009 unique orders**) into dynamic business insights, comprehensive statistical tabs, and an interactive executive presentation board.

---

## 📂 Workbook Architecture

The project workbook is systematically organized across 7 core specialized sheets:

| Sheet Name | Description & Functionality |
| :--- | :--- |
| 📁 **`Data`** | Raw, unformatted source sales dataset containing order details and transaction logs. |
| 🧹 **`Clean_Dataset`** | Formatted and pre-processed structured table (`Table1`) with standardized data types, clean headers, and error handling. |
| 📈 **`Sales_Analysis`** | In-depth breakdown covering Regional Performance, State-wise breakdown, Customer Segments, and Shipping Mode Metrics. |
| 📦 **`Product_Analysis`** | Detailed category, sub-category, Top 10 products analysis (`UNIQUE`, `SORTBY`, `SUMIFS`), and Discount distribution metrics. |
| 📊 **`Pivot_Analysis`** | Aggregated Pivot Tables serving as financial engines powering all charts and KPI cards. |
| 🖥️ **`Dashboard`** | Main interactive visual canvas featuring KPI cards, charts, dynamic Slicers, and a Timeline slicer. |
| 📋 **`Summary`** | High-level Executive Summary, key insights, and strategic business recommendations. |

---

## 🛠️ Step-by-Step Implementation Workflow

Raw Data ➔ Data Cleaning ➔ Analysis Sheets ➔ Pivot Tables ➔ Interactive Dashboard ➔ Executive Summary

### 1. Data Cleaning & Standardization (`Clean_Dataset`)
- Handled missing values, standardized text formatting, and converted the dataset into a structured Excel Table (`Table1`).
- Formatted currency fields (`Sales`, `Profit`) and date columns (`Order Date`, `Ship Date`).
- Calculated custom fields like shipping duration (`Ship Date - Order Date`).

### 2. Multi-Dimensional Data Analysis (`Sales_Analysis` & `Product_Analysis`)
- **Sales & Profit Metrics:** Evaluated overall revenue (**$2.30M**) and net margins (**12.5%**).
- **Regional & State Breakdown:** Identified top-performing zones (**West** & **East** driving **61.1%** share).
- **Category & Discount Insights:** Analyzed product profitability vs. margin erosion caused by heavy discounts in Furniture, and built automated Top 10 product rankings using `UNIQUE`, `SORTBY`, and `SUMIFS`.

### 3. Pivot Engine Setup (`Pivot_Analysis`)
- Created structured Pivot Tables for Category Performance, Regional Distribution, Monthly Sales Trends, Shipping Mode analysis, and Top 10 Products.
- Standardized number formatting and locked column widths to maintain visual stability across refreshes.

### 4. Interactive Dashboard Design (`Dashboard`)
- **KPI Cards:** Top-level visual indicators for Total Sales (**$2.30M**), Profit (**$286.4K**), Profit Margin % (**12.5%**), Unique Orders (**5,009**), and AOV (**$458.61**).
- **Dynamic Charts:**
  - 📊 **Sales by Category:** Bar chart comparing revenue vs. profit across categories.
  - 📈 **Monthly Sales Trend:** Line chart showcasing seasonality spikes (Q4 Peak).
  - 🍩 **Sales by Region:** Donut chart highlighting regional market share.
  - 📉 **Discount Range Distribution:** Histogram mapping discount frequencies.
- **Interactivity:** Integrated synchronized **Slicers** (*Region*, *Ship Mode*, *Segment*) and an **Order Date Timeline** using Report Connections.

---

## 📊 Key Business Insights & Executive Summary

- 💰 **Total Sales:** $2,297,200.86
- 💵 **Total Profit:** $286,397.02
- 📈 **Profit Margin:** 12.5%
- 📦 **Unique Orders:** 5,009 *(from 9,994 line items)*
- 🛒 **Avg Order Value (AOV):** $458.61

### 💡 Core Observations
1. **Category Performance:** **Technology** is the primary profit generator (**$145.5K** profit), whereas **Furniture** shows high sales (**$742.0K**) but compressed net profit (**$18.5K**) due to freight costs and steep average discounts (**17.39%**).
2. **Regional Dominance:** The **West** (**31.6%**) and **East** (**29.5%**) regions drive **61.1%** of total business revenue, followed by **Central** (**21.8%**) and **South** (**17.1%**).
3. **Top Product Performer:** **Canon imageCLASS 2200 Advanced Copier** leads both revenue (**$61,599.82**) and profit (**$25,199.93**).
4. **Q4 Seasonality:** Demand surges drastically in Q4, peaking in **November ($352K)** and **December ($325K)**.
5. **Fulfillment:** **Standard Class** handles **59.7%** of total shipping line items (**5,968** items).

---
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=217346&height=120&section=header&text=DASHBOARD&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%" />
</p>
<img width="822" height="485" alt="image" src="https://github.com/user-attachments/assets/7b9cbd8b-da0c-48b4-9cd8-26e622356879" />

## 🎯 Strategic Recommendations

- 🔹 **Furniture Margin Optimization:** Restructure pricing and cap maximum allowable discounts (especially on *Tables* and *Bookcases*) under 20% to protect margins.
- 🔹 **Q4 Inventory Prep:** Scale supply chain capacity by late Q3 to prevent stockouts during peak holiday demand.
- 🔹 **Regional Expansion:** Develop targeted marketing and logistical support in Central and South territories.

---

## 💻 Tech Stack & Tools Used

- **Spreadsheet Tool:** Microsoft Excel 365
- **Analytics Techniques:** Data
