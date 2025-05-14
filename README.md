# walmart-sales-dashboard

# 📊 Interactive Sales Performance Dashboard

This project is an **interactive data visualization dashboard** built using **HTML**, **JavaScript**, and **Plotly.js**. It allows users to **upload sales data in JSON format** and dynamically generates insightful visualizations to analyze sales trends and external influencing factors.

## 🔍 Features

- 📁 Upload your own **JSON sales data file**
- 📈 Dynamic plotting of:
  - Weekly Sales Over Time (Line Chart)
  - Holiday vs Non-Holiday Sales (Box Plot)
  - Temperature vs Sales (Scatter Plot)
  - Multi-axis comparison of Sales, Fuel Price & CPI (Multi-Line Chart)
  - Bubble Chart showing Unemployment vs Sales with CPI-based size


## 🖼️ Dashboard Preview

![Screenshot 2025-05-14 181049](https://github.com/user-attachments/assets/7dcc11a2-5d90-44c8-b014-a15f85a74f4c)


## 📂 Sample JSON Format

Ensure your uploaded JSON file follows this structure:

```json
[
  {
    "Store": 1,
    "Date": "05-02-2010",
    "Weekly_Sales": 1643690.9,
    "Holiday_Flag": 0,
    "Temperature": 42.31,
    "Fuel_Price": 2.572,
    "CPI": 211.0963582,
    "Unemployment": 8.106
  },
  ...
]
