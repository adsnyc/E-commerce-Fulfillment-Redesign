# E-commerce Orders & Returns Optimization  

## Objective  
This project analyzes and optimizes the **e-commerce order fulfillment and returns process** for a small retail operation.  
The goal was to identify inefficiencies, reduce delays in order-to-delivery, and improve customer experience by using **Python, SQL, and Power BI** for data-driven insights.  

### Key Objectives
- Detect bottlenecks in order flow and return handling.  
- Improve inventory and courier handoffs.  
- Provide real-time visibility into orders and returns.  
- Recommend process changes to reduce errors and delays.  

---

## Project Structure  

| File Name | Description |  
|-----------|-------------|  
| **Stakeholder_Interviews.docx** | Summarized real stakeholder interviews with warehouse, support, and fulfillment staff. Highlights manual processes and pain points. |  
| **As-Is.png** | Visual process map of the current (manual-heavy) order-to-delivery workflow. |  
| **To-Be.png** | Improved process map showing proposed automation and system integrations. |  
| **analysis.ipynb** | Python & SQL notebook: data cleaning, exploratory analysis, return rate calculation, and query preparation. |  
| **dashboard.pbix** | Power BI interactive dashboard file with revenue, orders, and return trends. |  
| **E-comm.pdf** | Exported Power BI dashboard snapshot for presentation. |  
| **Notion Link (Insights & Recommendations)** | [View Here](https://www.notion.so/E-commerce-Fulfillment-Redesign-Insights-Recommendations-263dd29ba66580978fccd3ea25f6ec05?source=copy_link) – Final write-up with dashboard insights and recommendations. |  

---

## Tools Used  
- **Python (Pandas, SQLite)** – Data cleaning, transformations, and SQL queries.  
- **SQLite** – Querying cleaned transactional data for deeper insights.  
- **Power BI** – Interactive dashboards (Revenue by Country, Orders by Hour, Return Rate).  
- **Lucidchart** – As-Is and To-Be process mapping.  
- **MS Word / Notion** – Stakeholder interviews and recommendations documentation.  

---

## Process Followed  

### 1. Stakeholder Interviews  
- Conducted 3 real interviews with warehouse, support, and fulfillment staff.  
- Heavy reliance on Excel and email handoffs.  
- Pain points: courier delays, manual inventory checks, and lack of real-time visibility.  
- Returns handling: slow manual logging (3–4 days).  
- Desired: barcode scanning, automated tracking, and live dashboards.  

### 2. Process Mapping  
- **As-Is**: Manual Excel picklists, email handoffs, slow courier coordination.  
- **To-Be**: Real-time WMS (Warehouse Mgmt System) sync, automated courier booking, barcode scanning, auto-alerts for delays.  

### 3. Data Cleaning & SQL Analysis  
- Cleaned transactional data in Python (`analysis.ipynb`).  
- Split **Orders** vs **Returns** datasets.  
- Built metrics like **Return Rate per Country**.  
- Used SQLite queries to extract revenue by country, orders by hour, and return ratios.  

### 4. Dashboard (Power BI)  
Created 4 key visuals:  
- **Revenue by Country** – UK dominates revenue (~70%).  
- **Orders by Hour** – Peak between 10AM–2PM.  
- **Return Rate by Country** – USA, Czech Republic, and Malta have highest rates.  
- **Summary Table** – Orders, returns, and return rates by country.  

### 5. Insights & Recommendations  
Final findings and business recommendations are documented in **Notion** → [View Here](https://www.notion.so/E-commerce-Fulfillment-Redesign-Insights-Recommendations-263dd29ba66580978fccd3ea25f6ec05?source=copy_link).  

---

## Key Outcomes  
- Identified **UK as the primary revenue driver** → critical market to prioritize.  
- Return rates in smaller markets (e.g., USA, Malta) are **5–6× higher** than average → need quality/courier audits.  
- Operational bottlenecks (Excel/email) replaced with **real-time integrations** in To-Be workflow.  
- Peak hour analysis supports **better staffing** between 10AM–2PM.  

---

## Project Relevance  
This project demonstrates:  
- Ability to **conduct stakeholder analysis** (real interviews).  
- Use of **Python + SQL** for cleaning and analytics.  
- Building **interactive Power BI dashboards** for business insights.  
- Translating data into **process optimization and business recommendations**.  

---

## Acknowledgements  
Thanks to the anonymized stakeholders who shared their operational insights.  

---

## Contact  
**Akshay Deep Siddam**  
📧 siddam.akshaydeep@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/akshaydeep-siddam/)  
