# Project Proposal (Updated Summary Version)

## Important Note

This document is **not the original project proposal**.  
The original proposal was submitted by email and validated during an in-class discussion with the teaching assistant Anna Smirnova.  
This version summarizes the project and reflects its final scope.

---

## Project Title
**Inventory Tracker with Dynamic Reorder Alerts and Demand Forecasting**

## Category
**Database Applications**

---

## Proposal

This project aims to develop a **Python-based inventory tracking system** designed to manage stock levels, detect shortages and support reorder decisions through data analysis and visualization.

The system loads product and sales data from CSV files, including stock quantities, reorder thresholds and product details. Using the `pandas` library, inventory levels are analyzed and each product is classified into three status zones: **Green** (sufficient stock), **Orange** (low stock requiring user confirmation) and **Red** (critical stock requiring immediate action).

In addition to inventory tracking, the project integrates **machine learning-based demand forecasting**. Tree-based models such as **Random Forest**, **LSTM** and **XGBoost** are used to predict future demand from historical sales data. These predictions allow the system to anticipate demand trends and adjust reorder quantities dynamically.

The application also provides **visual dashboards** using `matplotlib` or `seaborn`, displaying inventory status and demand trends in a clear and actionable format. User interaction is simulated for medium-risk inventory items, reflecting real-world decision-making.

The project’s success is evaluated based on accurate inventory classification, reliable demand prediction and the clarity of the generated visualizations.

