# 📊 Customer Insights Dashboard

A data analysis project exploring customer demographics, order behavior, regional distribution, and training course offerings using four structured datasets.

## 📁 Project Overview

This project combines information from Customer, Community, Orders, and Courses datasets to uncover patterns across order trends, customer segments, and product offerings.

The aim is to analyze real-world data, validate dataset relationships, and present actionable insights that business leaders can use.

## 🗂 Included Datasets

| File | Content |
|------|---------|
| `dashboard.xlsx` | 100 customer records including age, gender, and region |
| `Community.csv` | Customer demographic details (duplicate fields for validation) |
| `Courses.csv` | 10 course offerings including category and pricing |
| `Orders.csv` | Customer order transactions linked via CustomerID |

## 🎯 Key Questions Explored

- What are the demographic characteristics of customers?
- Which regions account for the greatest customer presence?
- Which courses are available and how are they priced?
- How do customer orders relate to age, region, or gender groups?
- How well do the datasets align with each other?

## 🔍 Methods & Approach

### 1️⃣ Data Cleaning & Validation
- Verified CustomerID integrity across all datasets
- Checked for missing/invalid fields
- Ensured consistent values across categories

### 2️⃣ Exploratory Data Analysis
- Age range, gender ratio, and regional distribution
- Frequency and aggregation summaries
- Course pricing patterns

### 3️⃣ Cross-Linking Files
- Connected Orders to Customers via CustomerID
- Compared demographic presence vs order activity
- Mapped course availability to purchases

### 4️⃣ Report & Dashboard Prep
- Pivot tables
- Aggregated metrics (region, gender, orders)
- Summary tables for insights

## 📈 Insight Highlights

- Dataset covers 100 customers across 6 Nigerian regions
- Gender split: ~63% Male / 37% Female
- Age range: 18–60 (avg ≈ 40 years)
- Regions with highest representation:
  - South East
  - North Central
  - South West

- Orders dataset adds:
  - Purchase totals per customer
  - Transaction opportunities for upsell
  - Course utilization potential

- Insight opportunities:
  - Identify top ordering customers
  - Analyze order frequency by region
  - Track which course categories drive more demand

## 🛠 Tools Used
- Excel
- Pivot Tables
- VLOOKUP / XLOOKUP
- COUNTIF / SUMIF / AVERAGE
- Data validation techniques

## 🌟 Skills Demonstrated
- Multi-source data merging
- Data validation and cleaning
- Insight extraction & storytelling
- Simple dashboard construction
- Dataset documentation

## 🚀 Future Enhancements
- Load files into Power BI or Tableau for visual dashboards
- Perform time-based analysis if order dates are added
- Automate joins using Python or SQL for scalability
