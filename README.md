# ✈️ Airlines Dashboard – Power BI Project

This project is the final dashboard I created as part of the **Power BI course at the Information Technology Institute (ITI)**. The goal was to analyze flight data and deliver clear, actionable insights using professional data modeling and visualization techniques.

---

## 📊 Dashboard Pages Overview

### 🟢 Page 1: Flight Punctuality Overview

This page provides a general view of how flights perform in terms of timing:

- **KPIs** showing counts of:
  - Total Flights
  - Early Arrivals
  - On-Time Arrivals
  - Delayed Arrivals
- **Bar Charts**:
  - Flight arrival status by month
  - Airline performance comparison
- **Filters**:
  - By Month

💡 **Insight:** Helps identify which airlines are consistently on time and which periods see the most delays.

---

### 🔴 Page 2: Cancellations & Diversions Analysis

This page focuses on understanding irregular flight outcomes:

- **KPIs** for:
  - Cancelled Flights
  - Diverted Flights
- **Line Chart**:
  - Monthly trend of cancellations and diversions
- **Bar Chart**:
  - Distribution by airline or reason
- **Slicers**:
  - Filter by month

💡 **Insight:** Highlights seasonal patterns and possible operational issues with specific airlines or routes.

---

## 🗂️ Data Model

The dashboard is built using a **Star Schema** that ensures performance and simplicity.

### 📐 Model Components:

- **Fact Table:** `Flights`
  - Contains flight records and measures (e.g., status, delay time)
- **Dimension Tables:**
  - `Date` – For date-based filtering and trends
  - `Time` – For time-based filtering and trends
  - `Location` – Source and destination airport details
  - `Carrier` – Carrier details

🔗 All dimensions are related to the fact table via surrogate keys.

💡 **Benefit:** This model supports efficient filtering, slicing, and drilling down across different dashboard visuals.

---

## ✅ Skills Applied

- Power BI Dashboard Design
- Star Schema Data Modeling
- DAX Calculations & Measures
- KPI Creation
- Drill-down and Filtering
- Visual storytelling with data
- Bookmarks

---

## 📸 Screenshots

> ![Page 1 - Flight Punctuality](https://github.com/eslam556/Airline-Dashboard/blob/main/Page%201.jpg)
> *Page 1: Overview of flight punctuality metrics.*

> ![Page 2 - Disruptions](https://github.com/eslam556/Airline-Dashboard/blob/main/Page%202.jpg)
> *Page 2: Overview of cancelled and diverted flights.*

> ![Data Model](https://github.com/eslam556/Airline-Dashboard/blob/main/Data%20Model.jpg)
> *Power BI Star Schema Data Model.*
