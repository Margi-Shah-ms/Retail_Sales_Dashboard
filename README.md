# 📊 Retail Sales Performance Dashboard & Executive Analytics

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Dashboard-blue?style=for-the-badge&logo=analytics)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-Pivot_Tables-orange?style=for-the-badge)
![License](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

An end-to-end interactive **Retail Sales Performance Analysis** and **Executive Dashboard** built in Microsoft Excel. This project transforms raw, unstructured sales transaction data into dynamic business insights, comprehensive statistical tabs, and an interactive executive presentation board.

---

## 📂 Workbook Architecture

The project workbook is systematically organized across 7 core specialized sheets:

| Sheet Name | Description & Functionality |
| :--- | :--- |
| 📁 **`Data`** | Raw, unformatted source sales dataset containing order details and transaction logs. |
| 🧹 **`Clean_Dataset`** | Formatted and pre-processed dataset with standardized data types, clean headers, and error handling. |
| 📈 **`Sales_Analysis`** | In-depth breakdown covering Regional Performance, State-wise breakdown, Customer Segments, and Shipping Mode Metrics. |
| 📦 **`Product_Analysis`** | Detailed category, sub-category, Top 10 products analysis, and Discount distribution metrics. |
| 📊 **`Pivot_Analysis`** | Aggregated Pivot Tables serving as financial engines powering all charts and KPI cards. |
| 🖥️ **`Dashboard`** | Main interactive visual canvas featuring KPI cards, charts, dynamic Slicers, and a Timeline slicer. |
| 📋 **`Summary`** | High-level Executive Summary, key insights, and strategic business recommendations. |

---

## 🛠️ Step-by-Step Implementation Workflow

Raw Data ➔ Data Cleaning ➔ Analysis Sheets ➔ Pivot Tables ➔ Interactive Dashboard ➔ Executive Summary

### 1. Data Cleaning & Standardization (`Clean_Dataset`)
* Handled missing values, standardized text formatting, and removed duplicated entries.
* Formatted currency fields (`Sales`, `Profit`) and date columns (`Order Date`, `Ship Date`).
* Calculated custom fields like shipping duration (`Ship Date - Order Date`).

### 2. Multi-Dimensional Data Analysis (`Sales_Analysis` & `Product_Analysis`)
* **Sales & Profit Metrics:** Evaluated overall revenue ($2.29M) and net margins (12.5%).
* **Regional & State Breakdown:** Identified top-performing zones (West & East driving 67% share).
* **Category & Discount Insights:** Analyzed product profitability vs. margin erosion caused by heavy discounts in Furniture.

### 3. Pivot Engine Setup (`Pivot_Analysis`)
* Created structured Pivot Tables for Category Performance, Regional Distribution, Monthly Sales Trends, Shipping Mode analysis, and Top 10 Products.
* Established dynamic calculated fields for Average Order Value (AOV) and Net Margin %.

### 4. Interactive Dashboard Design (`Dashboard`)
* **KPI Cards:** Top-level visual indicators for Total Sales ($2.29M), Profit ($286.4K), Profit Margin % (12.5%), Total Orders (9,994), and AOV ($229.86).
* **Dynamic Charts:**
  * 📊 **Sales by Category:** Bar chart comparing revenue vs. profit across categories.
  * 📈 **Monthly Sales Trend:** Line chart showcasing seasonality spikes (Q4 Peak).
  * 🍩 **Sales by Region:** Donut chart highlighting regional market share.
  * 📉 **Discount Range Distribution:** Histogram mapping discount frequencies.
* **Interactivity:** Integrated synchronized **Slicers** (*Region*, *Ship Mode*, *Segment*) and an **Order Date Timeline** using Report Connections.

---

## 📊 Key Business Insights & Executive Summary

* 💰 **Total Sales:** $2,297,200.86
* 💵 **Total Profit:** $286,397.02
* 📈 **Profit Margin:** 12.5%
* 📦 **Orders Processed:** 9,994
* 🛒 **Avg Order Value:** $229.86

### 💡 Core Observations
1. **Category Performance:** **Technology** is the primary profit generator ($145.4K profit), whereas **Furniture** shows high sales ($742K) but compressed net profit ($18.4K) due to freight costs and steep discounts.
2. **Regional Dominance:** The **West** (38%) and **East** (29%) regions drive **67%** of total business revenue.
3. **Q4 Seasonality:** Demand surges drastically in Q4, peaking in **November ($352K)** and **December ($325K)**.
4. **Fulfillment:** **Standard Class** handles 59% of total shipping volumes (5,968 orders).

---
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=217346&height=120&section=header&text=DASHBOARD&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%" />
</p>

<img width="717" height="397" alt="image" src="https://github.com/user-attachments/assets/f1e91ad6-35c6-4af8-b9c7-beeb1ba124c2" />


## 🎯 Strategic Recommendations

* 🔹 **Furniture Margin Optimization:** Restructure pricing and cap maximum allowable discounts to protect margins.
* 🔹 **Q4 Inventory Prep:** Scale supply chain capacity by late Q3 to prevent stockouts during peak holiday demand.
* 🔹 **Regional Expansion:** Develop targeted marketing and logistical support in Central and South territories.

---

## 💻 Tech Stack & Tools Used

* **Spreadsheet Tool:** Microsoft Excel 365
* **Analytics Techniques:** Data Cleaning, Pivot Tables, Dynamic Formulas, Report Connections
* **Visualizations:** Donut Charts, Clustered Columns, Histograms, Line Charts, Slicers & Timelines
---
