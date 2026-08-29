# inventory-optimization-dashboard
E-Commerce Inventory Tracker &amp; Stockout Forecasting Analysis built using Google Sheets / MS Excel.
# 📦 E-Commerce Inventory Optimization & Stockout Forecasting Dashboard

## 📌 Project Overview
This project focuses on inventory control and supply chain analysis for an E-Commerce operations framework. Using Google Sheets / MS Excel, dynamic data-driven formulas were built to calculate safety stock thresholds, trigger reorder points (ROP), and flag real-time stockout risks across multiple product SKUs.

The objective is to minimize holding costs while ensuring zero order fulfillment delays caused by stockouts.

---

## 🛠️ Key Features & Operational Metrics

* **Safety Stock Modeling:** Calculated custom buffer inventory levels using daily demand metrics to absorb sales spikes (`Daily_Sales * 2`).
* **Reorder Point (ROP) Trigger:** Automated reordering indicators combining lead times and safety stock (`(Daily_Sales * Lead_Time) + Safety_Stock`).
* **Dynamic Stock Alerts:** Automated 3-level alert status (`Critical Stockout`, `Reorder Now`, `Sufficient`) using nested `IF` logic.
* **Interactive Dashboard:** Integrated **Pie Charts** for status distribution and dynamic **Slicers** for category-wise filtering (`Electronics`, `Fashion`, `Home & Kitchen`).

---

## 📊 Key Findings & Insights

Based on the analysis of 20+ product SKUs:
* 🔴 **55% Critical Stockout:** Over half of the active SKUs breached their safety stock levels, requiring urgent vendor replenishment.
* 🟡 **45% Reorder Now:** Remaining inventory hit the ROP threshold, highlighting active lead-time dependency.
* 🟢 **0% Sufficient Stock:** Identified zero overstocking risks, pointing toward potential vendor delays across all categories.

---

## 🛠️ Tech Stack & Tools Used
* **Spreadsheet Software:** Google Sheets / MS Excel
* **Excel Skills Used:** `SUMPRODUCT`, `COUNTIF`, `IF` logic, Nested Formulas, Pivot Tables, Dynamic Charts, Slicers
* **Domain Focus:** Supply Chain Management, Inventory Control, SLA Management, Warehouse Operations

---

## 📁 Repository Structure
```text
├── Data/
│   └── Inventory_Optimization_Dataset.csv
├── Dashboard/
│   └── Inventory_Optimization_Dashboard.pdf
└── README.md
