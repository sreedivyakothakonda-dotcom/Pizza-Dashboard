# 🍕 Pizza Sales Dashboard

An interactive Power BI dashboard analyzing pizza sales performance across categories, sizes, and time periods.

![Pizza Dashboard]([pizza_dashboard.png](https://github.com/sreedivyakothakonda-dotcom/Pizza-Dashboard/blob/main/Pizza%20Dashboard.png))

---

## 📊 Overview

This dashboard provides a comprehensive view of pizza sales data, enabling quick insights into revenue trends, top-selling pizza types, and sales distribution across categories and sizes.

---

## 📌 Key Metrics

| Metric | Value |
|---|---|
| **Total Revenue** | $899.65K |

---

## 📈 Visuals Included

| Visual | Description |
|---|---|
| **Average Price by Month & Category** | Line chart showing monthly price trends for Chicken, Classic, Supreme, and Veggie |
| **Sum of Total Amount by Pizza Type** | Horizontal bar chart ranking pizza types by revenue (Thai Chicken leads) |
| **Sum of Total Amount by Month** | Line chart tracking monthly revenue fluctuations |
| **Average Price by Category & Size** | Grouped bar chart comparing prices across L, M, S, XL, XXL sizes |
| **Sum of Quantity by Category** | Pie chart showing sales share — Classic (30%), Chicken (24.18%), Supreme (25%), Veggie (22.29%) |
| **Sum of Quantity by Category & Size** | Stacked bar chart for quantity sold per size |
| **Sum of Total Amount by Size** | Scatter chart comparing revenue contribution by size |
| **Category Filter** | Slicer to filter all visuals by Chicken, Classic, Supreme, or Veggie |

---

## 🗂️ Dataset

- **Source:** Pizza sales transactional data
- **Fields used:** `pizza_type_id`, `category`, `size`, `total_amount`, `quantity`, `order_date`

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard creation and data modeling
- **Power Query** — Data transformation and cleaning
- **DAX** — Calculated measures and KPIs

---

## 🚀 How to Use

1. Clone or download this repository
2. Open the `.pbix` file in Power BI Desktop
3. Use the **Category slicer** (top right) to filter by pizza category
4. Hover over charts for detailed tooltips

---

## 💡 Key Insights

- **Thai Chicken** generates the highest revenue among all pizza types
- **Classic** category accounts for 30% of total quantity sold
- Revenue peaks mid-year with a dip in late months
- **XL and XXL** sizes contribute significantly to total revenue despite lower unit counts

---

## 📁 Files

```
📦 pizza-sales-dashboard
 ┣ 📊 Pizza_Dashboard.pbix
 ┣ 📄 pizza_sales_data.csv
 ┗ 📸 pizza_dashboard.png
```

