## Partnership
This project is a collaboration with **Montgomery County Alcohol Beverage Services (ABS)**.

## Data Description
ABS provided datasets containing the **top 500 products by total quantity sold** for the calendar year 2024. The data includes **weekly sales figures (52 weeks)** across all store types.

## Project Objective
The main objective is to determine appropriate **reorder point** and **safety stock** values for the top 500 best-selling products to enhance inventory planning and reduce the risk of stockouts.

## 🏬 Store Categories
- **High Volume Store**: Over $8 in annual revenue, restocked **twice per week**
- **Medium Volume Store**: $6-8M in annual revenue, restocked **once per week**
- **Low Volume Store**: Under $6M in annual revenue, restocked **once per week**

## 📈 Reorder Point Calculation
ABS’s formula for reorder point is:

**Reorder Point = Daily Average Sales × Lead Time**

This calculation provides a baseline for expected demand.

## 📅 Seasonal Grouping
Sales data is grouped by **quarter** to capture **seasonal demand trends** in alcohol sales. This allows for more responsive and accurate inventory planning.

## 🛡️ Safety Stock Strategy
Safety stock is added on top of the reorder point to:
- Account for **demand variability**
- Mitigate **delivery delays**
- Provide a **buffer** during peak periods
