# 📊 SuperStore Sales Dashboard & Analytics

## 📌 Overview

This repository contains an interactive **Power BI Dashboard** developed for analyzing retail sales data from the **SuperStore** dataset. The project provides an end-to-end analytical view of sales performance, profitability, customer demographics, shipping logistics, and predictive sales forecasting.

---

## 📈 High-Level Metrics (KPI Overview)

* **Total Sales:** $1.57M
* **Total Units Sold:** 22K
* **Total Profit:** $175.26K
* **Average Delivery Time:** 3.93 Days

---

## 🔍 Key Insights & Analytical Breakdown

### 1. 💳 Payment Mode Preference
* **Cash on Delivery (COD)** dominates payment choices at **42.62%**.
* **Online Payments** represent **35.38%** of transactions.
* **Cards** account for **21.99%** of total sales.

### 2. 👥 Customer Segment & Regional Distribution
* **Segment Breakdown:** **Consumer** is the largest revenue driver at **48.09%**, followed by **Corporate (32.55%)** and **Home Office (19.35%)**.
* **Regional Performance:** The **West Region** leads with **33.37%** of sales, followed by **East (28.75%)**, **Central (21.78%)**, and **South (16.10%)**.
* **Top States:** **California** leads state sales by a wide margin (~$0.33M), followed by **New York** (~$0.19M) and **Texas** (~$0.13M).

### 3. 📦 Category & Shipping Insights
* **Top Product Category:** **Office Supplies** generates the highest sales ($0.64M), closely followed by **Technology** ($0.47M) and **Furniture** ($0.45M).
* **Top Sub-Categories:** **Phones** ($0.20M), **Chairs** ($0.18M), and **Binders** ($0.17M) are the top revenue generators.
* **Shipping Preference:** **Standard Class** is overwhelmingly preferred ($0.91M), compared to Second Class ($0.31M), First Class ($0.24M), and Same Day ($0.10M).

### 4. 📅 Historical Growth & Forecasting
* **YoY Performance (2019 vs. 2020):** Both monthly sales and profit show substantial growth in 2020 compared to 2019 across almost every month.
* **Seasonal Surge:** Significant spikes in both revenue and profit occur in Q4, particularly during **November and December**.
* **Predictive Analysis:** Time-series forecasting indicates stable baseline demand heading into early 2021 with seasonal fluctuations accounted for in the confidence bounds.

---

## 📁 Repository Structure

```
├── Data/
│   └── Superstore_Dataset.xlsx      # Raw Excel dataset
├── Visualizations/
│   ├── dashboard_page1.png          # Main Overview Page
│   └── dashboard_page2.png          # Forecasting & State Analysis
├── SuperStore_Sales_Dashboard.pbix  # Power BI Project File
└── README.md                        # Documentation
```

---

## 🛠️ Tools & Technologies

* **Data Source:** Microsoft Excel (`.xlsx`)
* **ETL & Data Cleaning:** Power Query
* **Analytics & DAX:** Power BI Desktop
* **Geospatial & Predictive Modeling:** Shape Maps & Time Series Forecasting

---

## 🚀 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/superstore-sales-dashboard.git
   ```
2. **Open in Power BI Desktop:**
   * Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
   * Open `SuperStore_Sales_Dashboard.pbix`.
   * Update the data source path to `Data/Superstore_Dataset.xlsx` if prompted under **Transform Data > Data Source Settings**.

---

## 💡 Key Recommendations

1. **Leverage Q4 Demand:** Prepare inventory and promotional campaigns ahead of November and December, where revenue and profitability peak significantly.
2. **Expand West & East Dominance:** Focus marketing strategies in top-performing states like **California** and **New York** while addressing underperforming southern regions.
3. **Optimize Logistics:** Encourage faster shipping modes (like First Class or Same Day) for high-value Technology items, as Standard Class currently accounts for the vast majority of volume.

---

## 👤 Author

* **GitHub:** [@your-username](https://github.com/your-username)
* **LinkedIn:** [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

*⭐ Feel free to star this repository if you found it helpful!*