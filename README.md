# 🧾 Retail Product Returns Analysis — Power BI Project

## 🧩 Problem Statement

A retail company has observed a growing volume of product returns, which is negatively affecting logistics and profit margins. As part of the analytics team, your role is to analyze return behaviors across products, customers, and regions.

Your analysis will support the executive team in identifying root causes, improving customer satisfaction, and reshaping return policies.

---

## 🎯 Objective

To investigate patterns in product returns and uncover:

- Return frequency by product, category, and region
- Customer behavior and segment-specific return rates
- The relationship between discounts and returns
- Sales vs. returns trends over time

The goal is to generate **actionable recommendations** that improve profitability and operational efficiency.

---

## 🗃️ Dataset Overview

- **Source**: [Superstore Dataset (Kaggle / Tableau Sample Data)]
- **Period Covered**: 2014 – 2017
- **Key Fields Used**:
  - `Order ID`, `Product Name`, `Category`, `Sub-Category`
  - `Sales`, `Quantity`, `Discount`, `Region`, `City`
  - `Customer Name`, `Segment`
  - `Returned Flag` (Boolean)
  - `Order Date`, `Ship Date`

---

## 📊 Dashboard Preview

![Retail Returns Dashboard](images/dashboard_page1.png)(images/dashboard_page2.png)


---

## 🧮 Key Metrics Calculated (SQL)

| KPI                    | Description                                      |
|------------------------|--------------------------------------------------|
| `Order Return Rate (%)`| % of returned orders out of total orders         |
| `Product Return Rate`  | Return rate based on product frequency           |
| `Quantity Return Rate` | Ratio of returned quantity vs. total quantity    |
| `MoM Revenue Growth`   | Month-over-month revenue changes                 |
| `MoM Return Growth`    | Month-over-month changes in returns              |
| `Discount Frequency`   | % of discounted orders per region or segment     |
| `Avg Delivery Time`    | Shipping time per order                          |

---

## 🧪 Tools & Technologies

- **SQL**: Data cleaning, transformation, and KPI calculation
- **Power BI**: Dashboard creation, drill-downs, and executive summary visuals
- **Excel**: Initial data exploration and structure

---

## 📊 Dashboard Highlights (Power BI)

### Key Insights:

- 📈 **MoM Revenue Increased** while return rate declined — a strong positive trend
- 🧴 **8+ products** had a 100% return rate — clear product quality/fit issues
- 🏙️ **Detroit, Jacksonville, and Springfield** had the highest return rates (400%+)
- 🧑‍💼 **Home Office** segment saw the **highest return rates** of all customer segments
- 💸 **Discount-heavy regions** showed higher return rates — especially in the West
- ⏱️ Average delivery time close to 4 days — acceptable but can be optimized

### Dashboard Sections:

- **Overview KPIs**: Order Return Rate, Product Return Rate, Quantity Return Rate
- **Product-Level Analysis**: Most returned items
- **Region & City Maps**: Geo-spatial return trends
- **Customer Segments**: Behavior patterns
- **Discount vs. Return Correlation**
- **Month-on-Month Trends**

---

## 📌 Recommendations

1. **Product Rationalization**: Review and potentially discontinue high-return products.
2. **Discount Policy Review**: Targeted discounts over blanket promotions to prevent impulsive purchases.
3. **Vendor/City Audits**: Prioritize operational audits in Detroit, Jacksonville, and Springfield.
4. **Customer Experience**: Improve product descriptions, delivery accuracy, and after-sales service.
5. **Logistics Optimization**: Optimize delivery for Home Office customers, who may have stricter expectations.

---


## 📁 Folder Structure

