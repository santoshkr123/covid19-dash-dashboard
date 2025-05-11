

📊 COVID-19 Data Dashboard using Dash & Plotly
🧠 Project Overview
This project is an interactive data dashboard built using Dash and Plotly that visualizes real-time insights from state-wise COVID-19 data in India. It allows users to explore trends across cases, recoveries, deaths, and medical commodity demands like masks and oxygen. The app provides a clean, responsive interface for both public health stakeholders and general users to understand the impact and management of the pandemic.

🎯 Objectives
Display key COVID-19 metrics: total, active, recovered, and deceased cases.

Enable dynamic exploration of data by state, case type, or commodity.

Visualize zone-level classifications (Red, Green, Orange, Blue) with pie charts.

Provide a simple yet powerful tool for pandemic data awareness.

🛠️ Technologies Used
Python – for data manipulation and logic

Pandas – to load and filter CSV data

Dash – to create the web app and UI components

Plotly – for creating rich, interactive visualizations

Bootstrap (via CDN) – for layout styling and responsiveness

📁 Dataset
The dashboard is powered by a CSV file (state_wise_daily data file IHHPET.csv) containing daily COVID-19 updates for each state, including:

Epidemiological Data: Confirmed, Recovered, Deceased, Hospitalised

Medical Supplies: Mask, Sanitizer, Oxygen

Geographical Zones: Red, Green, Orange, Blue

🧩 Key Features
✅ Summary Cards
Displays Total, Active, Recovered, and Deceased counts.

Uses color-coded Bootstrap cards for better visual appeal.

📊 Bar Charts (State-wise)
Users can filter by case type (All, Hospitalised, Recovered, Deceased).

Displays bar plots of counts per state.

📈 Line Graphs (Commodity Usage)
Select commodities (Mask, Sanitizer, Oxygen) or all combined.

Shows trend lines of demand or availability over time.

🥧 Pie Chart (Zone or Status Analysis)
Analyze the distribution of states/zones based on selected categories.

Dynamic updates based on dropdown selection.

💡 What I Learned
Building scalable Dash applications with multiple callbacks.

Managing layout and responsiveness using Bootstrap grid system.

Integrating Plotly for interactive and real-time chart updates.

Error handling in data-driven web apps (e.g., missing values or inconsistent column names).

