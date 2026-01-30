# 📊 Budget Controlling & Variance Analysis Dashboard

> **A real-time financial reporting tool designed to bridge the gap between budgetary planning and actual operational spend.**

---

## 📝 Case Study

### The Challenge

A complex, multi-program organization relied heavily on spreadsheets for financial reporting. Reports were manual, slow to produce, and difficult to interpret at a leadership level. Decision-makers lacked real-time visibility into cash position, budget performance, and program efficiency, leading to reactive rather than proactive management.

### The Solution

I designed a tiered **Budget Controlling Dashboard** that consolidated data from multiple sources into a single, trusted source of truth.

* **Executive Snapshot:** Created a "Home" view with gauge charts for immediate MTD/YTD health checks.
* **Variance Tracking:** implemented "traffic light" logic to instantly flag cost centers overspending (Red) vs. saving (Green).
* **Granular Drill-Down:** Built architecture allowing users to move from global figures down to specific line items (e.g., Events, Marketing).

### The Outcome

* **Reporting Latency:** Reduced from days to near real-time.
* **Risk Management:** Financial risks (overspends) are now identified mid-month rather than post-month-end.
* **Data-Driven Culture:** Shifted the organization from static PDF reports to interactive, self-service exploration.

---

## 🗝 Key Features

* **Period Comparisons:** Dynamic switching between Month-to-Date (MTD) and Year-to-Date (YTD) views.
* **Automated Variance Logic:**
* Calculates `Variance $ = Actual - Budget`
* Calculates `Variance % = (Actual - Budget) / Budget.`


* **Best Performer Highlighting:** Automatically ranks and displays departments with the highest budget savings.
* **Trend Analysis:** Bar charts visualizing spending patterns over 12 months to identify seasonality.
* **Data Export:** Integrated "Download Crosstab" functionality for auditors requiring raw data for Excel.

---

## 🧠 Business Logic & Metrics

The dashboard is built on three core pillars of financial data:

1. **Actuals:** Realized expenditure pulled from the ERP system.
2. **Budget:** Planned expenditure targets.
3. **Variance:** The deviation indicator.

**Visual Strategy:**

* **Gauge Charts:** Used for high-level "How much of the tank is full?" visualization.
* **Bullet Charts:** Used in the breakdown sections to show progress toward a target line without clutter.
* **Color Coding:** Red indicates a negative variance (Over Budget), Green/Teal indicates a positive variance (Under Budget).

---

## 🛠 Tech Stack

* **Data Visualization:** [Tableau]
* **Data Processing:** [SQL / Python Pandas / Excel]
* **Design/Prototyping:** [Figma / Adobe XD]

---

## 📸 Project Previews

[Tableau Link](https://public.tableau.com/app/profile/stephen.kamau/viz/Budgetcontrol_17697491785070/Home#1)

| Executive Summary (Home) | Deep-Dive Analysis (Overview) |
| --- | --- |
| ![Home Page](https://github.com/SteveJoe-cloud/Budget-Control-Finance-Project/blob/main/assets/Home%20(1).png) | ![Overview](https://github.com/SteveJoe-cloud/Budget-Control-Finance-Project/blob/main/assets/Overview.png) |

