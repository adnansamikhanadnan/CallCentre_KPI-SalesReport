# Business Intelligence & Power BI Dashboard Portfolio

## 📊 Project Overview

This repository showcases **business intelligence and data analytics projects built with Microsoft Power BI**, SQL, and structured business requirements.

The projects focus on converting raw business data into interactive dashboards that help managers and sales/customer-service teams monitor KPIs, identify trends, compare performance, and make data-driven decisions.

### Projects Included

1. **AdventureWorks Internet Sales Dashboard**
   - Sales performance overview
   - Customer and product analysis
   - Sales vs. budget tracking
   - Monthly trend analysis
   - Customer-city analysis
   - Interactive filtering by year, month, city, category, and sub-category

2. **Call Centre Performance Dashboard**
   - Call volume and answer-rate analysis
   - Agent performance tracking
   - Resolved vs. unresolved calls
   - Customer satisfaction analysis
   - Average speed of answer
   - Call-topic distribution

---

# 1. AdventureWorks Sales Report

## 🎯 Business Objective

The sales dashboard was designed to give sales managers and representatives a clear overview of internet sales, customers, products, and performance against budget.

The business requirements specify dashboards for understanding the best-performing customers and products, filtering customer/product details, and comparing actual sales against budget over time.

## 👥 Target Users

- Sales Managers
- Sales Representatives
- Business/Reporting Teams

## 🔑 Key Business Questions

- What is the total internet sales?
- Are actual sales above or below budget?
- Which customers generate the most sales?
- Which products perform best?
- How does sales performance change month by month?
- Which customer cities contribute most to sales?
- How can sales representatives identify customers for follow-up and upselling?

## 📈 Dashboard Features

### Sales Overview

The dashboard provides:

- Total Sales
- Budget
- Profit/Loss
- Sales by Category
- Sales vs. Budget by Month
- Top 5 Customers
- Top 5 Products
- Sales by Customer City

The provided dashboard reports **29,358,677 in sales**, **21,100,000 budget**, and **8,258,677 profit/loss**.

### Customer Details

The customer analysis page provides:

- Top 10 customers by sales
- Monthly sales by customer
- Customer-city visualization
- Year and month filters
- Category and sub-category filters
- Customer-level performance analysis

The dashboard supports filtering across years **2018–2021** and individual months.

## 🛠️ Technology Stack

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **SQL**
- **AdventureWorks dataset**
- Data modeling / dimensional modeling
- Interactive data visualization

## 🗂️ Data Model / SQL Assets

The repository includes SQL/data assets for:

- `DIM_Customer`
- `DIM_Date`
- `DIM_Product`
- `FACT_InternetSales`

These components support structured analysis of customers, dates, products, and internet sales transactions.

---

# 2. Call Centre Performance Dashboard

## 🎯 Business Objective

This dashboard analyzes call-centre operations and agent performance to help identify service-level trends, workload distribution, resolution performance, response speed, and customer satisfaction.

## 📊 Key KPIs

The dashboard reports:

| KPI | Value |
|---|---:|
| Total Calls | 5,000 |
| Answered Calls | 4,054 |
| Unanswered Calls | 946 |
| Average Speed of Answer | 67.52 seconds |
| Average Satisfaction Rating | 3.40 |

## 📌 Dashboard Analysis

The report includes:

- Total Calls by Topic
- Total Answered Calls by Satisfaction Rating
- Resolved vs. Unresolved Calls by Agent
- Average Speed of Answer by Agent
- Detailed Agent Performance table

### Call Topics

The dashboard analyzes:

- Streaming
- Technical Support
- Payment related
- Admin Support
- Contract related

### Agent Performance

Agent-level metrics include:

- Total Calls
- Answered Calls
- Unanswered Calls
- Resolved Calls
- Unresolved Calls
- Satisfaction Rating
- Average Speed of Answer

---

# 💡 Business Impact

These dashboards transform operational and sales data into actionable business insights.

### Sales Team Benefits

