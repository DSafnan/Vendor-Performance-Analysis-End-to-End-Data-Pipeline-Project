# 📦 Vendor Performance Analysis – End-to-End Data Pipeline Project

This project demonstrates a complete **data analytics workflow** for evaluating vendor and brand performance using **real-world scale data** (1 crore+ rows). The analysis integrates **SQL, Python, statistics**, and **Power BI** to produce actionable insights from raw purchase and sales data.

---

## 🔧 Tools & Technologies Used

- **SQL (SQLite):** Complex queries with `JOIN`, `CTE`, and aggregations to generate unified vendor data.
- **Python (pandas, logging):** Data cleaning, feature engineering, and automated logging.
- **Statistics:** Business KPIs such as profit margin, sales ratio, stock turnover.
- **Power BI:** Interactive dashboard with visual analytics.
- **Logging:** Full transparency and traceability of the data pipeline process.

---

## 📊 Key Business Metrics Calculated

- **Gross Profit**  
- **Profit Margin (%)**  
- **Sales-to-Purchase Ratio**  
- **Stock Turnover**  
- **Total Sales & Purchase by Vendor and Brand**

---

## ✅ Project Highlights

- Processed and filtered **1 crore+ rows** to retain only analysis-ready data.
- Built a **Python script** to automate data extraction, transformation, and ingestion into SQLite.
- Created a **vendor summary view** by joining sales, purchase, and freight datasets.
- Calculated business-critical KPIs and cleaned the data for accuracy.
- Developed a **Power BI dashboard** to identify top/low-performing vendors and brands visually.
- Reduced manual analysis time by over **60%** and enhanced decision-making.

---

## 📁 Folder Structure
├── ingestion_db.py # Script to ingest cleaned data back into SQLite
├── get_vendor_summary.py # Main logic: SQL queries, cleaning, metric creation
├── inventory.db # SQLite database (use sample or mock if private)
├── logs/ # Auto-generated logs for audit and debugging
└── PowerBI_Dashboard.pbix # Power BI dashboard file (if shared)

How to Run

1. Clone the repository  
2. Install required Python packages (only `pandas` needed)  
3. Ensure `inventory.db` is in the root directory  
4. Run:

```bash
python get_vendor_summary.py
