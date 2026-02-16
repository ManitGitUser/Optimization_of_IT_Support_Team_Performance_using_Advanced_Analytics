# Supportlytics: Data-Driven Optimization of IT Support Team Performance

## Problem Statement
Modern IT support environments handle thousands of incident tickets daily, making it difficult to monitor performance efficiency, workload distribution, and resolution delays.  
This project aims to transform raw incident event logs into actionable analytics that help identify operational bottlenecks, optimize resolution time, and improve IT support team performance.

---

## Dataset Description
The project uses the **Incident Management Process Enriched Event Log** dataset.

- Source: Real-world ServiceNow incident data
- Volume: ~25K incidents derived from 141K+ events
- Key Fields:
  - Priority
  - Assignment Group
  - Opened / Resolved timestamps
  - Reassignment count
  - Incident state

Raw logs were flattened using Python to create one record per incident lifecycle.

---

## Key Performance Indicators (KPIs)
- Total Tickets
- Average Resolution Time (Hours)
- Resolution Completion Rate
- Ticket Distribution by Priority
- Resolution Speed Categories
- Assignment Group Workload

---

## Dashboard Overview
The Power BI dashboard is structured into three analytical sections:

### 1️⃣ Executive Overview
High-level metrics showing ticket volume, average resolution time, and overall resolution success rate.

### 2️⃣ Operational Performance
Breakdown of workload vs performance across priority levels to detect inefficiencies.

### 3️⃣ Team Efficiency
Assignment group analysis highlighting workload imbalance and potential performance bottlenecks.

---

## Key Insights
- Moderate priority tickets dominate workload, indicating operational focus should shift beyond only critical issues.
- Low priority tickets show longer resolution times, suggesting possible backlog or resource imbalance.
- Majority of tickets are resolved quickly (<1 day), but long-tail incidents inflate average resolution time.
- Certain assignment groups handle a disproportionately high number of tickets, indicating potential resource optimization opportunities.

---

## Future Improvements & Recommendations
- Add predictive models to estimate resolution time during ticket creation.
- Introduce automation for repetitive low-priority tickets.
- Expand dashboard with root-cause clustering using NLP.

---

## 🛠 Tools Used
Python (Pandas, NumPy) — Data Cleaning  
Power BI — Dashboard & Analytics  
Jupyter Notebook — Development Environment
