# OptiStock-Smart-Inventory-Control-System
A SQL-based inventory control solution built to intelligently manage stock, reduce understock/overstock issues, and enhance operational efficiency for businesses.


🚀 Project Overview
OptiStock is a smart inventory control system designed using MySQL that helps businesses efficiently monitor stock levels, avoid shortages, and optimize restocking. This project addresses common inventory challenges by integrating safety stock control, reorder rules, transaction tracking, and inventory turnover analysis — all using structured SQL queries, views, and relational tables.

📌 Features
✅ Track Inventory in Real-Time
Monitor current stock levels for each product across multiple categories.
✅ Understock Detection
Automatically identifies products whose stock is below the defined safety level.
✅ Smart Reordering Alerts
Generates alerts when stock drops below the reorder point, with suggested reorder quantity.
✅ Inventory Turnover Insights
Measure how efficiently inventory is being sold or used over time.
✅ Supplier Mapping
Link suppliers to specific products for easy reorder reference.
✅ Aged Stock Reports
Identify products that haven’t been restocked for a long time (dead stock detection).
✅ Monthly Transaction Summary
Summarizes IN/OUT stock movement per month for trend analysis.

🧱 Database Schema
The project includes the following normalized relational tables:

Table Name	Description
products	Product catalog with name, category, price
inventory	Tracks current quantity and restock date
transactions	Records stock IN/OUT movements
restock_rules	Holds safety stock and reorder thresholds
suppliers	Supplier directory
product_suppliers	Links products to suppliers (many-to-many)

💾 Sample Data
10+ products across different categories
Mapped suppliers with valid contact info
Sample transactions (IN and OUT)
Restock rules for each product
Realistic last restocked dates

🔍 Key Views & Reports
understock_view
Shows products currently below safety stock.
reorder_alert_view
Lists products below reorder point with suggested reorder quantity.
inventory_turnover_view
Provides inventory usage and efficiency over time.
aged_inventory_report
Shows products not restocked in over 60 days.

💡 Technologies Used
🛢️ MySQL – Core database engine
✍️ SQL – Queries, views, reports
🗃️ Relational Schema Design – Normalized, scalable

📈 Future Enhancements
📦 Add batch/expiry tracking for perishable items
🖥️ Create a web dashboard using PHP/Flask/Node.js
📧 Email/SMS alerts for low stock

📊 Visual inventory charts using Power BI or Python
📁 Folder Structure
📦 OptiStock-SQL
 ┣ 📂 scripts
 ┃ ┣ 📄 create_tables.sql
 ┃ ┣ 📄 insert_data.sql
 ┃ ┣ 📄 views.sql
 ┣ 📄 README.md
