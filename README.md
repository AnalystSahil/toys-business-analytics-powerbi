# Toys Business Analytics — Power BI Project

Business Intelligence • DAX • Data Modeling • Time Intelligence • Website Analytics

## 📌 Project Overview

A Power BI-based business analytics solution built for a toy business. The report combines order, order-item, refund, product, website-session, and website-pageview data into one consolidated view of business performance.

The project converts raw business data into analytical insights through data preparation, calculated columns, DAX measures, time-intelligence calculations, and an interactive dashboard covering sales, orders, products, profitability, refunds, website traffic, sessions, and marketing sources.

**Scope:** Descriptive and diagnostic analytics — explains *what happened* in the business. This is not a predictive/ML system.

## 🎯 Objectives

- Analyze overall toy business performance
- Measure total sales, orders, items purchased, and toys sold
- Analyze profitability (COGS, profit, profit margin)
- Analyze refund amount and average refund performance
- Understand website sessions and pageview activity
- Analyze traffic sources, UTM info, device type, referral sources
- Build a custom Date table for time-based analysis
- Use MTD and YTD calculations for time intelligence
- Check distinct values and NULL/blank values as part of data quality
- Build an interactive report with page navigation

## 🗂️ Dataset / Tables

| Table | Purpose |
|---|---|
| `orders` | Order-level sales, cost, profit, customer/session info |
| `order_items` | Item-level product/order info and COGS data |
| `order_item_refunds` | Refund transactions and amounts |
| `products` | Product master info (ID, name) |
| `website_sessions` | Session, device, referral, UTM, user info |
| `website_pageviews` | Pageview activity and session metrics |
| `custom_date` | Date dimension for month/quarter/week/year/MTD/YTD |

## 🧮 Data Preparation & Calculations

- **Custom Date table** — Date, month, month_num, quarter, week of year, years, MTD, YTD
- **Data quality checks** — NULL/blank value analysis, distinct/different value analysis (device type, referral source, UTM source/campaign, pageview URL, etc.)
- **DAX measures** across:
  - Sales & Orders: Total Sales, Total Orders, Average Order, Items Purchased, Total Toys Sold
  - Profitability: COGS, Profits, Profit Margin
  - Refunds: Total Refund, Average Refund
  - Website Analytics: Total Sessions, Total Pageviews, Unique Sessions, Pageviews per Session
  - Marketing/Traffic: http_referer, new_utm_source, new_utm_content, utm_campaign, device_type, is_repeat_session

## 📊 Business Analysis Areas

1. **Sales Performance** — overall sales, order volume, average order value, toy units sold, trend over time
2. **Product Performance** — product-level sales, contribution, primary vs. item-level analysis
3. **Profitability** — profit, COGS impact, profit margin, revenue vs. profitability
4. **Refund Performance** — total/average refund vs. order performance
5. **Website Sessions & Pageviews** — session volume, pageviews, engagement, link to orders
6. **Marketing & Traffic Analysis** — UTM source/campaign/content, referral source, device type
7. **Time-Based Analysis** — monthly, quarterly, yearly, weekly, MTD, YTD performance

## 🖥️ Dashboard Structure

- **Overview / Home Page** — Total Revenue, Ticket Size, Total Cost, Unit Sold, Profit Rate, Total Profit by Product, Sales Trend, Sales by Product, Refund by Product, Orders by UTM
- **Navigation Panel** — Quarter filters (Qtr 1–Qtr 4) and Year buttons (2012–2015)
- **Yearly Pages** — 2012, 2013, 2014, 2015 (sales, profit, refund, and UTM performance per year)

## 📈 Key KPIs

Total Sales • Total Orders • Average Order • Total Items Purchased • Total Toys Sold • COGS • Profit • Profit Margin • Total Refund • Average Refund • Total Sessions • Total Pageviews • Unique Sessions

## ✅ Conclusion

This project demonstrates using Microsoft Power BI to turn raw order, item, product, refund, session, and pageview data into an interactive BI solution. DAX measures, calculated fields,
a custom Date table, MTD/YTD calculations, and data-quality checks strengthen the analytical foundation, helping users understand sales, profitability, products, refunds, website activity, and marketing traffic from one dashboard.
