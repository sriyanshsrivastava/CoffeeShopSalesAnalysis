# Coffee Shop Sales Analysis Project

## Overview
This project involved creating an interactive sales dashboard for a coffee shop using Microsoft Excel's Power Query and Pivot Tables. The objective was to analyze transactional data, identify trends, and provide actionable insights for decision-making.

---

## Tools and Technologies Used
- **Microsoft Excel**: Data cleaning, transformation, and dashboard creation.
- **Power Query**: For data extraction, transformation, and loading (ETL) processes.
- **Pivot Tables**: For aggregating and summarizing data for visualizations.

---

## Data Cleaning and Transformation
1. **Data Loading**:
   - Imported transaction data into Power Query for preprocessing.

2. **Transformations**:
   - Extracted a new column `Size` from `product_details` to categorize sizes (e.g., `Sm` as `Small`, `Lg` as `Large`, etc.).
   - Created a new column `Total_Bill` by multiplying `transition_qty` and `unit_price`.
   - Modified the `transection_time` column to remove the incorrect date, retaining only time values.
   - Extracted `Month`, `Weekdays`, and `Hours` for temporal analysis from `transection_date` and `transection_time`.
   - Extracted numeric representations of weekdays and months for sequence-based sorting.

---

## Dashboard Features
### Key Metrics:
- **Total Sales**: $12,742.52
- **Total Footfall**: 2,725
- **Average Bill/Person**: ₹4.68
- **Average Orders/Person**: 1.45

### Visualizations:
1. **Hourly Sales Trend**:
   - Line chart showing sales patterns by hour to identify peak and off-peak times.
2. **Category-wise Sales Distribution**:
   - Pie chart showing sales contribution by product categories (e.g., Coffee: 39%, Bakery: 29%).
3. **Sales by Size**:
   - Donut chart illustrating sales distribution by cup sizes (e.g., Small, Regular, Large).
4. **Footfall Analysis**:
   - Line chart showing footfall trends by weekdays.
5. **Top-Selling Products**:
   - Bar chart highlighting the top 5 products based on total revenue.
6. **Store Location Analysis**:
   - Bar chart showing footfall distribution across store locations (e.g., Astoria, Lower Manhattan).

---

## Findings
1. **Peak Hour Analysis**:
   - Sales peaked between 9 AM and 12 PM, indicating high morning demand.
2. **Product Categories**:
   - Coffee accounted for the largest share of sales (39%), followed by Bakery items (29%).
3. **Top Products**:
   - The best-selling product was Barista Espresso ($1,730.80), followed by Brewed Chai Tea.
4. **Location Insights**:
   - Astoria had the highest footfall (963 customers).

---

## Future Scope
- **Automation**:
  - Implement macros or VBA for real-time updates.
- **Scalability**:
  - Integrate with Power BI or Tableau for enhanced interactivity.
- **Data Sources**:
  - Connect directly to databases for live data feeds.
- **Additional Metrics**:
  - Include customer demographics and loyalty program analysis.

---

## How to Access the Dashboard
1. Download the Excel file from this repository.
2. Open the file in Microsoft Excel (2016 or later).
3. Navigate to the "Dashboard" tab to view the visualizations.

---

## Repository Structure
```
|-- Coffee_Shop_Sales_Analysis
    |-- Data
        |-- Coffee Shop Sales.xlsx
    |-- Dashboard
        |-- Coffee Sales Data Analysis and Dashboard.xlsx
    |-- Documentation
        |-- README.md
```

---

Feel free to reach out for collaboration or suggestions on this project!

