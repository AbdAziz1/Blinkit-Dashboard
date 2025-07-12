#  Blinkit Dashboard

This report documents the complete pipeline used to develop the interactive Power BI dashboard for **Blinkit – India’s Last Minute App**. The dashboard visualizes grocery sales insights across outlet types, item categories, and business performance metrics.

---

## 📦 Data Collection

- **Source:** [`BlinkIT Grocery Data.xlsx`](https://drive.google.com/drive/folders/1mKh61zKVBnPJN0A5lc77osGNkmNa-loI)
- **Format:** Microsoft Excel (.xlsx)
- **Content:**
  - **Sales Data** sheet with transactional details:
    - Item Type
    - Outlet Size
    - Outlet Location Tier
    - Ratings
    - Fat Content
    - Financial Metrics

---

## 🛠️ Data Preprocessing

- **Data Cleaning:**
  - Removed missing/null values from key fields
  - Standardized categorical data (e.g. Fat Content, Outlet Sizes)

- **Transformations:**
  - Added calculated columns:
    - Total Sales
    - Average Sales
    - Average Rating
    - Item Visibility = `No. of Items` / `Total Items`

- **Data Types:**
  - Categorical:
    - Item Type
    - Outlet Size
    - Outlet Location
    - Fat Content
  - Numerical:
    - Sales
    - Rating
    - No. of Items

---

## 🗂️ Data Modeling

- Established relationships in Power BI:
  - One-to-many links (e.g. outlets → transactions)
- Created hierarchies for easy filtering
- Implemented slicers for:
  - Outlet Location Type
  - Outlet Size
  - Item Type

---

## 📊 Data Visualization (Power BI)

![Screenshot 2025-02-02 180448](https://github.com/user-attachments/assets/d92de7f5-8723-4cc3-bf99-1900f38a54ec)
---

## 🎯 Insights Summary

-  Designed and implemented an interactive Power BI dashboard to analyze sales performance for a **Blinkit** platform,
achieving total sales of **$1.2M**.
-  Low-fat items emerged as the top contributors, accounting for **64.7% ($776K)** of sales, while regular items
contributed **35.3% ($425K)**.
-  Among item categories, **Fruits & Vegetables** and **Snack Foods** were the top performers, each contributing
$180K, while **Breakfast and Seafood** showed the lowest sales, both under **$20K**. The dashboard also tracked
outlet performance trends over a decade, highlighting a peak in sales at **$205K in 2018**.

---

## 🛠 Tools & Technologies

- Power BI → Interactive dashboard creation
- Excel → Data storage and cleaning
- DAX → Custom Measures

---






