# Warehouse Restock Predictions

https://purribd8.github.io/warehouse_predictions/dashboard.html (See dashboard here)

This project is an interactive web-based dashboard designed to visualize demand forecasts for warehouse inventory items. Built using HTML, JavaScript (Chart.js + PapaParse), and CSV-based time series data, it allows users to:

Select from 10 different inventory items

View weekly forecasted demand

Display upper and lower confidence intervals

Easily interpret predictive trends for planning and procurement

The forecast data was generated using Facebook's Prophet model and exported into structured CSV summaries. This tool is ideal for analysts, operations managers, or inventory teams seeking to make data-driven stocking decisions.

🔧 Tech Stack
Chart.js for line graph visualization

PapaParse for fast CSV parsing in-browser

Prophet (Python) for time series forecasting (modeling done separately)

Fully client-side HTML/JS — no backend required

🚀 Possible Enhancements
Filter by date range

Add aggregate trends across all items

Enable CSV export of visual data

Embed into internal enterprise dashboards
