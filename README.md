# 🚚 Olist Logistics Intelligence & Satisfaction Optimization

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) 
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

An end-to-end data analytics project transforming raw Brazilian e-commerce logistics data into actionable strategic insights. This project proves the correlation between **"Delivery Speed"** and **"Customer Satisfaction"**.

---

## 📌 Project Overview
The project evaluates delivery performance and identifies systemic bottlenecks through three key dimensions:
1. **Operational Efficiency:** Analyzing the breakdown between warehouse handling and actual transit time.
2. **Satisfaction Trends:** Identifying the "Critical Threshold" where delivery delays directly impact review scores.
3. **Geographic Analysis:** Pinpointing nationwide disruptions and regional carrier failures using Heatmaps.



---

## 🛠️ Data Exploration & Preparation
Before analysis, a robust Data Pipeline was built to handle complex Relational Data:
* **Advanced SQL (SQLite):** Utilized CTEs and Window Functions (`ROW_NUMBER()`) to deduplicate orders and extract only the latest customer reviews.
* **Data Cleansing:** Standardized city names, handled NULL values, and performed "Time Travel Checks" to eliminate logical errors.
* **Stable Operations Filtering:** Intentionally excluded 2016 data to focus on 2017-2018, ensuring the analysis reflects a period of stable business operations.
* **ETL Process:** Exported 100% cleaned data to CSV for high-fidelity visualization in Microsoft Excel.

---

## 📊 Key Insights & Strategic Actions
* **The 8-Day Rule:** Data proves that maintaining an "Early Delivery" buffer of at least 8 days ensures a 4.0+ star satisfaction rating.
* **Systemic Shock Identification:** The March 2018 crisis was identified as a nationwide failure rather than a regional one, evidenced by simultaneous "Dark Orange" bands across all states in the Heatmap.
* **Strategic Proposals:** Recommended an **Early Warning Alert** system for orders with <10 days buffer and a carrier restructuring plan for remote states (AP, RR).



---

## 🔗 Full Case Study
Detailed documentation, SQL logic, and the full interactive dashboard are available here:
👉 **[Full Project Case Study on Notion](https://www.notion.so/Project-SQL-Excel-30b2e2b3003280ea81afe94fef1d256c?source=copy_link)**

---
*Developed by Chitnapak Kingkoyao*
