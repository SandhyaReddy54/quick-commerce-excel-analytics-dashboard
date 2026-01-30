# 📦 Quick-Commerce Operations Dashboard (Excel Case Study)
## 📌 Project Overview

This project is an exploratory operational analytics case study built using Microsoft Excel, focusing on understanding revenue drivers, demand patterns, payment success, and customer experience in a quick-commerce (instant grocery delivery) context.

## 🎯 Objectives

* Clean and prepare multi-table transactional data using Power Query
* Build a structured Data Model with relationships
* Design meaningful business KPIs
* Perform exploratory analysis using Pivot Tables
* Create an interactive executive dashboard using Pivot Charts and slicers
* Derive actionable insights related to operations and customer experience
  
## 🛠️ Tools & Techniques Used

#### Microsoft Excel
* Power Query (data cleaning & transformation)
* Data Model & relationships
* Pivot Tables & Pivot Charts
* DAX Measures (for KPIs)
* Slicers & Timelines
* KPI cards

## 📂 Dataset Description

The dataset simulates a quick-commerce platform with the following entities:
* Customers – customer demographics and location
* Orders – order date, quantity, coupons, delivery partner
* Products – product category, brand, pricing
* Transactions – payment mode and transaction status
* Ratings – product and delivery/service ratings
* Delivery Partners – delivery agent information

## 🧹 Data Cleaning & Preparation
#### Performed using Power Query:
* Standardized column names and data types
* Removed orphan and invalid records (e.g., ratings without orders)
* Created derived fields:
* Order Day
* Monthly buckets
* Hourly divisions
* Validated relationships across tables
* Loaded clean tables into the Excel Data Model

## 📊 Key KPIs

The dashboard highlights the following core KPIs:
* Total Revenue (Net Order Value)
* Total Orders
* Average Order Value (AOV)
* Order Completion Rate

## 📈 Dashboard Analysis & Insights
🔹 Revenue & Demand Trends
* Monthly revenue shows moderate variation across the available period
* Order volume is relatively stable across weekdays, with mid-week peaks
🔹 Revenue Drivers
* Personal Care and Snacks categories show higher AOV
* Revenue is concentrated in a few key states, indicating regional demand clustering
🔹 Payments & Operations
* Digital payment methods (UPI, Cards) show higher success rates than COD
* Payment mode selection impacts order completion
🔹 Customer Experience
* Average ratings appear healthy, but distribution analysis shows a meaningful share of low ratings
* Rating distribution provides better insight than averages alone





