# UrbanKart-Ecommerce-Analytics
End-to-end Retail &amp; E-commerce Analytics Project using Python, MySQL, and Power BI.


# 🛒 UrbanKart: End-to-End E-commerce Analytics Project

> An end-to-end retail analytics project that simulates a real-world e-commerce business using Python, MySQL, and Power BI. The project covers synthetic data generation, database design, SQL analytics, customer analytics in Python, and interactive business intelligence dashboards.

---

## Project Overview

UrbanKart is a fictional e-commerce company operating across multiple cities in India. As the company expanded, large volumes of transactional, customer, inventory, and operational data were generated daily. However, this data remained fragmented across multiple business functions, making it difficult for management to extract actionable insights.

This project demonstrates a complete analytics workflow by transforming raw business data into meaningful insights using database management, SQL, Python, and Power BI.

The project follows the same lifecycle that many organizations use for business analytics:

- Business Understanding
- Data Generation
- Database Design
- SQL Analytics
- Python Analytics
- Business Intelligence Dashboard
- Business Recommendations

---

## Business Problem

UrbanKart's management wants to answer several key business questions:

- Which products and categories generate the highest revenue?
- Which customer segments contribute most to sales?
- How do customer purchasing patterns change over time?
- Which marketing campaigns perform best?
- What factors contribute to product returns?
- How effectively is inventory managed?
- Which geographical regions generate the highest sales?
- How can customer retention and profitability be improved?

The objective is to build a centralized analytics solution that enables data-driven decision-making.

---

## Project Objectives

- Design a relational database for an e-commerce business.
- Generate realistic synthetic retail data using Python.
- Build and normalize a MySQL database.
- Perform business analysis using SQL queries and views.
- Used Python for data manipulation, exploratory analysis, customer analytics, visualization.
- Create interactive Power BI dashboards for executive reporting.
- Generate actionable business insights from the data.

---

# Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Data Generation & Analytics |
| Pandas | Data Manipulation |
| NumPy | Synthetic Data Generation |
| Matplotlib | Data Visualization |
| MySQL | Relational Database |
| SQL | Business Queries & KPIs |
| Power BI | Interactive Dashboards |
| Git & GitHub | Version Control |

---

# Dataset Overview

The project consists of a fully normalized retail database containing multiple fact and dimension tables.

| Table | Description |
|--------|-------------|
| Categories | Product categories |
| Suppliers | Product suppliers |
| Warehouses | Warehouse information |
| Couriers | Shipping partners |
| Products | Product catalog |
| Customers | Customer demographics |
| Marketing Campaigns | Campaign details |
| Orders | Customer orders |
| Order Items | Products purchased in each order |
| Inventory | Warehouse inventory |
| Payments | Payment transactions |
| Shipping | Shipment details |
| Returns | Product return records |
| Reviews | Customer ratings and reviews |

---
# Project Size

- Customers: 100,000
- Orders: 391,000+
- Products: 1,892
- Reviews: 364,000+
- Revenue: ₹12.6 Billion

---- 


# Database Design

The database follows a normalized relational model to eliminate redundancy while maintaining data integrity.

### Features

- Primary Keys
- Foreign Keys
- One-to-Many Relationships
- Normalized Structure
- Fact & Dimension Tables

### ER Diagram

> <img width="3575" height="1868" alt="UrbanKart E-Commerce Data Model ER" src="https://github.com/user-attachments/assets/495324ff-caee-45fc-a4f2-40bb23192072" />


---

# Synthetic Data Generation

Instead of using publicly available datasets, realistic business data was generated using Python.

The generated data includes:

- Customer demographics
- Product catalog
- Order transactions
- Inventory levels
- Marketing campaigns
- Shipping records
- Payment details
- Customer reviews
- Product returns

This approach provides full control over business rules and relationships while creating a scalable analytics dataset.

---

# SQL Analysis

The SQL phase focused on designing the database and answering business questions through optimized queries.

### Database Implementation

- Database Creation
- Table Design
- Primary Keys
- Foreign Keys
- Constraints
- Relationships

### Business KPIs

Examples include:

- Total Revenue
- Total Orders
- Average Order Value
- Revenue by Category
- Revenue by State
- Customer Spending
- Inventory Status
- Return Rate
- Product Performance

### SQL Views

Several reusable SQL views were created to simplify reporting and dashboard development.

---

# Python Analytics

Python was used for exploratory data analysis and business analytics beyond SQL reporting.

The analyses include:

## Customer Analytics

- RFM Segmentation
- Customer Lifetime Value (CLV)
- Cohort Analysis
- Customer Behavior Analysis

## Sales Analytics

- Time Series Analysis
- Revenue Trends
- Monthly Sales
- Customer Growth

## Product Analytics

- Product Performance
- Category Performance
- Inventory Analysis

## Operational Analytics

- Returns Analysis
- Customer Reviews Analysis

> <img width="1190" height="597" alt="image" src="https://github.com/user-attachments/assets/c2a3e2a2-8955-4727-b494-239665c38cc1" />

> <img width="1322" height="622" alt="image" src="https://github.com/user-attachments/assets/ad2bbf0a-01fb-40cc-8096-cad510a4a848" />

