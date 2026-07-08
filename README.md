# 📊 Retail Sales Analysis — Excel Portfolio Project

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot_Tables-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

> **End-to-end sales data analysis on a 9,994-row US retail dataset — answering 17 business questions using Excel formulas, Pivot Tables, Pivot Charts, and Conditional Formatting.**

---

## 📌 Project Overview

This project performs a comprehensive analysis of a US retail Superstore dataset to uncover sales trends, regional performance, customer behavior, and revenue drivers. Using advanced Excel techniques, the analysis answers 17 structured business questions across three categories: Sales Trends, Regional Insights, and Key Revenue Drivers.

---

## 🗄️ Dataset

| Field | Details |
|---|---|
| Records | 9,994 orders |
| Columns | 18 (Order ID, Customer, Segment, Region, Category, Sub-Category, Product, Sales, Profit, Ship Mode, etc.) |
| Time Period | 2015 – 2018 |
| Geography | United States (4 Regions: East, West, Central, South) |
| Categories | Furniture · Office Supplies · Technology |
| Segments | Consumer · Corporate · Home Office |

---

## 🔍 Business Questions Answered

### 📈 Understanding Sales Trends

| # | Question | Technique Used |
|---|---|---|
| 1 | Total profit per category | SUMIF / Pivot Table |
| 2 | Total profit per sub-category | SUMIF / Pivot Table |
| 3 | Total sales per product | SUMIF |
| 4 | City with highest sales | MAXIFS / Pivot Table |
| 5 | Most common shipping mode | COUNTIF |
| 6 | Product with highest sales per unit | Calculated Column (Sales ÷ Quantity) |
| 7 | Count of unique customers | COUNTUNIQUE / SUMPRODUCT |
| 8a | Pivot table: total sales by customer | Pivot Table |
| 8b | Top 3 customers by total purchases | LARGE / Pivot Table sort |
| 9a | Sales distribution by Segment | Pivot Chart |
| 9b | Slicers by Region and Ship Mode | Slicer on Pivot Chart |
| 10 | % of customers per segment | COUNTIF ÷ Total |
| 11 | Category contribution to overall sales | SUMIF ÷ Total Sales |

### 🗺️ Regional Insights

| # | Question | Technique Used |
|---|---|---|
| 12a | Region for a given state + total sales per state | FILTER function |
| 12b | States with sales > $10,000 | COUNTIF |
| 13 | Total sales by Region and Category | Pivot Table (2D) |
| 14 | Average sales per order by Region | AVERAGEIF |
| 15 | % of total sales per region | SUMIF ÷ Total |

### 💰 Key Revenue Drivers

| # | Question | Technique Used |
|---|---|---|
| 16a | Total sales per Order ID with conditional formatting | SUMIF + Conditional Formatting |
| 16b | Top 5 Order IDs with category-wise breakdown | INDEX MATCH |
| 17 | Orders by sales range buckets (<$100 to >$1,000) | COUNTIFS (multiple ranges) |

---

## 🛠️ Excel Skills Demonstrated

- **Pivot Tables** — multi-dimensional aggregation, sorting, filtering
- **Pivot Charts** — visual sales distribution with interactive slicers
- **Advanced Formulas** — SUMIF, COUNTIF, AVERAGEIF, MAXIFS, COUNTIFS, FILTER, INDEX MATCH, LARGE
- **Calculated Columns** — custom metrics like Sales Per Unit
- **Conditional Formatting** — highlighting above-average order values
- **Slicers** — interactive filtering by Region and Ship Mode
- **Data Validation & Cleaning** — consistent formats across 9,994 rows

---

## 💡 Key Findings

| Insight | Finding |
|---|---|
| Most profitable category | Technology leads in profit contribution |
| Top shipping mode | Standard Class is the most common (60%+ of orders) |
| Highest sales city | New York City records the highest total sales |
| Top customer segment | Consumer segment accounts for ~51% of customers |
| Regional leader | West region contributes the highest % of total sales |
| Revenue concentration | Top 5 Order IDs contribute disproportionately to total sales |

---

## 📁 File Structure

```
📁 excel-sales-analysis/
├── Excel_Portfolio_Project_File.xlsx    # Full workbook with all analysis
├── report/
│   └── Excel_Portfolio_Project.pdf      # Documented question-answer report
└── README.md
```

---

## 🚀 How to Use

1. Download `Excel_Portfolio_Project_File.xlsx`
2. Enable editing if prompted
3. Navigate sheets to explore Pivot Tables, Charts, and Formula outputs
4. Use slicers on the Pivot Chart sheet to filter by Region / Ship Mode

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdul-rasheed-551814244)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sheikhabdulrasheed2003@gmail.com)
