# 📊 Meta Ad Performance Analytics Dashboard  
### Data Analytics Project | Power BI

---

## 🧠 Project Overview

This project is a data analytics dashboard built in Power BI to analyze advertising performance across Meta platforms (Facebook and Instagram).

Using a dataset containing 400,000+ ad event records over four months, the dashboard transforms raw campaign data into meaningful performance insights. The objective is to evaluate engagement trends, cost efficiency, demographic behavior, and campaign effectiveness using interactive visual analytics.

---

## 🎯 Problem Statement

Marketing datasets often contain large volumes of performance metrics such as impressions, clicks, conversions, and engagement data. Without structured modeling and analysis, extracting actionable insights becomes difficult.

This dashboard addresses:

- Platform-wise performance comparison  
- Campaign efficiency evaluation  
- Audience engagement analysis  
- Cost optimization tracking  
- Time-based performance trends  

---

## 📌 Key Features

### 🔄 Platform Comparison
Toggle between Facebook and Instagram to compare campaign performance metrics.

### 📈 Dynamic KPI Calculations (DAX)
The dashboard includes calculated measures for:
- Click Through Rate (CTR)
- Cost Per Click (CPC)
- Conversion Rate
- Engagement Rate
- Total Spend
- ROI Indicators

All KPIs dynamically update based on applied filters.

### 🎛 Interactive Visual Controls
Users can switch metrics (Impressions, Clicks, Comments, Conversions, etc.) across charts using a unified slicer.

### 🔍 Advanced Filtering
Filters include:
- Gender
- Age Group
- Target Interest Category
- Country
- Campaign Type
- Platform

### ⏳ Time-Series Analysis
Weekly and hourly trend analysis to identify peak engagement periods.

---

## 🏗 Data Model

The data model follows a structured schema optimized for performance and scalability.

### Fact Table
- `Ad_Events` (400,000+ rows)

### Dimension Tables
- `Users_Data`
- `Ads_Data`
- `Campaigns`
- `Date_Table`

### Modeling Approach
- Snowflake Schema
- Proper relationship cardinality
- Custom Calendar Table for time intelligence
- Optimized aggregations for large dataset handling

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **Power Query (ETL & Data Cleaning)**
- **DAX (Data Analysis Expressions)**
- **Data Modeling (Snowflake Schema)**
- **Time Intelligence Functions**

---

## 📊 Analytical Insights Generated

- High engagement observed in the 16–25 age group  
- Video and Carousel ads outperform static image ads  
- Regional variation in conversion efficiency  
- Peak engagement hours identified during specific daily windows  
- Cost optimization opportunities detected across campaigns  

---

## 📷 Dashboard Preview

(Add screenshots below)

