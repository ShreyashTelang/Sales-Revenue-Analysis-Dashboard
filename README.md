# Sales & Revenue Analysis Dashboard

An interactive **Sales & Revenue Analysis Dashboard** built using **Microsoft Power BI** to analyze sales performance, customer behavior, product trends, and regional sales distribution. This dashboard transforms raw sales data into meaningful business insights through interactive visualizations and DAX-powered KPIs.

---

## Project Overview

The objective of this project is to create a professional Business Intelligence dashboard that helps businesses monitor their sales performance and make data-driven decisions.

The dashboard includes:

- 📈 Sales Trend Analysis
- 📊 Sales by Category & Sub-Category
- 🌍 Regional Sales Performance
- 🛒 Top Selling Products
- 👥 Customer Segment Analysis
- 🎯 Interactive Filters
- 📌 KPI Cards

---

## 🚀 Dashboard Preview

> Add your dashboard screenshot inside the **Images** folder and update the path below.

![Dashboard](Sales and Revenue Analysis Dashboard/Images/dashboard.png)

---

# ✨ Features

### 📌 KPI Cards

- 💰 Total Sales
- 📦 Total Orders
- 👥 Total Customers
- 🛍️ Total Products
- 💵 Average Order Value

---

### 📊 Visualizations

- Monthly Sales Trend
- Sales by Category
- Sales by Sub-Category
- Sales by Region
- Sales by Customer Segment
- Top Selling Products

---

### 🎛️ Interactive Filters

- Year
- Region
- Category
- Segment

---

# 🛠️ Tech Stack

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset
- Data Modeling
- Data Visualization

---

# 📂 Dataset

The dashboard is built using the **Superstore Sales Dataset**.

The dataset contains:

- Order Details
- Customer Details
- Product Information
- Sales
- Category
- Sub-Category
- Region
- Segment
- Shipping Information

---

# 📐 Data Cleaning

The dataset was cleaned using **Power Query**.

Cleaning steps performed:

- Removed duplicate records
- Checked for missing values
- Corrected data types
- Created Month, Year and Quarter columns
- Prepared data for reporting

---

# 📊 DAX Measures

### Total Sales

```DAX
Total Sales =
SUM(train[Sales])
```

### Total Orders

```DAX
Total Orders =
DISTINCTCOUNT(train[Order ID])
```

### Total Customers

```DAX
Customers =
DISTINCTCOUNT(train[Customer ID])
```

### Total Products

```DAX
Products =
DISTINCTCOUNT(train[Product ID])
```

### Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Sales], [Total Orders])
```

---

# 📈 Dashboard Insights

The dashboard helps answer business questions such as:

- Which product category generates the highest sales?
- Which customer segment contributes the most revenue?
- Which region performs the best?
- What are the highest selling products?
- How do monthly sales change over time?
- Which sub-categories generate the most sales?

---

# 📌 Business Insights

Some key observations from the dashboard:

- ✅ Technology is the highest revenue-generating category.
- ✅ Consumer segment contributes the largest share of sales.
- ✅ West region records the highest overall sales.
- ✅ Phones are the best-selling sub-category.
- ✅ A small number of products generate a significant percentage of total revenue.
- ✅ Monthly sales fluctuate throughout the year, indicating seasonal demand.

---

# 📁 Project Structure

```
Sales-Revenue-Analysis-Dashboard/
│
├── Dataset/
│   └── train.csv
│
├── Dashboard/
│   └── Sales Revenue Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
├── README.md
│
└── LICENSE
```

---

# 🎯 Skills Demonstrated

- Power BI Dashboard Development
- Business Intelligence
- Data Visualization
- Power Query
- Data Cleaning
- Data Modeling
- DAX
- KPI Development
- Interactive Dashboard Design
- Business Analytics

---

# 📊 Dashboard Components

| Visualization | Purpose |
|---------------|---------|
| KPI Cards | Display business metrics |
| Line Chart | Monthly Sales Trend |
| Bar Chart | Sales by Category |
| Bar Chart | Sales by Sub-Category |
| Pie Chart | Sales by Segment |
| Column Chart | Sales by Region |
| Bar Chart | Top Selling Products |
| Slicers | Dynamic Filtering |

---

# 🔮 Future Improvements

- Add Profit Analysis
- Add Quantity Sold Analysis
- Customer Retention Dashboard
- Drill-through Reports
- Drill-down Hierarchies
- Forecast Future Sales
- Publish Dashboard to Power BI Service

---

# 👨‍💻 Author

**Shreyash Telang**

Computer Engineering Student | Aspiring Data Analyst

## ⭐ If you found this project helpful, don't forget to give it a star!
