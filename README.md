Customer Acquisition bottleneck Analysis & Warehouse Utilization Optimization.

---
Summary 
An end-to-end business analysis project that investigates declining customer acquisition by analyzing marketing performance, customer behavior, and warehouse operations using SQL and Power BI.

Business Problem

A retail company generating approximately ₹110.29 million in annual revenue reported an unexpected slowdown in customer acquisition. Although the business remained profitable, it acquired only 2 new customers during the current month.

Management wanted to determine whether the issue originated from marketing performance, product quality, inventory management, or another operational bottleneck.

The objective of this project was to investigate the root cause using data analysis and provide actionable business recommendations.

---

Project Objective

- Investigate why new customer acquisition had declined.
- Evaluate the effectiveness of marketing campaigns.
- Analyze customer behaviour and loyalty.
- Examine warehouse operations and inventory utilization.
- Identify operational bottlenecks affecting sales.
- Recommend business improvements backed by data.

---

Dataset

This project uses a synthetic business dataset created using Python's Faker library.

Rather than generating clean sample data, the dataset was intentionally designed to mimic real business environments by including operational inefficiencies, inventory constraints, marketing metrics, customer behaviour, warehouse utilization data, and other realistic business challenges.

The business scenario and dataset design were created to simulate a real consulting engagement.

---

Business Questions

- Is marketing underperforming?
- Are customers dissatisfied with the products?
- Is inventory causing lost sales?
- Are warehouse operations efficient?
- What is preventing the company from acquiring new customers?

---

Key Business KPIs

KPI| Value
Annual Revenue| ₹110.29M
Marketing Spend| ₹702.18K
Marketing Revenue| ₹55.45M
Returning Customers| 90%
New Customers (Monthly)| 2
Average Revenue per Customer| ₹22.58K
Total Orders (Year)| 20,000
Average Order Value| ₹5.51K
Total Units Sold| 110K
Warehouse Utilization| 53.01%

---

Investigation Process

The project followed a hypothesis-driven approach.

Hypothesis 1 — Marketing Performance

Marketing campaigns generated approximately ₹55.45 million in attributed revenue from a spend of ₹702K, indicating that marketing was performing efficiently.

Conclusion: Marketing was not the primary issue.

---

Hypothesis 2 — Product Quality

Customer analysis showed:

- 90% returning customers
- Strong customer loyalty
- Healthy average revenue per customer

These findings suggested customers were satisfied with the products.

Conclusion: Product quality was unlikely to be responsible.

---

Hypothesis 3 — Operational Bottlenecks

Warehouse analysis revealed several operational issues:

- Average warehouse utilization of only 53.01%
- Large warehouses operating between 46–60% capacity
- Smaller warehouses operating between 86–90% capacity
- Average product delay of 12 days
- Limited warehouse staffing

The imbalance created inventory shortages in high-demand locations, causing products to remain unavailable when new customers attempted to purchase.

Returning customers purchased available stock before inventory could be replenished, explaining the unusually low number of new customers.

Root Cause Identified: Inefficient warehouse utilization and inventory distribution.

---

Key Findings

- Marketing performance was strong and generated significant revenue.
- Existing customers remained loyal and continued purchasing.
- Warehouse utilization was poorly balanced.
- Inventory distribution created frequent stock shortages.
- Delivery delays reduced product availability.
- Operational inefficiencies, rather than marketing or product quality, limited business growth.

---

Business Recommendations

- Increase warehouse staffing to improve operational efficiency.
- Convert larger warehouses into regional distribution hubs.
- Rebalance inventory between warehouses based on demand.
- Improve replenishment scheduling to reduce stockouts.
- Reduce average delivery time from 12 days.
- Monitor warehouse utilization through executive dashboards.

---

Business Impact

If implemented, these recommendations could:

- Improve warehouse utilization.
- Reduce inventory shortages.
- Increase product availability.
- Improve customer acquisition.
- Support long-term revenue growth through operational improvements.
Page 1 = Executive Sales Overview
Theme: customer_analysis
<img width="1422" height="797" alt="Image" src="https://github.com/user-attachments/assets/9bbb5033-decf-4135-bc34-183a31385116" />
Page 2 = Customer Loyalty & behavior
Theme: marketing_performance
<img width="1428" height="792" alt="Image" src="https://github.com/user-attachments/assets/51689c4f-8e3a-4d50-9b01-0a299f31d76f" />
Page 3 = Marketing Performance & ROI
Theme: warehouse_utilization
<img width="1433" height="796" alt="Image" src="https://github.com/user-attachments/assets/6477b16d-1ebb-4f20-ac5b-f88bcd6640bf" />


📁 Project Structure

Revenue-Loss-Analysis/
│
├── README.md
├── SQL/
│   ├── new project one of 22.sql
│
├── Dashboard/
│   ├── Revenue_Loss_Dashboard.pbix
│   
└── Images/
    ├── customer_analysis
    ├── marketing_performance.png
    └── warehouse_utilization.png

---

▶️ How to Run

Step 1 — Download the Repository

Clone the repository or download it as a ZIP file.

Step 2 — Open the Dataset

Open the dataset from the Dataset folder.

Step 3 — Execute the SQL Scripts

Run the SQL files in your preferred SQL environment to perform data cleaning.

Step 4 — Explore the Dashboard

Open the Power BI (project 08.pbix) file to interact with the dashboard and explore the findings.

Step 5 — Review the Analysis

Read the Business Findings and Recommendations sections in this README for the complete analysis.

---
# # Tools Used 
- MY SQL
- Power BI
- Python (faker)
- Excel

---

👨‍💻 Author

Arjun Baliga

Aspiring Business Analyst | Data Analyst

Skills

- SQL
- Python
- Power BI
- Excel

GitHub

https://github.com/BaligaArjun

LinkedIn

((https://www.linkedin.com/in/arjunprakashbaliga))





