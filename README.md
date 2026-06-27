# Shield Insurance Business Intelligence Dashboard

## 📌 Project Overview

This Power BI project was developed as part of the **Codebasics Virtual Internship Program** to analyze insurance business performance and provide actionable insights through an interactive dashboard.

The dashboard enables stakeholders to monitor key business metrics, evaluate sales channel performance, understand customer demographics, analyze policy preferences, and assess settlement trends to support data-driven decision-making.

---

## 🎯 Business Problem

Shield Insurance generates large volumes of customer, policy, and premium data through multiple sales channels. The objective was to transform this raw data into meaningful business insights and answer critical questions such as:

* Which sales channels generate the highest revenue?
* Which customer segments contribute the most revenue?
* How do customer acquisition trends change over time?
* Which cities contribute the highest customer base?
* How do settlement trends vary across age groups?

---

## 🛠 Tools & Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Power Query
* Data Modeling
* Excel / CSV Files
* MySQL
* Business Intelligence & Data Visualization

---

## 📂 Dataset Information

The project utilizes five datasets:

### Dimension Tables

#### dim_customer

Contains customer information:

* Customer Code
* Date of Birth
* City

#### dim_date

Contains date-related attributes:

* Date
* Month-Year
* Day Type
* Week Number

#### dim_policies

Contains policy information:

* Policy ID
* Base Cover Amount
* Base Premium Amount

### Fact Tables

#### fact_premiums

Contains policy sales transactions:

* Date
* Customer Code
* Policy ID
* Sales Mode
* Final Premium Amount

#### fact_settlements

Contains settlement information:

* Age
* Settlement Percentage

---

## ⭐ Data Model

A Star Schema data model was implemented using dimension and fact tables to ensure efficient report performance and accurate filtering.

### Relationships

* Customer → Premium Transactions
* Policy → Premium Transactions
* Date → Premium Transactions
* Settlement Data → Age-Based Analysis

---

## 📊 Dashboard Pages

### 1. Executive Dashboard

Provides a high-level overview of business performance through key metrics and trend analysis.

**KPIs**

* Total Revenue: ₹989.25M
* Total Customers: 26.84K
* Daily Revenue Growth: ₹13.21M
* Daily Customer Growth: 340

**Insights**

* Delhi NCR contributes the highest customer base.
* Revenue experienced significant growth during March 2023.
* Customer acquisition varies across cities and age groups.

---

### 2. Sales Mode Analysis

Analyzes customer acquisition and revenue generation across different sales channels.

**Sales Channels**

* Offline Agent
* Offline Direct
* Online App
* Online Website

**Insights**

* Offline Agent is the dominant sales channel.
* More than half of total revenue is generated through Offline Agents.
* Online channels demonstrate strong growth potential.
* Offline Direct contributes comparatively lower revenue.

---

### 3. Age Group Analysis

Examines customer demographics, policy preferences, and expected settlement amounts.

**Age Groups**

* 18–24
* 25–30
* 31–40
* 41–50
* 51–65
* 65+

**Insights**

* Customers aged 31–40 form the largest customer segment.
* Age groups 31–50 contribute the highest revenue.
* Policy preferences vary significantly among age groups.
* Older customers show higher expected settlement amounts.

---

## 🔍 Key Business Insights

### Customer Analysis

* Customers aged 31–40 represent the largest customer segment.
* The 18–24 age group contributes the lowest share of customers.

### Sales Channel Performance

* Offline Agent is the highest-performing acquisition channel.
* Online channels are steadily increasing their contribution to revenue.

### Geographic Analysis

* Delhi NCR has the largest customer base.
* Mumbai and Hyderabad are important revenue-generating markets.

### Revenue Trends

* Revenue peaked during March 2023.
* Certain customer segments consistently generate higher premium revenue.

### Settlement Analysis

* Older age groups have higher expected settlement amounts.
* Settlement trends help identify risk exposure across demographics.

---

## 📈 Skills Demonstrated

### Data Modeling

* Star Schema Design
* Relationship Management
* Fact & Dimension Modeling

### Data Transformation

* Data Cleaning
* Data Preparation using Power Query
* Date Table Integration

### DAX

* KPI Calculations
* Revenue Analysis
* Growth Metrics
* Month-over-Month Comparisons
* Dynamic Filtering

### Data Visualization

* KPI Cards
* Line Charts
* Area Charts
* Donut Charts
* Stacked Bar Charts
* Interactive Slicers

---

## 🚀 Dashboard Features

* Interactive Navigation Buttons
* Dynamic Filters and Slicers
* City-wise Analysis
* Policy-wise Analysis
* Age Group Segmentation
* Revenue Growth Tracking
* Customer Growth Monitoring
* Settlement Trend Analysis

---

## 📁 Repository Structure

```text
Shield-Insurance-Business-Insights/
│
├── Dashboard/
│   └── Shield_Insurance.pbix
│
├── Dataset/
│   ├── dim_customer.csv
│   ├── dim_date.csv
│   ├── dim_policies.csv
│   ├── fact_premiums.csv
│   └── fact_settlements.csv
│
├── Screenshots/
│   ├── Landing_Page.png
│   ├── Executive_Dashboard.png
│   ├── Sales_Mode_Analysis.png
│   └── Age_Group_Analysis.png
│
└── README.md
```

---

## 📸 Dashboard Screenshots

### Landing Page

![Landing Page](Landing_Page.png)

### Executive Dashboard

![Executive Dashboard](Screenshot(90).png)

### Sales Mode Analysis

![Sales Mode Analysis](Screenshot(91).png)

### Age Group Analysis

![Age Group Analysis](Screenshot(92).png)

---

## 🎓 Project Outcome

This dashboard provides a centralized view of insurance business performance and helps stakeholders:

* Monitor revenue growth
* Track customer acquisition
* Understand customer demographics
* Evaluate sales channel effectiveness
* Analyze policy demand patterns
* Support strategic business decisions

---

## 👨‍💻 Author

**Jay Shinde**

Aspiring Data Analyst skilled in SQL, Power BI, Excel, Python, and Data Visualization.

📧 Connect with me on LinkedIn and explore more analytics projects on my GitHub profile.
