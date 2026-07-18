# 🛒 SuperVision — Retail Sales Intelligence Dashboard

An end-to-end **Power BI project** built on a cleaned Superstore retail dataset —
covering data preparation in Excel through to an interactive dashboard that answers
real business questions about sales performance, shipping efficiency, customer
segmentation, and product trends across **4 years**, **49 states**, and
**793 customers**.

---

## 📁 Repository Structure

```
📦 SuperVision-Dashboard
 ┣ 📊 dashboard_level1_finished.pbix     ← Power BI report (visuals + DAX measures)
 ┣ 📂 Superstore_Sales_cleaned.xlsx      ← Cleaned source dataset
 ┣ 📁 screenshots/
 ┃ ┗ 🖼️ dashboard.png                    ← Add your screenshot here
 ┗ 📄 README.md
```

---

## 📦 Dataset Overview

| Property | Value |
|---|---|
| **File** | `Superstore_Sales_cleaned.xlsx` |
| **Rows** | 9,799 orders |
| **Columns** | 18 fields |
| **Period** | January 2015 — December 2018 (4 years) |
| **Geography** | 49 US States across 4 Regions |
| **Customers** | 793 unique customers |
| **Total Revenue** | $2,261,255 |

### Columns

| Column | Description |
|---|---|
| `Order ID` | Unique order identifier |
| `Order Date` | Date the order was placed |
| `Ship Date` | Date the order was shipped |
| `Ship Mode` | Shipping method (Standard, Second Class, First Class, Same Day) |
| `Customer ID` | Unique customer identifier |
| `Customer Name` | Full name of the customer |
| `Segment` | Customer type — Consumer, Corporate, Home Office |
| `City` | Customer city |
| `State` | Customer state (49 US states) |
| `Postal Code` | Customer postal code |
| `Region` | Geographic region — East, West, Central, South |
| `Product ID` | Unique product identifier |
| `Category` | Product category — Furniture, Office Supplies, Technology |
| `Sub-Category` | 17 sub-categories (Chairs, Phones, Binders, etc.) |
| `Product Name` | Full product name |
| `Sales` | Revenue from the order |
| `Monthly Trends` | Calculated monthly grouping field |
| `Shipping Days` | Number of days between order and shipment |

---

## 📊 Dashboard — `DB` Page (1280 × 720)

### KPI Cards

| Metric | Description |
|---|---|
| 💰 **Total Sales** | Sum of all revenue across 4 years |
| 📦 **Total Orders** | Count of all orders placed |
| 🛍️ **Total Products** | Number of distinct products sold |
| 🚚 **AVG Shipping Days** | Average days from order to shipment |

---

### Visuals

**📈 Monthly Trend** *(Line Chart)*
Plots **Total Sales** month by month across the full 2015–2018 period — reveals seasonal peaks, holiday spikes, and year-on-year growth patterns.

**📦 Ship Mode by Category** *(Clustered Column Chart)*
Compares **Total Sales** per **Shipping Mode** (Standard Class · Second Class · First Class · Same Day) broken down by **Category** (Furniture · Office Supplies · Technology). Shows which categories rely on faster/slower shipping.

**🍩 Sales by Segment** *(Donut Chart)*
Visualizes revenue share across **Consumer**, **Corporate**, and **Home Office** segments — instantly showing which customer type is the most valuable.

**📋 Category × Sub-Category Matrix** *(Pivot Table)*
Cross-tabulates all **17 Sub-Categories** under their **3 Categories** against **Total Sales** and **Total Orders** — pinpoints the best and worst performing product lines at a glance.

**🔽 Dynamic Slicers**
- **Region** — filter all visuals by East / West / Central / South
- **Sub-Category** — drill into any of the 17 product sub-categories

---

## 💡 Business Questions This Dashboard Answers

- Which months and seasons generate the highest sales?
- Which product category drives the most revenue?
- Which shipping mode is preferred for each product type?
- Which customer segment (Consumer / Corporate / Home Office) is most valuable?
- Which sub-categories are underperforming vs. top sellers?
- How does shipping speed vary across the dataset?
- How do sales differ across the 4 US regions?

---

## 🛠️ Tools & Skills Used

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design, DAX measures, visual layout |
| **DAX** | Calculated measures: Total Sales, Total Orders, Total Products, AVG Shipping Days |
| **Power Query** | Data transformation and loading |
| **Excel** | Data cleaning — removing duplicates, fixing dates, adding derived columns |
| **Data Visualization** | KPI cards, line chart, clustered column, donut, pivot table |

---

## ⚙️ Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) *(free)* — to open, explore, and edit the `.pbix` file
- Microsoft Excel or any spreadsheet viewer — to explore the raw data
- No external data connection required — the dataset is embedded in the `.pbix` and available as a standalone `.xlsx`

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open `dashboard_level1_finished.pbix` in **Power BI Desktop**
3. Navigate to the `DB` page
4. Use the **Region** and **Sub-Category** slicers to filter all visuals dynamically
5. To explore the raw data, open `Superstore_Sales_cleaned.xlsx` in Excel
6. To publish online → use **Power BI Service** *(requires a Microsoft/work account)*

---

## 🧠 Skills Demonstrated

`Power BI` · `DAX` · `Power Query` · `Excel Data Cleaning` · `KPI Design` ·
`Data Visualization` · `Retail Analytics` · `Business Intelligence` ·
`Data Storytelling` · `Exploratory Data Analysis (EDA)`

---

## 📌 About This Project

This is a **Level 1** retail analytics dashboard, focused on clean visual
storytelling with core BI fundamentals. It is part of an ongoing data analytics
portfolio built during my studies in Mathematics & Computer Science at
**Faculty of Science, Helwan University**.

Future versions could include:
- 🗺️ Map visual by State/City
- 📉 Profit margin and discount analysis
- 📆 Year-over-Year (YoY) comparison measures
- 🔍 Customer drill-through pages

---

## 📄 License

Free to use as a learning reference or portfolio template. Attribution appreciated.
