 🍕 Pizza Sales Performance & Insights Analysis

An end-to-end data analysis project exploring pizza sales performance using SQL for business queries, Power BI for interactive dashboards, and comprehensive documentation for stakeholders.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔗 Quick Project Links & Deliverables

Click any of the links below to view or download the project files directly:

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Project Overview
This project analyzes key sales metrics, ordering patterns, and product performance for a pizza restaurant chain. It bridges raw data with actionable business intelligence to answer key business questions regarding total revenue, order volume, and top/bottom selling items.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Repository Structure

```text
├── BRD/
│   └── Pizza_Sales_BRD.pdf
├── Dashboards/
│   └── Pizza_Sales_Dashboard.pbix
├── SQL/
│   └── pizza_sales_queries.sql
├── Presentations/
│   ├── Pizza_Sales_Presentation.pdf
│   ├── Pizza_Sales_Presentation.pptx
│
└── README.md

```

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📐 Data Architecture & Model

The database is modeled using a **Star Schema** centered around transactional order details connected to dimension tables:

* **Fact Table**: `order_details` (line items, quantities, and sales metrics)
* **Dimension Tables**:
* `orders` (order date, time, day name, hour)
* `pizzas` (size, price, mapping)
* `pizza_types` (name, category, ingredients)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Key Insights & Metrics Addressed

* **Total Revenue**: Comprehensive aggregation of sales across all pizza categories and sizes.
* **Total Orders**: Distinct order tracking (~21,350 unique orders across ~48,620 total items ordered).
* **Average Order Value (AOV)**: Revenue per transaction analysis.
* **Sales by Category & Size**: Identifying high-volume and high-revenue menu items.
* **Peak Ordering Hours & Days**: Identifying operational surge times to optimize kitchen staffing.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools & Technologies Used

* **SQL**: Data extraction, aggregation, CTEs, Joins, and Window Functions.
* **Power BI**: Data modeling (Star Schema), DAX measures, and visual dashboard design.
* **Canva / PowerPoint**: Custom presentation deck and asset formatting.

---

## 👨‍💻 Connect with Me

* **LinkedIn**: [Krishna's LinkedIn Profile](https://www.linkedin.com/in/krishna-das-07b3b9244/)
* **GitHub**: [Krishna's GitHub Profile](https://github.com/Krishna17201)
* **SQL Queries pdf**:[Krishna's SQL Queries PDF](https://drive.google.com/file/d/1FewT40RbYxc1H3ecmtr78CoVg5TkmKn0/view?usp=sharing)
* **Email**: das360497@gmail.com

```

```
