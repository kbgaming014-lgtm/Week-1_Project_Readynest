# Week-1_Project_Readynest
Week-1 E-Commerce Data Analysis Project (ReadyNest) Built Using Python and SQL
# 📊 ReadyNest Week 1 – E-Commerce Sales Analysis Dashboard

## 🚀 Project Overview

This project was completed as part of the **ReadyNest Data Analytics Internship – Week 1 Task**. The objective was to perform **Data Cleaning, Exploratory Data Analysis (EDA), Statistical Analysis, and Dashboard Development** using **Python (Pandas, Matplotlib)** and **MySQL**.

The project demonstrates a complete analytics workflow — from importing raw messy data to generating business insights through interactive visualisations.

---

## 👨‍💻 Author

**Abhijay**  
B.Tech (2nd Semester)  
Chandigarh Engineering College, Jhanjeri, Mohali, Punjab, India

---

## 🎯 Project Objectives

- Load and manage data using MySQL.
- Clean and preprocess the raw e-commerce dataset.
- Perform descriptive statistical analysis.
- Conduct univariate and bivariate analysis.
- Create a multi-panel visual dashboard using Python Matplotlib.
- Generate actionable business insights from sales data.
- Present findings through a professional PDF report.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python (Pandas, Matplotlib) | Data Cleaning, EDA, Visualization |
| MySQL / SQL | Database Management & Querying |
| Microsoft Excel | Raw & Cleaned Data Storage |
| Git & GitHub | Version Control & Project Hosting |

---

## 📂 Dataset Information

The dataset contains 500 cleaned e-commerce transaction records with the following attributes:

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of transaction |
| Category | Product category (Electronics, Clothing, Furniture, Books, Sports) |
| Ship_Mode | Shipping method (Standard, Express, Same Day, Overnight) |
| Region | Geographic region (North, South, East, West) |
| Quantity | Number of units ordered |
| Sales | Total sale amount (INR) |
| Discount | Discount applied (0.0–0.3) |
| Profit | Profit earned on the order |

---

## 🧹 Data Cleaning Process

- Removed **12 duplicate records**.
- Dropped **8 rows** with missing Sales values.
- Standardised column names to snake_case.
- Verified and enforced correct data types.
- Converted Sales & Profit to float with 2 decimal precision.
- Formatted Order_Date uniformly to YYYY-MM-DD.
- Sorted dataset chronologically.
- **Final dataset: 500 records, 0 nulls, 0 duplicates.**

---

## 📈 Key KPIs

| Metric | Value |
|---|---|
| Total Sales | INR 18,29,444.63 |
| Average Sales | INR 3,658.89 |
| Total Orders | 500 |
| Total Profit | INR 4,15,404.69 |
| Profit Margin | 22.7% |

---

## 📊 EDA — Category Analysis

| Category | Total Sales (INR) | Orders | Avg Sale (INR) | % Share |
|---|---|---|---|---|
| **Electronics** | 6,86,341 | 176 | 3,899 | 37.5% |
| **Furniture** | 8,62,270 | 98 | 8,799 | 47.1% |
| **Clothing** | 1,64,026 | 130 | 1,262 | 9.0% |
| **Sports** | 91,329 | 39 | 2,342 | 5.0% |
| **Books** | 25,479 | 57 | 447 | 1.4% |

---

## 📊 Dashboard Features

✅ KPI Cards (Total Sales, Avg Sales, Total Orders, Total Profit)  
✅ Sales by Product Category (Bar Chart)  
✅ Category Revenue Contribution (Pie Chart)  
✅ Sales by Shipping Mode (Horizontal Bar)  
✅ Average Order Value by Category  
✅ Sales Distribution Histogram  
✅ Regional Sales Analysis  
✅ Filtered View — Electronics Category  

---

## 🔍 Key Business Insights

**Insight 1:** Furniture drives maximum revenue (47.1%) despite only 19.6% of order volume — highest avg order value of INR 8,799.

**Insight 2:** Electronics dominates order volume (35.2%) with 176 orders — the primary growth driver by volume.

**Insight 3:** Standard Delivery accounts for ~49% of total shipping revenue — most customers prefer economy shipping.

**Insight 4:** East region generates the highest revenue (INR 5.60 Lakh), though all four regions are relatively balanced.

**Insight 5:** Sales distribution is right-skewed — a few large Furniture orders disproportionately inflate the mean.

**Insight 6:** Books and Sports combined contribute less than 7% of revenue — high potential for targeted promotions.

**Insight 7:** Overall profit margin is a healthy 22.7%.

---

## 📸 Dashboard Preview

### Main Dashboard (4-Panel)
![Main Dashboard](Dashboard_Images/Main_Dashboard.png)

### Sales Distribution Histogram
![Histogram](Dashboard_Images/Sales_Histogram.png)

### Regional Analysis
![Region](Dashboard_Images/Region_Analysis.png)

### Filtered View — Electronics
![Electronics](Dashboard_Images/Electronics_Filter.png)

---

## 📁 Project Structure

```
ReadyNest-Week1-ECommerce-Analysis/
│
├── README.md
├── Abhijay_Week1_Report.pdf
├── Raw_ECommerce_Data.xlsx
├── Cleaned_ECommerce_Data.xlsx
└── Dashboard_Images/
    ├── Main_Dashboard.png
    ├── Sales_Histogram.png
    ├── Region_Analysis.png
    └── Electronics_Filter.png
```

---

## 🎓 Learning Outcomes

- Data Cleaning & Preprocessing
- SQL Database Management
- Python Data Analysis (Pandas)
- Data Visualisation (Matplotlib)
- Descriptive & Exploratory Statistics
- Business Insight Generation
- Professional PDF Report Writing

---

## 🔮 Future Improvements

- Sales Forecasting using Time-Series models
- RFM Customer Segmentation
- Geographic Heat-Map Visualisation
- Real-Time Dashboard Integration
- Predictive Discount Optimisation
- Automated Weekly Reporting Pipeline

---

## 📜 Conclusion

This project successfully demonstrates an end-to-end data analytics workflow. Starting from a messy raw dataset, data was cleaned, analysed, visualised, and converted into actionable business insights. Furniture and Electronics are the clear revenue leaders, while the East region shows the strongest geographic performance. The right-skewed distribution of sales highlights the outsized impact of premium product categories on total revenue.

---

⭐ *If you found this project useful, consider giving it a star on GitHub!*
