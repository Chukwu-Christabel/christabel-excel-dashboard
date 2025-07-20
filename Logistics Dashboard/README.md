# 🚚 Logistics Dashboard Project (Excel-Based)

A dynamic and insightful logistics dashboard built entirely in Microsoft Excel. Designed to track transport efficiency, monitor delays, analyze costs, and visualize delivery performance — all with slicers and pivot tables.

📊 Interactive. Clean. Business-Ready.

[📥 Download Dashboard Excel File](./Logistics_Dashboard.xlsx)  
[🖼️ View Dataset Preview](./images/raw-dataset-preview.png)  
[📸 See Final Dashboard Snapshot](./images/dashboard-snapshot.png)

---

## 🔍 Quick Preview

| | |
|--|--|
| 📦 File Type | Excel Workbook (.xlsx) |
| 📅 Features | Pivot Tables, Slicers, Calculated Fields |
| 🧰 Tools Used | Excel formulas, helper columns, XLOOKUP, data cleaning |
| 🧑‍💻 Built By | Chukwu Christabel |

---

## 📚 Table of Contents
- [📌 Project Summary](#-project-summary)
- [📁 Dataset Details](#-dataset-details)
- [📷 Screenshots](#-screenshots)
- [📥 How to Use](#-how-to-use)
- [🚀 Going Further](#-going-further)
- [🙋‍♂️ Author & Links](#-author--links)

---

## 📌 Project Summary

This dashboard gives a clear overview of transportation performance across:
- Different routes
- Various transporters
- Key delivery delays
- Invoicing status
- Profit margins between clients and suppliers

It features auto-calculated values for cost analysis, delivery tracking, and performance rankings. It is powered by Excel PivotTables and slicers, giving end-users full control over the insights they want to extract.

---

## 📁 Dataset Details

🗂️ This Excel file includes the following columns:  
(🛠️ = Custom column created manually using formulas)

| Column Name | Description |
|-------------|-------------|
| Transporter | Delivery agents (A, B, C) |
| Depart From / Arrive To | Route locations |
| 🛠️ Route | Combined "Depart From" & "Arrive To" |
| Loading Date / Offloading Date | Start and end of delivery |
| 🛠️ Delivery Status | Derived from Offloading Date |
| 🛠️ Year | Extracted from Offloading Date |
| 🛠️ Valid Year Flag | Filters blank dates in pivots |
| Client Invoice Status / Transporter Invoice Status | Invoicing progress |
| Product Name | Item description |
| Gross Weight | Raw weight |
| Client Rate per T / Currency | Client pricing |
| 🛠️ Client Rate Per Two | Formula-based conversion |
| 🛠️ Client Total Cost | Based on rate & weight |
| Supplier Rate per T / T2 / Currency | Supplier pricing |
| 🛠️ Supplier Total Cost | Total supplier payout |
| 🛠️ Weight | Derived and standardized weight |
| 🛠️ Profit per T | Per-ton margin |
| 🛠️ Gross Profit | Final client-supplier margin |
| POD Attached | Proof of delivery status |
| Delay at Toll / Workshop / Borders | Delay points |
| 🛠️ Total Delay in Days | Summed delay values |

---

## 📷 Screenshots

### 🖼️ Raw Dataset Preview
![Raw Dataset Preview](./images/raw-dataset-preview.png)

### 📸 Final Dashboard Snapshot
![Dashboard View](./images/logistics-dashboard-snapshot.png)

---

## 📥 How to Use

1. 📁 Download the file: [Click here to download](./Logistics_Dashboard.xlsx)
2. 🖥️ Open with Microsoft Excel (2016+ or any)
3. 🌀 Use the slicers to filter by:
   - Route
   - Year
   - Transporter
   - Invoice Status
4. 📊 Charts and values update dynamically

---

## 🚀 Going Further

🔧 Planned upgrades:
- Power BI version
- Macro-based automation
- Embedded insights generator

📌 You can also suggest improvements via [Issues](https://github.com/Chukwu-Christabel/christabel-excel-dashboard/issues)

---

## 🙋‍♂️ Author & Links

Chukwu Christabel 
Logistics Data Analyst & Excel Enthusiast

- 🌐 [LinkedIn Profile](https://www.linkedin.com/in/christabel-chukwu-8576782a9)
- 💼 [Github Portfolio](https://github.com/Chukwu-Christabel)
- 📤 [Logistics Dashboard Repository](https://github.com/Chukwu-Christabel/christabel-excel-dashboard) 

---

> ⭐️ Don’t forget to star this repo if you find it helpful!  
> 📝 Feel free to fork, clone, or contribute to make it even better.
