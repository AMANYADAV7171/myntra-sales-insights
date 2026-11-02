# 🛍️ Myntra Sales Analysis Dashboard

An interactive **Power BI dashboard** that analyzes Myntra fashion e-commerce sales data across brands, product categories, customer demographics, and locations. It helps uncover buying patterns, top-performing brands, and regional trends to support data-driven business decisions.

---

## 📌 Project Overview

This project explores sales data from **500 orders** across **10 popular fashion brands** and **5 product categories**. The dashboard turns raw transactional data into clear visuals, so stakeholders can quickly see what sells, who buys it, and where.

---

## 🎯 Objectives

- Analyze brand-wise sales performance by customer gender
- Identify the most popular product categories
- Compare order trends across years (2024 vs 2025)
- Understand customer distribution across cities
- Study the relationship between unit price, total price, and quantity ordered

---

## 📊 Dashboard Features

### Page 1: Sales Overview
| Visual | Insight |
|---|---|
| **Matrix Table** | Brand-wise order counts split by Female / Male customers (Total: 1,229) |
| **Donut Chart** | Share of Unit Price (29.16%) vs Total Price (70.84%) |
| **Pie Chart** | Quantity sold by product category (Men Clothing leads at ~21.97%) |
| **Combo Chart** | Customer count and total sales value by product category |
| **Stacked Column Chart** | Orders by product category, compared across 2024 and 2025 |
| **Clustered Column Chart** | Brand count by customer location and gender |
| **Slicers** | Filter by Gender, Customer Location, and Brand |

### Page 2: Deep-Dive Analysis
| Visual | Insight |
|---|---|
| **100% Stacked Area Chart** | Female vs Male customer share for each brand |
| **Area Chart** | Brand count by quantity ordered |
| **Scatter Plot** | Sum of unit price by brand |
| **Decomposition Tree** | Drill-down of 500 orders by Product Category → Customer Gender |

---

## 🔍 Key Insights

- **Men Clothing** is the top category by order count (109 orders), followed by Beauty and Footwear (105 each).
- **Adidas** has a female-dominated customer base (~61% female).
- **H&M** records the highest total unit price among all brands.
- **Chennai** has the highest customer count, with female customers leading in most cities.
- Order volume grew in **2025** across most product categories.
- Footwear orders are skewed toward female customers (60 female vs 45 male).

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**: data modeling, DAX, and visualization
- **Excel / CSV**: source dataset
- **Power Query**: data cleaning and transformation

---

## 📁 Repository Structure
