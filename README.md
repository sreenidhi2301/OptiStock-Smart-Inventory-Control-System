
# 🚀 OptiStock – Smart Inventory Control System

**OptiStock** is a SQL-based smart inventory control system built on **MySQL**, designed to help businesses efficiently monitor stock levels, avoid shortages, and optimize restocking.  

This project tackles common inventory management challenges by integrating **safety stock control, reorder rules, transaction tracking, and turnover analysis** — all implemented with **structured SQL queries, views, and relational tables**.

---

## 📌 Features

- ✅ **Real-Time Stock Tracking** – Monitor stock levels for each product across multiple categories.  
- ✅ **Understock Detection** – Identify products falling below the defined safety threshold.  
- ✅ **Smart Reordering Alerts** – Get reorder alerts with suggested quantities when stock dips below the reorder point.  
- ✅ **Inventory Turnover Insights** – Track how efficiently inventory is being sold/used over time.  
- ✅ **Supplier Mapping** – Link suppliers to products for quick and reliable restocking.  
- ✅ **Aged Stock Reports** – Detect slow-moving or dead stock not restocked for 60+ days.  
- ✅ **Monthly Transaction Summary** – Analyze IN/OUT stock movements per month for demand trends.  

---

## 🧱 Database Schema

The project includes normalized relational tables:

| Table Name         | Description                                      |
|--------------------|--------------------------------------------------|
| `products`         | Product catalog (name, category, price)          |
| `inventory`        | Tracks current quantity & last restock date      |
| `transactions`     | Records stock IN/OUT movements                   |
| `restock_rules`    | Safety stock & reorder thresholds                |
| `suppliers`        | Supplier details (name, contact info)            |
| `product_suppliers`| Many-to-many mapping between products & suppliers |

---

## 💾 Sample Data

- 10+ products across multiple categories  
- Suppliers with contact details  
- Stock IN/OUT transactions for realistic flow  
- Restock rules for each product  
- Simulated aged stock (not restocked for 60+ days)  

---

## 🔍 Key Views & Reports

- 📉 **`understock_view`** → Products below safety stock  
- 🔔 **`reorder_alert_view`** → Products needing reorder with suggested quantity  
- 📊 **`inventory_turnover_view`** → Stock usage & efficiency metrics  
- 🕒 **`aged_inventory_report`** → Products not restocked in 60+ days  

---

## 💡 Technologies Used

- 🛢️ **MySQL** – Database engine  
- ✍️ **SQL** – Queries, views, reports  
- 🗃️ **Relational Schema Design** – Normalized & scalable  

---

## 📈 Future Enhancements

- 📦 Batch/expiry tracking for perishable items  
- 🖥️ Web dashboard using PHP / Flask / Node.js  
- 📧 Automated email/SMS alerts for low stock  
- 📊 Power BI / Python dashboards for visual insights  

---