> <img width="1297" height="632" alt="image" src="https://github.com/user-attachments/assets/48a7c6d9-6ba0-417c-b2e6-31bb31316717" />

> <img width="1285" height="622" alt="image" src="https://github.com/user-attachments/assets/5b2bbc73-9bf9-426f-b78f-763ccdc7482f" />

><img width="1437" height="712" alt="image" src="https://github.com/user-attachments/assets/da20ba5f-84db-4a0c-a99c-c3e6191cda86" />



---

# Power BI Dashboard

An interactive Power BI dashboard was developed for business users.

The dashboard consists of four pages.

## Executive Dashboard

Displays overall business performance through KPIs and revenue trends.

Business KPIs
- Revenue
- Orders
- Average Order Value
- Customer Count

Visualizations
- Monthly Revenue Trend
- Revenue by State
- Revenue by Category
- Acquisition Channel Performance
- Revenue by Loyalty Tier

> <img width="1407" height="711" alt="Executive dashboard" src="https://github.com/user-attachments/assets/9c541013-9bec-41c9-899d-d7a74250abf7" />


---

## Customer Analytics Dashboard

Provides customer segmentation, acquisition, demographics, and purchasing behavior.

Business KPIs
- Repeat Customers
- Repeat Customer Rate
- Active Customers
- Average Customer Spend

Visualizations
- Monthly Customer Signups
- Customer Age Distribution
- Top Customers by Revenue
- Gender Distribution
- Customer Acquisition Channels

> <img width="1412" height="711" alt="Customer Analysis" src="https://github.com/user-attachments/assets/5ce98dd9-1824-48e5-9efe-da7e331acd56" />

---

## Product & Inventory Dashboard

Analyzes product sales, inventory levels, supplier performance, and stock availability.

Business KPIs
- Product Count
- Quantity Sold
- Inventory Value
- Low Stock Products

Visualizations
- Top Selling Products
- Highest Revenue Products
- Inventory Value by Category
- Inventory Status
- Warehouse Stock Distribution
- Supplier Revenue

> <img width="1522" height="782" alt="Products and Inventory Dashboard" src="https://github.com/user-attachments/assets/c9c0a26b-38ec-4ba1-94c1-0eff553b0da8" />


---

## Returns & Customer Experience Dashboard

Monitors returns, refunds, shipping performance, and customer reviews.

Business KPIs
- Refund Amount
- Return Rate
- Average Rating
- Reviews Count

Visualizations
- Monthly Returns
- Rating Distribution
- Return Reasons
- Shipping Status
- Payment Method Distribution

> <img width="1412" height="702" alt="Returns   Customer Experience Dashboard" src="https://github.com/user-attachments/assets/7ab4b3c6-d9cd-4a66-a64a-0dda12705d78" />


---

# Key Business Insights

**Executive Dashboard**
- Generated ₹12.6 Billion in revenue from 391K orders.
- Revenue accelerated significantly after July 2024, indicating strong seasonal demand.
- Maharashtra contributed the highest revenue (₹3.1 Billion).
- Electronics was the largest revenue-generating category (₹4.5 Billion).
- Organic Search and Google Ads together generated nearly 60% of total revenue.
- Bronze loyalty customers contributed approximately 60% of total revenue.
---

**Customer Analysis**
- 55.02% of customers made repeat purchases.
- Average customer spend reached ₹125.9K.
- Customers aged 25–44 formed the largest customer segment.
- Organic acquisition remained the strongest customer acquisition channel.
- A small group of customers generated disproportionately high revenue.

---
**Product & Inventory**
- Managed 1,892 products while selling nearly 977K units.
- Inventory value reached ₹6.7 Billion.
- Electronics represented the largest inventory investment (₹3.06 Billion).
- Only 5% of products required replenishment.
- Premium electronics generated the highest product revenue.
---

**Returns & Customer Experience**
- Return rate remained low at 3.05%.
- Average customer rating reached 4.14 / 5.
- More than 80% of reviews were rated 4 or 5 stars.
- Product quality and damaged products were among the primary return drivers.
- UPI emerged as the most preferred payment method.

---
# Business Recommendations

- Increase inventory allocation for high-performing categories during peak demand periods.
- Strengthen supplier quality assurance to reduce product returns.
- Expand investment in Organic Search and high-performing digital marketing channels.
- Enhance loyalty programs to increase repeat purchases and customer lifetime value.
- Improve demand forecasting to optimize inventory investment.
- Strengthen packaging standards to reduce damage-related returns.

---

# Skills Demonstrated

- Data Modeling
- Relational Database Design
- SQL Query Writing
- Business KPI Development
- Exploratory Data Analysis
- Customer Analytics
- Time Series Analysis
- Data Visualization
- Dashboard Design
- Business Intelligence
- Git & GitHub Documentation

---

# Author

**Bhawna Kumari**

Data Analyst | SQL | Python | Power BI

LinkedIn: https://www.linkedin.com/in/bhawna-kumari-data-analyst/

GitHub: https://github.com/Bhawna013


---

## License

This project is intended for educational and portfolio purposes.
