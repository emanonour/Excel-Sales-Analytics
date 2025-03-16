
# Excel Data Analytics Project

## Description
This project analyzes sales data for a food business using Microsoft Excel. The dataset includes information about orders, products, prices, purchase types, payment methods, cities, managers, quantities, and revenue. The analysis focuses on identifying key insights such as best-selling products, total revenue, and revenue breakdown by payment method.

---

## Dataset Overview
The dataset is stored in the Excel file `Data_Original.xlsx` and contains the following sheets:

1. **Data**:
   - Contains raw sales data with columns such as:
     - `Order ID`, `Date`, `Product`, `Price`, `Purchase Type`, `Payment Method`, `City`, `Manager`, `Quantity`, and `Revenue`.
   - Revenue is calculated as `Price * Quantity`.

2. **analysis1**:
   - Provides a breakdown of revenue by product and manager.
   - Key insights:
     - **Best-selling product**: Burgers (highest revenue).
     - **Top-performing manager**: Mohamed Hafez (highest revenue contribution).

3. **analysis2**:
   - Shows the revenue distribution by payment method.
   - Key insights:
     - **Most popular payment method**: Credit Card (50.3% of total revenue).
     - **Least popular payment method**: Gift Card (20.5% of total revenue).

4. **Analysis**:
   - Lists key questions addressed in the analysis:
     1. What is our best-selling product?
     2. What is our total revenue?
     3. What is the revenue breakdown by payment method?

---

## Key Insights
1. **Best-Selling Product**:
   - **Burgers** generate the highest revenue (`$392,000.28`), followed by Fries (`$130,007.59`) and Chicken Sandwiches (`$115,139.00`).

2. **Total Revenue**:
   - The total revenue across all products is **$821,544.37**.

3. **Revenue by Payment Method**:
   - **Credit Card**: 50.3% of total revenue.
   - **Cash**: 29.2% of total revenue.
   - **Gift Card**: 20.5% of total revenue.

4. **Top-Performing Manager**:
   - **Mohamed Hafez** contributed the most to revenue (`$121,574.46` from Burgers alone).

---

## How to Use This Project
1. **Open the Excel File**:
   - Download `Data_Original.xlsx` and open it in Microsoft Excel.
   - Navigate through the sheets to explore the raw data and analysis.

2. **Review the Analysis**:
   - Check the `analysis1` sheet for product and manager performance.
   - Check the `analysis2` sheet for payment method breakdown.
   - Refer to the `Analysis` sheet for key questions and insights.

3. **Reproduce the Analysis**:
   - Use Excel formulas and pivot tables to recreate the analysis.
   - Example formulas:
     - Revenue: `=Price * Quantity`.
     - Pivot tables: Summarize data by product, manager, or payment method.

---

## Tools Used
- **Microsoft Excel**: For data cleaning, analysis, and visualization.
- **Pivot Tables**: For summarizing and analyzing large datasets.
- **Basic Excel Formulas**: For calculations (e.g., revenue).

---

## Future Improvements
- **Visualizations**: Add charts (e.g., bar charts, pie charts) to better represent the data.
- **Advanced Analysis**: Perform trend analysis over time or segment data by city or purchase type.
- **Automation**: Use Excel macros or Python scripts to automate repetitive tasks.

