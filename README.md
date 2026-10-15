# E-commerce Sales Analysis using Power BI

## 📌 Project Overview

This project focuses on analyzing e-commerce sales data using Microsoft Power BI. The dashboard provides insights into sales performance, customer behavior, product performance, and geographical sales distribution.

The goal is to transform raw data into meaningful insights through interactive visualizations and key performance indicators (KPIs), helping businesses make data-driven decisions.

## 🎯 Project Objectives

- Analyze overall sales and revenue performance.
- Identify monthly and yearly sales trends.
- Understand customer purchasing behavior.
- Analyze returning customers and customer distribution.
- Identify top-performing products and units.
- Compare sales performance across different store locations.
- Track year-over-year changes in key business metrics.

## 🛠️ Tools and Technologies

- **Microsoft Power BI Desktop** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Measures and business calculations.
- **Data Modeling** – Connecting multiple tables for analysis.
- **CSV Files** – Source datasets.

## 📊 Dashboard Preview

### 1. Year-Wise Sales Analysis

This dashboard provides an overview of sales performance, including revenue, quantity sold, average unit price, monthly sales trends, and geographical sales distribution.

![Year Wise Sales Analysis](Screenshots/Year%20Wise%20Sales%20Analysis.png)

### 2. Customer and Product Insights

This dashboard focuses on customer metrics, returning customers, order distribution, product performance, and sales trends across different time periods and locations.

![Customer and Product Insights](Screenshots/Customer%20and%20Product%20Insights.png)

## 📈 Key Performance Indicators (KPIs)

The dashboard includes the following metrics:

- **Total Revenue:** Approximately 105.40M
- **Total Quantity Sold:** Approximately 6M
- **Average Unit Price:** 17.56
- **Total Customers:** Approximately 9K
- **Year-over-Year Performance:** Comparison of selected business metrics across years.
- **Top-Selling Units:** Identification of units with the highest quantities sold.

*Note: The displayed values are based on the supplied dashboard screenshots and may change when filters or slicers are applied.*

## 🔍 Analysis Performed

### Sales Analysis
- Analyzed monthly and yearly sales trends.
- Evaluated overall revenue and quantity sold.
- Compared business performance across time periods.

### Customer Analysis
- Examined customer counts and returning-customer metrics.
- Analyzed customer purchasing behavior.
- Explored customer and order distribution.

### Product Analysis
- Evaluated product-level performance.
- Compared quantities sold across products.
- Identified top-performing items.

### Geographical Analysis
- Analyzed sales across different store locations.
- Compared regional performance using geographical visualizations.

### Time-Based Analysis
- Evaluated monthly and yearly trends.
- Compared selected metrics across years.

## 🗂️ Dataset Description

The project uses multiple CSV files representing different parts of the e-commerce data model.

| Dataset | Description |
|---|---|
| `fact_table.csv` | Transaction-level sales data, including quantity and price information. |
| `customer_dim.csv` | Customer-related information. |
| `item_dim.csv` | Product and item details. |
| `store_dim.csv` | Store and geographical information. |
| `time_dim.csv` | Date and time attributes for time-based analysis. |
| `Trans_dim.csv` | Transaction-related details, including transaction type and bank information. |

These datasets are used together to analyze sales performance from different business perspectives.

## 🧮 Data Modeling and DAX

The project uses a data model that combines transaction data with customer, product, store, time, and transaction-related tables.

DAX can be used to calculate metrics such as:

- Total Revenue
- Total Quantity Sold
- Average Unit Price
- Customer Count
- Returning Customer Count
- Year-over-Year Growth

The exact calculations depend on the measures implemented in the Power BI report.

## 💡 Business Value

This analysis can help businesses:

- Monitor sales performance.
- Identify customer purchasing patterns.
- Understand product performance.
- Recognize high-performing store locations.
- Track changes in business performance over time.
- Make informed decisions based on data.

## 🚀 How to Use the Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open `Ecommerce.pbix` in Power BI Desktop.
4. If prompted, configure the data source paths to match the location of the CSV files.
5. Refresh the data if required.
6. Use the available slicers, filters, and visualizations to explore the report.

## 📁 Project Structure

```text
Ecommerce/
│
├── README.md
├── Ecommerce.pbix
├── fact_table.csv
├── customer_dim.csv
├── item_dim.csv
├── store_dim.csv
├── time_dim.csv
├── Trans_dim.csv
│
└── Screenshots/
    ├── Year Wise Sales Analysis.png
    └── Customer and Product Insights.png
```

## 🔒 Data Privacy

Before publishing this repository publicly, ensure that the datasets and Power BI report do not contain sensitive or personally identifiable information.

Review fields such as contact numbers and identification numbers. Remove or anonymize sensitive information before sharing the files publicly.

## 👨‍💻 Author

**Name:** Your Name

- **GitHub:** Add your GitHub profile
- **LinkedIn:** Add your LinkedIn profile

---

⭐ If you find this project useful, feel free to explore the repository and its dashboard screenshots.