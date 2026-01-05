# saas-executive-dashboard
# SaaS Executive Dashboard

## Overview
This project is an executive-level Tableau dashboard built to give a clear, high-level view of a SaaS business’s subscription health. The goal is to help decision-makers quickly understand how the customer base is changing over time, where growth is coming from, and where losses are occurring.

The dashboard focuses on clarity, consistency, and metrics that are commonly used in SaaS reporting.

---

## What This Dashboard Shows
The dashboard tracks five core subscription metrics:

- **Active Subscriptions**  
  The number of subscriptions that are currently active as of the selected date.

- **New Subscriptions**  
  Subscriptions that started during the selected time period.

- **Churned Subscriptions**  
  Subscriptions that ended during the selected time period.

- **Net Change**  
  The difference between new and churned subscriptions, showing whether the business is growing or shrinking.

- **Churn Rate**  
  The proportion of active subscriptions that were lost during the selected period.

All event-based metrics (new, churned, net change, and churn rate) update dynamically based on the selected date range to ensure consistency across the dashboard.

---

## Dashboard Preview
![Dashboard Preview](screenshots/dashboard.png)

---

## How the Analysis Was Done
- Subscription lifecycle events were identified using start and end dates
- Event-based metrics were scoped using a shared date filter
- Active subscriptions were treated as a state-based metric
- The dashboard was built using a tiled layout to ensure stability and responsiveness
- Tooltips were added to clearly explain how each KPI is calculated

The design prioritizes readability and executive usability over excessive visual complexity.

---

## Tools Used
- **Tableau** – Dashboard design and visualization  
- **Python** – Data preparation and validation  
- **GitHub** – Project version control and portfolio hosting  

---

## Repository Contents
- `data/subscriptions.csv` – Dataset used for the analysis  
- `tableau/SaaS_Executive_Overview.twbx` – Tableau workbook file  
- `screenshots/dashboard.png` – Dashboard preview image  

---

## Why This Project
This project was created to demonstrate the ability to:
- Translate raw subscription data into meaningful business metrics
- Design dashboards that balance clarity with analytical rigor
- Communicate SaaS performance in a way that supports decision-making