- Faster identification of high-value customers
- Better product performance monitoring
- Easier sales follow-up and upselling opportunities
- Budget vs. actual performance tracking
- Monthly and geographic sales analysis

### Call Centre Benefits

- Visibility into agent workload
- Identification of unresolved calls
- Monitoring of response speed
- Customer satisfaction tracking
- Topic-level demand analysis

---

# 🧠 Skills Demonstrated

This project demonstrates practical skills in:

- Business Intelligence
- Data Analytics
- Microsoft Power BI
- Dashboard Development
- Data Visualization
- KPI Design
- DAX
- Power Query
- SQL
- Data Modeling
- Customer Analytics
- Sales Analytics
- Performance Analysis
- Business Requirement Analysis
- User Story Analysis
- Data-driven Decision Making

---

# 📁 Repository Structure

```text
Business-Intelligence-PowerBI/
│
├── README.md
│
├── AdventureWorks-Sales/
│   ├── SalesReport_AdventureWorks.pbix
│   ├── SalesReport_AdventureWorks.pdf
│   ├── DIM_Customer.sql
│   ├── DIM_Date.sql
│   ├── DIM_Product.sql
│   └── FACT_InternetSales
│
├── Call-Centre-Analytics/
│   ├── KPI_CallCentreReport.pbix
│   ├── KPI_CallCentreReport.pdf
│   └── 01 Call-Center-Dataset(PwC).xlsx
│
└── Business-Requirements/
    ├── Business Demand & User Stories.md
    └── Business Request
```

---

# 🚀 How to Use

### AdventureWorks Sales Dashboard

1. Open `SalesReport_AdventureWorks.pbix` using Microsoft Power BI Desktop.
2. Review the data model and relationships.
3. Use the Year, Month, Customer City, Category, and Sub-Category filters.
4. Explore sales, budget, customer, product, and geographic insights.

### Call Centre Dashboard

1. Open `KPI_CallCentreReport.pbix` in Power BI Desktop.
2. Use the Month filter to change the reporting period.
3. Review call volume, agent performance, resolution, response speed, and satisfaction metrics.

> **Note:** Power BI Desktop is required to open and interact with `.pbix` files.

---

# 📌 Business Requirements

The sales reporting requirements call for a Power BI dashboard that updates data daily, supports customer-level and product-level filtering, and compares actual sales against budget using KPIs and visualizations.

The supplied business requirements identify **Steven, Sales Manager** as the reporter and specify Power BI and a CRM system as necessary systems.

---

# 📷 Dashboard Highlights

### AdventureWorks Sales Dashboard

The overview page combines KPI cards, category analysis, customer/product rankings, monthly sales-vs-budget trends, and a customer-city map.

### Customer Details Dashboard

The customer page provides customer-level monthly sales, top-10 customer ranking, geographic analysis, and detailed customer totals.

### Call Centre Performance Dashboard

The call-centre page combines operational KPIs, topic distribution, satisfaction ratings, agent resolution performance, response speed, and an agent-level performance table.

---

# 💼 Recruiter-Friendly Summary

**Business Intelligence & Power BI Analytics Portfolio**

Developed interactive Power BI dashboards for sales and customer-service analytics using structured business requirements and real-world datasets. Built KPI-driven reports covering sales performance, budget comparison, customer and product analysis, call-centre operations, agent performance, resolution rates, response time, and customer satisfaction. Used SQL-based dimensional data assets, Power Query, DAX, data modeling, and interactive visualizations to transform business data into actionable insights.

---

# 🔖 Suggested GitHub Topics

```text
power-bi
business-intelligence
data-analytics
data-visualization
sql
dax
power-query
sales-analytics
customer-analytics
call-center-analytics
dashboard
adventureworks
business-analysis
kpi-dashboard
```

---

## 👨‍💻 Author

**Adnan Sami**

B.Tech — Artificial Intelligence & Data Science

Interested in **AI, Data Analytics, Business Intelligence, Machine Learning, and Data-driven Solutions**.
