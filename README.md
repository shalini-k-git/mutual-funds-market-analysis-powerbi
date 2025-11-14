# 📊 Mutual Funds Market Analysis and Performance Insights (2019–2025)

> **Tools:** Power BI | Excel | DAX | Power Query | Data Modeling  
> **Domain:** Finance | Investment Analytics

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Domain-Finance](https://img.shields.io/badge/Domain-Finance-blue)
![Language-DAX](https://img.shields.io/badge/Language-DAX-orange)


## 🧩 Project Overview
This project analyzes the **Indian Mutual Funds Market (2019–2025)**, focusing on fund mobilization, redemptions, net inflows, and **Assets Under Management (AUM)** across various scheme types and categories.  
Using **Power BI**, the data was cleaned, modeled, and visualized to uncover key investment trends and fund performance insights over time.

---

## 🎯 Project Objectives

### 1. Analyze Market Trends
Study overall trends in the Indian Mutual Funds industry (2019–2024), focusing on fund mobilization, redemptions, inflows, and outflows across scheme types.

### 2. Evaluate Fund Performance
Assess the performance and growth of mutual fund categories — *Equity, Debt, Hybrid, and Solution-Oriented Schemes* — based on Net AUM and Net Inflows.

### 3. Understand Investor Behavior
Identify how investor preferences shifted between *Open-Ended, Close-Ended, and Interval schemes* over time.

### 4. Compare Scheme Categories
Compare and visualize contributions of different scheme categories and their performance metrics using **interactive Power BI dashboards**.

---

## 📂 Data Sources

**Sources & Timeline:**
- 📅 *Indian Data Portal (2019–2024)*  
- 📈 *Association of Mutual Funds in India (AMFI) (2024–2025)*  

**Domain:** Finance

---

## ❓ Problem Statement
- Analyze mutual fund performance across different scheme types and categories to identify top-performing funds.  
- Study investor behavior through inflow and outflow trends to understand investment patterns over time.  
- Evaluate fund mobilization, redemption, and AUM data to assess market growth and stability.  
- Compare open-ended, close-ended, and interval schemes for strategic investment insights.  
- Identify which categories attract the most investors and funds.  
- Examine monthly/yearly AUM trends for forecasting potential and investor confidence.  
- Analyze the relationship between investor count (folios) and asset growth.

---

## 🧾 Attribute Details

| **Attribute Name** | **Data Type** | **Description** |
|--------------------|---------------|-----------------|
| ID | Integer | Unique identifier for each record |
| DATE | Date | Reporting date (monthly) |
| Scheme Name | Text | Name of the mutual fund scheme |
| Scheme Type | Category | Open Ended / Close Ended / Interval |
| Scheme Category | Category | Equity, Debt, Hybrid, Solution Oriented, Others |
| No. of Schemes | Whole Number | Total schemes under a category |
| No. of Folios | Whole Number | Total investor accounts (folios) |
| Funds Mobilized (₹ Crore) | Currency | Total inflows during the period |
| Repurchase/Redemption (₹ Crore) | Currency | Total outflows during the period |
| Net Inflow (+/-) (₹ Crore) | Currency | Net money movement (Inflow/Outflow) |
| Net AUM (₹ Crore) | Currency | Total market value of managed assets |
| Average AUM (₹ Crore) | Currency | Average AUM during reporting period |
| No. of Segregated Portfolios | Whole Number | Segregated portfolios within the fund |
| AUM in Segregated Portfolio (₹ Crore) | Currency | Assets managed under segregated portfolios |
| Inflow/Outflow Status | Text | Indicates positive or negative net investment |

---

## 🛠️ Tools and Technologies

### 🧮 Microsoft Excel
- Used **Power Query** for ETL operations (data collection, cleaning, transformation).  
- Removed duplicates, consolidated data, and standardized formats before Power BI import.  
- Automated formatting tasks using **Excel Macros**.

### 📈 Microsoft Power BI
- Primary tool for data modeling, visualization, and dashboard creation.  
- Used **DAX (Data Analysis Expressions)** to build custom measures and KPIs.  
- Performed advanced data cleaning and integration in **Power Query Editor**.

---

## 🧹 Data Preprocessing Steps

1. **Data Collection:**  
   Gathered data (2019–2024) from Indian Data Portal and (2024–2025) from AMFI.  

2. **Data Consolidation:**  
   Combined monthly Excel sheets, removed subtotals and redundant rows.  

3. **Automation (Macros):**  
   Automated repetitive formatting tasks like column alignment and styling.  

4. **Data Cleaning (Power Query):**  
   Filled missing values, standardized text formats, corrected data types.  

5. **Data Transformation:**  
   Added calculated flag columns and harmonized field names.  

6. **Data Integration:**  
   Appended cleaned datasets into a unified dataset (2019–2025) for visualization.

---

## 🧩 Data Modeling & DAX (Power BI)

### 🗂️ Data Modeling
- Created a **Calendar Table** linked to the main dataset via the Date field for time-based analysis.

### 🧮 DAX Components

#### 📊 Calculated Columns
- Inflow/Outflow Status  
- Activity Flag

#### 📏 Measures
- Total Funds Mobilized  
- Total Withdrawals (Redemptions)  
- Total Net Inflow / Outflow  
- Total Net AUM  
- Inflow Percentage (%)  
- Average Investment per Scheme  

#### ⚙️ Parameters
- Funds Parameter (for fund movement trends)  
- Investors Parameter (for participation comparison)

---

## 📉 Analysis & Visualizations

Developed **interactive Power BI dashboards** addressing all problem statements using:
- Bar Charts  
- Line Graphs  
- Donut Charts  
- Tree Maps  
- KPI Cards  

**Highlights:**
- Fund Performance – Compared top-performing schemes.  
- Investor Behaviour – Visualized inflow/outflow patterns.  
- Market Growth – KPIs for total inflows, redemptions, and AUM stability.  
- Scheme Comparison – Compared open-ended vs. close-ended vs. interval schemes.  
- Investor Distribution – Funnel charts and tree maps for category analysis.  
- AUM Trends – Area charts for growth over time.  
- Investor Engagement – Donut charts for folio contributions.

 ![Dashboard Preview](dashboards/dashboard_screenshots/Market_Analysis_1.png)

---

## 📈 Performance Insights

- 🟢 **Open-Ended Schemes** were the most preferred investment type.  
- 📅 **2024** recorded peak values in both AUM and total inflows.  
- 💹 **Other ETFs** category received the highest inflows.  
- 💰 **Debt & Income Schemes** showed strong, low-risk inflow trends.  
- 💧 **Liquid Fund Schemes** had the maximum investor participation.  
- 📈 Year-over-year growth in folios indicates strong market trust.  
- 🔻 **Money Market Funds** recorded high outflows (possible profit booking).

---

## 🧠 Conclusion

The integration of **Excel and Power BI** enabled a comprehensive analysis of the Indian Mutual Funds Market (2019–2025).  
Key findings include:
- Open-Ended Schemes received the highest funding.  
- 2024 marked peak AUM and inflows, showing strong investor confidence.  
- Liquid Funds attracted the most investors.  
- Money Market Funds showed high outflows due to reallocation strategies.  

This project transformed complex financial data into **clear, actionable insights** on mutual fund performance and investor behavior.

---

## 👩‍💻 Author

**Shalini K**  
*Data Analyst | Power BI Developer*  

- 🌐 GitHub: [Shalini_K](https://github.com/shalini-k-git)  
- 💼 LinkedIn: [Shalini K](https://www.linkedin.com/in/shalini-k10/)  
- 📧 Email: shalinikandaswamy10@gmail.com

If you found this project useful or have feedback, feel free to reach out!  

---

## 📚 Tags
`#PowerBI` `#DataAnalysis` `#MutualFunds` `#FinanceAnalytics`  
`#DAX` `#DataVisualization` `#ExcelPowerQuery`

