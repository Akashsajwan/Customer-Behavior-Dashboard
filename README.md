# Customer Shopping Behavior Analytics Dashboard | Power BI

## 📌 Overview

This project is an end-to-end **Customer Behaviour Analytics** project focused on analyzing customer purchasing patterns, customer demographics, subscription status, product categories, and purchase performance.

The project follows a complete data analytics workflow:

**Dataset → Python → EDA → Data Cleaning → SQL Analysis → Power BI → Report → Presentation**

The final Power BI dashboard provides an interactive view of customer behaviour and purchasing trends, helping identify patterns across **customer segments, age groups, gender, subscription status, product categories, and purchased items**.

---

## 📊 Dataset

The project uses a customer behaviour dataset containing customer-level purchasing and demographic information.

### Key Data Attributes

- Customer ID
- Gender
- Age / Age Group
- Subscription Status
- Product Category
- Item Purchased
- Purchase Amount
- Customer-related metrics
- Average Purchases
- Average Rating

The dataset was prepared and analyzed before being used for dashboard development.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data loading, cleaning and exploratory data analysis |
| **Pandas** | Data manipulation and preprocessing |
| **NumPy** | Numerical analysis |
| **Matplotlib / Seaborn** | Data visualization during EDA |
| **SQL** | Data analysis and querying |
| **PostgreSQL / MySQL / SQL Server** | Database-based analysis |
| **Power BI** | Interactive dashboard development |
| **DAX** | Measures and analytical calculations |
| **Power Query** | Data transformation |
| **Gamma** | Presentation/PPT creation |

---

## 🔄 Project Workflow

### 1. Dataset Loading

The dataset was initially loaded into Python using Pandas for inspection and analysis.

The initial analysis focused on:

- Understanding the structure of the dataset
- Identifying columns and data types
- Checking the number of records
- Identifying missing values
- Understanding categorical and numerical variables

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand customer behaviour and identify meaningful patterns.

The analysis included:

- Customer demographic analysis
- Purchase amount analysis
- Category-wise analysis
- Age-group analysis
- Subscription status analysis
- Gender-wise analysis
- Item purchase analysis
- Customer distribution analysis
- Statistical exploration of numerical variables

Python visualizations were used to understand trends and distributions before dashboard development.

---

### 3. Data Cleaning & Preparation

The dataset was cleaned and prepared for further analysis.

Key activities included:

- Handling missing values
- Checking duplicate records
- Correcting data types
- Standardizing categorical values
- Creating useful analytical fields
- Creating customer age groups
- Preparing the dataset for SQL and Power BI

---

### 4. SQL Analysis

The cleaned dataset was loaded into a relational database and analyzed using SQL.

SQL queries were used to perform tasks such as:

- Customer-level analysis
- Category-wise purchase analysis
- Age-group analysis
- Subscription-status analysis
- Gender-wise analysis
- Purchase amount analysis
- Customer segmentation
- Aggregation and filtering
- Sorting and ranking

SQL helped validate and analyze the dataset from a database perspective.

---

## 📈 Power BI Dashboard

The final Power BI dashboard is titled:

### **Customer Behavior Dashboard**

The dashboard contains key performance indicators and interactive visualizations.

### KPI Cards

The dashboard displays important customer metrics including:

- **Total Customers**
- **Total Purchases**
- **Average Purchases**
- **Average Rating**

### Visualizations

The dashboard includes analysis of:

- **Subscription Status**
- **Purchase Amount by Category**
- **Customers by Category**
- **Purchase Amount by Age Group**
- **Customers by Age Group**
- **Purchase Amount by Item Purchased**

### Interactive Filters

Users can interact with the dashboard using filters for:

- Subscription Status
- Gender
- Category

These filters allow users to explore customer behaviour across different segments.

---

## 🔍 Results

The analysis provides a consolidated view of customer purchasing behaviour across different dimensions.

The dashboard enables users to examine:

- How customers are distributed across subscription statuses
- Which product categories generate higher purchase amounts
- How purchasing behaviour differs across age groups
- Customer distribution across categories
- Purchase patterns across different customer segments
- Which items contribute more to overall purchase amounts
- Differences in behaviour based on gender and subscription status

The interactive Power BI dashboard makes these patterns easier to explore and compare.

---

## 📑 Report

A detailed analytical report was created based on the findings from:

**Python EDA + Data Cleaning + SQL Analysis + Power BI Dashboard**

The report documents the methodology, analysis, visual findings, and important observations from the project.

---

## 📽️ Presentation

A professional project presentation was created using **Gamma**.

The presentation summarizes:

- Project objective
- Dataset
- Data preparation
- EDA
- SQL analysis
- Power BI dashboard
- Key findings
- Final observations

---

## 🖼️ Dashboard Preview

### Customer Behavior Dashboard

![Customer Behavior Dashboard](https://github.com/Akashsajwan/Customer_Shopping_Behavior_Dashboard/blob/main/Customer_behavior_Dashboard.png)

---

---

## 🖼️ Findings and recommendations Preview

### Dashboard Insights

![Dashboard Insights](https://github.com/Akashsajwan/Customer_Shopping_Behavior_Dashboard/blob/main/Customer_behavior_Insights.png)

---

## 📂 Project Structure

```text
Customer-Behaviour-Analytics/
│
├── dataset/
│   └── customer_behaviour.csv
│
├── python/
│   └── customer_behaviour_eda.ipynb
│
├── sql/
│   └── customer_behaviour_queries.sql
│
├── powerbi/
│   └── customer_behaviour_dashboard.pbix
│
├── report/
│   └── customer_behaviour_report.pdf
│
├── presentation/
│   └── customer_behaviour_presentation.pdf
│
├── screenshots/
│   └── customer_behaviour_dashboard.png
│
└── README.md
