# 🚖 Uber Trip Analysis Dashboard (Power BI)

This project presents an **interactive Power BI dashboard** that analyses Uber trip data to uncover insights about **ride demand, revenue trends, trip efficiency, vehicle usage, and location patterns**.

The dashboard enables stakeholders to make **data-driven decisions** using dynamic measures, interactive filters, and detailed visual analytics.

---

# 📊 Project Objective

The goal of this project is to analyse Uber trip data and provide insights into:

- Ride booking trends
- Revenue generation
- Trip efficiency
- Vehicle demand
- Location-based ride patterns
- Time-based ride demand

This helps improve **operational planning, pricing strategies, and driver allocation**.

---

# 🧩 Dashboards Overview

The Power BI solution contains **3 interactive dashboards**.

---

# 1️⃣ Overview Analysis Dashboard

This dashboard provides a **high-level summary of Uber trip performance**.

### Key KPIs

- **Total Bookings** – Total number of trips
- **Total Booking Value** – Total revenue generated
- **Average Booking Value** – Average revenue per trip
- **Total Trip Distance** – Total miles covered
- **Average Trip Distance** – Average trip distance
- **Average Trip Time** – Average trip duration

### Visualizations

- Total Trip Distance by **Payment Type**
- Total Trip Distance by **Trip Type (Day / Night)**
- **Total Bookings by Day**
- **Vehicle Type Analysis**
- **Location Analysis**

### Location Insights

- Most Frequent Pickup Point
- Most Frequent Drop-off Point
- Farthest Trip
- Top 5 Locations by Total Bookings
- Most Preferred Vehicle for Pickup Location

### Additional Features

- Dynamic measure selector
- Dynamic titles
- Interactive slicers
- Tooltips with additional insights
- Conditional formatting for KPIs

---

# 2️⃣ Time Analysis Dashboard

This dashboard focuses on **trip demand patterns based on time**.

### Global Dynamic Measure

Users can switch between:

- Total Bookings
- Total Booking Value
- Total Trip Distance

All visuals update dynamically based on the selected metric.

### Visualizations

**1. Bookings by Pickup Time**

- Area chart
- Groups trips into **10-minute intervals**

**2. Bookings by Day Name**

- Line chart
- Shows demand across **Monday – Sunday**

**3. Booking Heatmap**

Matrix grid showing:

- Rows → Hours (0–23)
- Columns → Days (Mon–Sun)
- Values → Selected dynamic measure

This highlights **peak booking hours and days**.

---

# 3️⃣ Details Dashboard

This tab provides **granular trip-level data** for deeper analysis.

### Features

- Detailed **grid table**
- Displays trip-level data such as:

  - Trip ID
  - Pickup Date
  - Pickup Hour
  - Vehicle Type
  - Payment Type
  - Passenger Count
  - Trip Distance
  - Booking Value
  - Pickup Location

### Drill-Through Capability

Users can:

- Right-click any visual
- Drill through to see **underlying trip records**

### Bookmark Features

- View Full Dataset
- Toggle filtered vs complete data

---

# 🛠 Power BI Features Used

This project demonstrates multiple advanced Power BI techniques:

- Data Modeling
- Relationships (Active & Inactive)
- DAX Measures
- Dynamic Measure Selection
- Disconnected Tables
- Bookmarks
- Drill-through
- Conditional Formatting
- Interactive Slicers
- Dynamic Titles
- Matrix Heatmaps

---

# 📂 Project Structure
