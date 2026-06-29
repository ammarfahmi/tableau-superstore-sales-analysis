# Executive Sales Performance Dashboard

An end-to-end Business Intelligence project developed using **Tableau** to analyze sales performance, product profitability, customer behavior, and regional performance using the Sample Superstore dataset.

---

## Project Overview

### Business Problem

The management team of a nationwide office supply retailer lacked a centralized reporting solution to monitor overall business performance. Existing reports were static and made it difficult to identify sales trends, profitable products, high-value customers and regional performance.

This project aims to develop an interactive Tableau dashboard that enables management to make data-driven decisions through visual analytics and actionable business insights.

---

## Project Objectives

* Develop an executive-level sales performance dashboard.
* Monitor key business performance indicators (KPIs).
* Identify top and underperforming products.
* Analyze customer purchasing behavior.
* Evaluate regional and managerial performance.
* Provide actionable recommendations to improve business performance.

---

## Intended Stakeholders

| Stakeholder                   | Business Need                            |
| ----------------------------- | ---------------------------------------- |
| Chief Executive Officer (CEO) | Overall company performance              |
| Sales Manager                 | Regional sales performance               |
| Product Manager               | Product profitability                    |
| Operations Manager            | Return analysis and shipping performance |

---


# Dataset Description

The project uses the **Sample Superstore** dataset consisting of three related tables.

## Orders

The primary transactional table containing:

* Order information
* Customer information
* Product information
* Geographic information
* Sales metrics
* Profit metrics

Key Fields:

* Order ID
* Order Date
* Customer Name
* Segment
* Region
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit

---

## Returns

Contains returned orders.


Used to analyze the financial impact of product returns.

---

## People

Maps each sales region to its corresponding regional manager.


Used for regional performance analysis.

---

# Data Preparation

The following preprocessing steps were performed before analysis.

### Data Cleaning

* Verified data types.
* Ensured numerical fields were correctly formatted.
* Removed unnecessary fields from the analysis.
* Applied appropriate currency and percentage formatting.

---

### Calculated Fields

| Calculated Field    | Purpose                                        |
| ------------------- | ---------------------------------------------- |
| Profit Margin       | Measure profitability                          |
| Average Order Value | Average revenue generated per order            |
| Return Status       | Identify returned orders                       |
| Returned Profit     | Measure profit associated with returned orders |

---

# Dashboard Overview

The project consists of **three interactive dashboards** and **Tableau Story**.

---

## Dashboard 1 — Executive Overview

### Purpose

Provide management with a high-level overview of business performance.

### KPIs

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Average Order Value

### Visualizations

* KPI Cards
* Monthly Sales Trend
* Sales by Region
* Sales by Category
* Sales by Customer Segment
* Geographic Sales Map

**Dashboard Screenshot**

![Loading...](https://drive.google.com/file/d/15prkl2EMKUmcLNWeENhKKUge7J7Entyt/view?usp=sharing)

---

## Dashboard 2 — Product Performance

### Purpose

Identify products and categories contributing most to company profitability.

### Visualizations

* Top 10 Products
* Bottom 10 Products
* Sales vs Profit Scatter Plot
* Category Heatmap
* Product Treemap

**Dashboard Screenshot**

![Loading...](https://drive.google.com/file/d/1DhR4lLWCN4y7-JFA92gB-NposqDQ-pYw/view?usp=sharing)

---

## Dashboard 3 — Customer & Regional Performance

### Purpose

Understand customer behavior, regional performance, shipping methods and return analysis.

### Visualizations

* Top Customers
* Sales by Regional Manager
* Customer Segment Analysis
* Shipping Mode Analysis
* Returns Analysis
* Regional Performance Map

**Dashboard Screenshot**

![Loading...](https://drive.google.com/file/d/1FndLJJxeL-T29nhoZbkJW0UKfkgoKxp_/view?usp=sharing)

---

# Tableau Story

The Tableau Story presents the dashboards as a business presentation.

| Story Page                | Purpose                           |
| ------------------------- | --------------------------------- |
| Executive Summary         | Overall company performance       |
| Product Analysis          | Product profitability             |
| Regional Analysis         | Customer and regional performance |
| Executive Recommendations | Business recommendations          |

**Story Screenshots**

![Loading...](https://drive.google.com/file/d/1yDRTXMAqzxbXTp6S4_jJ3QXJ2UXvXlxc/view?usp=sharing)
![Loading...](https://drive.google.com/file/d/1jcIW_zRgXQ5bhIOBH-O2zVwPj9-ct9BP/view?usp=sharing)
![Loading...](https://drive.google.com/file/d/1e-PFPtfdU8qrAM5zey1qkxaiRmKT_KUO/view?usp=sharing)
![Loading...](https://drive.google.com/file/d/1q9UUd4sbpwGvDrBa-htxg6-dgnouUGDG/view?usp=sharing)

---

# Key Business Insights

## 1. West Region Generated the Highest Revenue

The West region consistently produced the highest sales while maintaining healthy profit margins.

**Business Impact**

The region represents the company's strongest performing market.

---

## 2. Technology Products Deliver the Highest Profit

Technology products generated both high sales and strong profit margins.

**Business Impact**

Technology should remain a strategic investment category.

---

## 3. Furniture Products Have Lower Profit Margins

Although Furniture contributed significant revenue, profitability remained comparatively weak.

**Business Impact**

Revenue growth does not necessarily translate into profitability.

---

## 4. Customer Revenue is Highly Concentrated

A relatively small group of customers contributed a significant proportion of total sales.

**Business Impact**

Customer retention strategies should prioritize these high-value customers.

---

# Business Recommendations

| Finding                        | Recommendation                                             |
| ------------------------------ | ---------------------------------------------------------- |
| Strong Technology performance  | Increase inventory and promotional activities              |
| Low Furniture profitability    | Review pricing strategy and supplier costs                 |
| West region outperforms others | Replicate successful sales strategies across other regions |
| High-value customers           | Implement customer loyalty and retention programs          |

---

# Skills Demonstrated

## Business Intelligence

* Executive Dashboard Design
* KPI Development
* Data Storytelling
* Business Analysis
* Decision Support

## Tableau

* Dashboard Development
* Interactive Filters
* Dashboard Actions
* Story Creation
* Calculated Fields
* Maps
* Heatmaps
* Scatter Plots

## Data Analysis

* Data Cleaning
* Data Modeling
* Relationship Modeling
* Profitability Analysis
* Customer Analysis
* Regional Performance Analysis

---

# Repository Structure

```
.
├── README.md
├── workbook/
│   └── Executive Sales Dashboard.twbx
├── dataset/
│   └── Sample Superstore.xlsx
├── screenshots/
│   ├── Dashboard1.png
│   ├── Dashboard2.png
│   ├── Dashboard3.png
│   ├── Story1.png
│   ├── Story2.png
│   ├── Story3.png
│   └── Story4.png
```

---

# Instructions

1. Download the Tableau workbook (`.twbx`).
2. Open it using Tableau Desktop or Tableau Public.
3. Navigate through the dashboards.
4. Explore the interactive filters and dashboard actions.
5. Review the Tableau Story for a guided business presentation.

---

# Tools & Technologies

* Tableau Desktop
* Microsoft Excel

---

# Future Improvements

Potential enhancements include:

* Connecting to a live SQL database.
* Automating data refreshes.
* Publishing dashboards to Tableau Public or Tableau Server.
* Incorporating predictive analytics and forecasting.

---

# Author

**Ammar Fahmi**

Feel free to explore the workbook and provide feedback.
