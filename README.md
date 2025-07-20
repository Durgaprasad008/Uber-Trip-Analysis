# 🚕 Uber Trip Analysis | Power BI Dashboard Project

## 📊 Project Overview

The **Uber Trip Analysis Dashboard** is an interactive Power BI solution built to uncover insights from Uber trip data. This project visualizes patterns in bookings, revenue, trip distance, and customer preferences to help stakeholders make data-driven decisions.

📅 **Duration:** June 2024
📁 **Data Source:** `Uber Trip Details.xlsx`
📌 **Tool Used:** Microsoft Power BI

---

## 🔍 Business Requirements

The goal is to analyze Uber ride data and:

* Identify ride booking trends
* Understand revenue generation by vehicle and payment type
* Analyze trip efficiency (distance, time, cost)
* Optimize resource allocation based on time and location trends

---

## 🧩 Dashboards Overview

### 🟦 1. Overview Analysis

> High-level metrics and insights for decision-makers

**Key KPIs:**

* ✅ Total Bookings: 103.7K
* 💰 Total Booking Value: \$1.6M
* 💳 Average Booking Value: \$15
* 🚗 Total Trip Distance: 349K miles
* 📏 Avg. Trip Distance: 3 miles
* ⏱ Avg. Trip Time: 16 minutes

**Features:**

* Total Bookings by Payment Type (Uber Pay, Cash, Wallet)
* Day vs Night trip analysis
* Vehicle Type comparison (UberX, UberXL, Green, Comfort, Black)
* Top Pickup & Drop-off locations
* Farthest Trip Distance (144.1 miles)
* Top 5 locations by booking volume
* Preferred vehicle per pickup location

### 🟨 2. Time Analysis

> Understand temporal ride patterns to improve demand forecasting

**Visualizations:**

* Area chart by Pickup Time (10-minute intervals)
* Line chart by Day Name (Mon-Sun)
* Heatmap by Hour & Day showing peak booking periods

**Dynamic Measure Selector:**

* Toggle between:

  * Total Bookings
  * Total Booking Value
  * Total Trip Distance

### 🟩 3. Details Tab

> Explore individual trip records and raw-level insights

* Detailed table with fields like Trip ID, Pickup Date, Time, Vehicle Type, Distance, Booking Value, and Location
* Drill-through functionality from charts to individual trip records
* "View Full Data" bookmark for resetting filters and exploring full dataset

---

## ⚙️ Power BI Implementation Highlights

* ✅ **Dynamic Measure Selector** using Disconnected Table
* 🎯 **Conditional Formatting** for performance indicators
* 🧭 **Slicers:** Date and City filters
* 🛠 **Bookmarks:** Drill-through to details, Reset Filters, View Full Data
* 📁 **Export Feature:** Download raw data to Excel (via Power Automate)
* 🧠 **Tooltips:** Additional insights on hover

---

## 📂 Project Structure

```plaintext
Uber-Trip-Analysis/
│
├── Dataset/
│   └── Uber Trip Details.xlsx
│
├── Screenshots/
│   ├── Screenshot-Overview.png
│   ├── Screenshot-TimeAnalysis.png
│   └── Screenshot-DetailsTab.png
│
├── Uber_Trip_Analysis_Report.pbix (optional if sharing PBIX)
│
└── README.md
```
