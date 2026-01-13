# Procurement KPI Analysis & Purchase Order Dashboard

Project focused on analyzing procurement performance using Power BI. This project presents a strategic view of supplier reliability, cost savings, delays, and fulfillment trends through an interactive dashboard and data-driven KPIs.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Dashboard Highlights](#dashboard-highlights)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Supplementary Documents](#supplementary-documents)
- [How to Run](#how-to-run)
- [Contact](#contact)

---

## Overview

The goal of this project is to assess the performance of procurement operations and suppliers by analyzing key purchase order (PO) metrics. Through an interactive Power BI dashboard, the analysis helps uncover late deliveries, pending POs, and potential cost savings opportunities.

---

### Project Components:
- Data visualization with Power BI
- KPI tracking (On-Time Delivery %, Cost Savings, Avg Delay)
- Dashboard report (PDF) and .pbix file included

---

## Dataset

- **Source:** Internal procurement system (anonymized)
- **Size:** ~7,000 records across multiple suppliers
- **Data Includes:**
  - Supplier ID, PO Number, PO Status, Order Date, Delivery Date
  - Quantity, Unit Price, PO Amount, Delay (Days)
  - Cost Savings, Region

📁 Files:
- `cleaned_procurement_data.csv`
- `Procurement KPI Analysis Dataset.csv`
- `supplier_summary.csv`

---

## 📈 Dashboard Highlights

📊 Built with Power BI to present actionable insights:

- **KPI Cards**: Total POs, On-Time Delivery %, Cost Savings, Avg Days Past Due
- **Visuals**:
  - Late Deliveries by Supplier
  - PO Status Breakdown
  - Top Suppliers by PO Volume
  - Cost Savings by Region
  - Delivery Trends & Delays

📊 [Power BI Dashboard (PDF)](https://drive.google.com/file/d/1sFVVK0mqdvYWrtwmaPW8Z8ef2cJ6C6Yl/view?usp=drive_link)

---

## Key Insights

- **On-Time Delivery Rate:** ~57%
- **Avg Days Past Due:** 568.25 days
- **Top Delayed Suppliers:** Beta Supplies, Epsilon Group
- **Cost Savings Achieved:** $786,230
- **Pending POs:** 206 POs pending, mostly across three suppliers

---

## Recommendations

- Enable automated delivery alerts for at-risk POs
- Introduce supplier performance scorecards
- Prioritize contracts with historically reliable suppliers
- Improve forecasting for high-volume regions
- Digitize procurement workflows to reduce manual errors

---

##  Supplementary Documents

📄 [Procurement KPI Analysis Report (PDF)](https://drive.google.com/file/d/1dhepcYaVYdQ26Hvr7HSt7496wbqsSqop/view?usp=sharing)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/KiruthikaRamadoss/Procurement_KPI_Analysis.git
   cd Procurement_KPI_Analysis
   
2. Create and activate a virtual environment (Optional):
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install dependencies:
   pip install -r requirements.txt

---

## Contact

For inquiries, collaboration, or feedback:

- [LinkedIn](https://www.linkedin.com/in/kiruthikaramadoss/)
- [GitHub](https://github.com/KiruthikaRamadoss)
- [Email](mailto:kiruthikaramadoss12@gmail.com)
