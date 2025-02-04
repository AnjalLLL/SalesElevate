# SalesElevate
# Sales Insights Dashboard (Power BI)

## 📌 Project Overview
This project involves building a **Sales Insights Dashboard** using **Power BI** to analyze sales performance. The raw data is stored in **SQL**, and data cleaning was performed to ensure accuracy and consistency before visualization.

## 🔍 Data Cleaning Process
Before creating the dashboard, data cleaning was performed with the following steps:
- **Filtering Negative Sales Values**: Removed negative values from the `Sales Amount` column in the `Sales Transactions` table.
- **Handling Duplicate Currency Names**: Identified and removed duplicate currency names to maintain data integrity.
- **Currency Standardization**: Converted all `USD` values to `INR` to maintain consistency in currency analysis.

## 📊 Dashboard Features
The Sales Insights Dashboard includes:
- **Total Revenue**: ₹142.22M
- **Total Sales Quantity**: 350K
- **Revenue by Product Type**: Breakdown of revenue for Own Brand and Distribution.
- **Yearly Sales Performance**: Analysis from 2017 to 2020.
- **Monthly Revenue Trends**: Visualization of revenue fluctuations across months.
- **Revenue by Zone**:
  - North: ₹99.57M
  - Central: ₹36.1M
  - South: ₹6.56M
- **Detailed Time-Based Analysis**: Revenue trends by year, quarter, month, and day.

## ⚙️ Tech Stack
- **Power BI**: For data visualization and dashboard creation.
- **SQL**: For data storage, cleaning, and transformations.


## 🚀 How to Use
1. Load the cleaned sales dataset into **Power BI**.
2. Connect to the **SQL database** if needed for real-time analysis.
3. Explore the **Sales Insights Dashboard** to analyze sales trends and patterns.

## 📎 Project Files
- `db_dump.sql` – SQL file containing the raw sales dataset.
- `sales insights dashboard.pdf` – Sales Insights Dashboard in pdf file.
- `sales_insights.pbix` – Power BI file containing the final dashboard.
- `README.md` – This documentation file.

## 📢 Future Improvements
- Adding **predictive analytics** to forecast future sales trends.
- Integrating **automated data refresh** for real-time insights.
- Enhancing **interactivity** with drill-through features and advanced filters.




