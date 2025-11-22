## 📊SwiftCart E-Commerce Sales Dashboard
An interactive Power BI dashboard built to analyze e-commerce sales, profit, customer behavior, and category-wise performance.
This dashboard provides business insights using two CSV datasets, DAX calculations, and well-designed visuals.

## 🔧 Tools & Technologies:
- Power BI Desktop
- Power Query (for cleaning & transformations)
- DAX (Data Analysis Expressions)
- CSV Data Files

## 🔍 Data Cleaning & Transformations:
- Removed duplicates
- Standardized column names
- Handled missing values
- Corrected data types
- Built relationships between the two tables
- Created calculated columns

##🧮 DAX Calculations Used:
Total Amount = SUM(Orders[Amount])
Total Quantity = SUM(Orders[Quantity])
Total Profit = SUM(Orders[Profit])
AOV = DIVIDE([Total Amount], [Total Quantity])
Profit by Month = CALCULATE([Total Profit], ALLEXCEPT(Orders, Orders[Month]))

<img width="1430" height="799" alt="Snapshot Of Dashboard" src="https://github.com/user-attachments/assets/11252b98-117c-48c3-b57e-d0a16d7b8712" />

