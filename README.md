# # SpaceX Launch Records Dashboard 🚀

This interactive dashboard, built using **Plotly Dash**, enables users to explore and analyze SpaceX launch records visually. Users can filter by **launch site** and **payload mass** to gain insights into launch success rates and booster performance.

## 🧠 Features

- Dropdown to select **launch site**
- Pie chart displaying:
  - Total successful launches by site (ALL)
  - Success vs. Failure per site (SPECIFIC)
- Range slider to filter **payload mass**
- Scatter plot showing:
  - Correlation between payload and mission outcome
  - Color-coded by **Booster Version**

## 📊 Dashboard Preview

![All Sites View](screenshots/dashboard_all_sites.png)
![Site Specific View](screenshots/site_specific_pie.png)
![Payload Filtered View](screenshots/payload_filtered.png)

## 📁 Project Structure

📦 spacex-dash-app/
├── spacex_launch_dash.csv
├── app.py
├── README.md
└── screenshots/
├── dashboard_all_sites.png
├── site_specific_pie.png
└── payload_filtered.png
