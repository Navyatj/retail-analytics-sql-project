# Coffee Shop SQL Business Analysis

## 📌 Project Overview

This project presents a data-driven SQL analysis of a coffee shop dataset to evaluate:

Sales performance across cities

Customer behavior patterns

Product demand concentration

Market penetration gaps

Unit economics and cost efficiency

City-level expansion feasibility

The objective is to support strategic decision-making for offline store expansion using structured SQL-based insights.

## 🗂️ Database Structure

The analysis was conducted using a relational database with the following tables:

City – Population, estimated rent, city ranking

Products – Product details and pricing

Customers – Customer information and city mapping

Sales – Transaction-level sales data with date, revenue, and ratings

The dataset was imported using SQL Server BULK INSERT and analyzed using joins, aggregations, CTEs, and window functions.

## 🔍 Key Business Questions Addressed

What is the estimated coffee-consuming market size in each city?

What is the total revenue generated in the last quarter of 2023?

Which products drive the highest sales volume?

What is the average revenue per customer by city?

How large is the market penetration gap?

What are the top 3 selling products in each city?

How do unit economics (revenue vs rent per customer) vary?

What is the monthly sales growth trend?

Which cities are most suitable for expansion?

## 📊 Key Insights

Revenue is concentrated in a few top-performing cities.

Significant gap exists between estimated consumers and actual customers.

Product demand is concentrated but varies by location.

Customer monetization differs across cities.

Unit economics vary significantly despite similar revenue levels.

Growth momentum is inconsistent across markets.

Expansion decisions must integrate revenue, cost, and growth metrics.

#### 🏙️ Recommended Cities for Expansion

Based on revenue strength, customer base, cost feasibility, and growth stability:

🥇 Pune

High revenue, strong customer spend, moderate rental exposure.

🥈 Chennai

Balanced revenue-to-cost structure with sustainable growth.

🥉 Jaipur

Strong unit economics and lowest rent per customer.

#### ❌ Cities Not Recommended

Bangalore – High rental exposure leading to margin risk.

Delhi – Lower revenue per customer relative to cost structure.

## 🛠️ Tools & Techniques Used

SQL Server

Joins (INNER JOIN)

Aggregations (SUM, COUNT, AVG)

CTEs

Window Functions (LAG, DENSE_RANK)

Date functions (YEAR, MONTH, DATEPART)

Revenue growth calculation

Unit economics analysis

## 📈 Analytical Focus Areas

Market Size Estimation

Revenue Performance Analysis

Product Portfolio Optimization

Customer Monetization

Cost Efficiency Evaluation

Trend & Growth Analysis

Multi-Metric Expansion Framework

## 🎯 Project Outcome

This analysis demonstrates how structured SQL queries can be used to translate raw transactional data into actionable business insights that inform expansion strategy and profitability optimization.
