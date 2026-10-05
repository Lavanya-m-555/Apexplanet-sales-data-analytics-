# Sales Data Analysis - ApexPlanet Internship

This repository contains my data analytics project for the ApexPlanet internship. The goal was to take a raw sales dataset of 1,000 orders, clean up data quality issues, and analyze overall sales performance across product categories, locations, and customer age groups.

---

## What Was Done

1. **Data Cleaning & Fixes:**
   * Checked for blank and inconsistent values across all columns.
   * Filled missing age entries to keep demographic records complete.
   * Handled 13 missing/zero city values by marking them as `Unknown` so total sales revenue remained accurate without altering actual city data.
   * Standardized all dates into a uniform format (`YYYY-MM-DD`).

2. **Customer Segmentation:**
   * Grouped customer ages into four standard age brackets (`Gen Z`, `Young Adult`, `Middle-Aged`, `Senior`) to analyze buying patterns.

3. **Data Analysis & Visualization:**
   * Built summary pivot tables to calculate Total Revenue, Total Quantity Sold, and Average Order Value (AOV).
   * Created visual charts (Pie Chart for Category Sales and Bar Chart for City Sales) to highlight revenue drivers.

---

## Key Takeaways

* **Total Sales Revenue:** ~₹13.94 Crore across 1,000 orders.
* **Top Category:** **Electronics** brought in the highest revenue (over ₹5.07 Crore), making up more than a third of total business sales.
* **Top Regions:** **Patna**, **Kolkata**, and **Bengaluru** were the leading cities by sales revenue.
* **Main Demographics:** **Middle-Aged (41–55)** and **Young Adult (26–40)** buyers accounted for the vast majority of total purchases.

---

## Repository Files

* `ApexPlanet_DataAnalytics_Dataset.xlsx` - Raw dataset
* `Final_Cleaned_Dataset.xlsx` - Processed dataset with clean metrics and charts
* `README.md` - Project documentation
