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
![Screenshot 2025-05-14 181059](https://github.com/user-attachments/assets/d4123e60-eda7-4afe-830d-2fe343bbdaa3)
![Screenshot 2025-05-14 181105](https://github.com/user-attachments/assets/a0297db1-22a6-4f31-9769-f79e0b4a16b3)


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

🚀 Getting Started:-
Download the project files (HTML file).
Open the sales_dashboard_glassmorphism.html file in any modern browser.
Click the file upload input to select your local JSON data file.
Visualizations will automatically be generated.

🛠️ Technologies Used:-
HTML5 for structure
JavaScript for dynamic file handling and logic
Plotly.js (latest CDN) for visualizations
CSS with glassmorphism design principles

📌 Use Cases:-
Business analytics for retail sales
Identifying seasonal trends and external influences
Comparing economic indicators with sales performance
