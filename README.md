# Financial-Loan-Analysis

🏦 Bank Loan Report - Power BI Dashboard

This project presents a comprehensive *Bank Loan Report* built using *Power BI*. The goal is to monitor and assess the bank’s lending activities by analyzing key metrics such as loan applications, funding, repayments, and loan statuses. The report is designed to support strategic decision-making and operational efficiency across lending functions.

---

📌 Problem Statement

In order to effectively track and evaluate our bank’s loan portfolio, a detailed report is required to analyze trends, monitor performance, and assess loan quality. This report will support data-driven decisions and help improve lending strategies.

---

📊 Dashboard 1: Summary

This dashboard provides a high-level summary of the bank's overall loan performance with focus on key metrics and Month-over-Month (MoM) trends.

🎯 Key Performance Indicators (KPIs)

1. *Total Loan Applications*  
   - Includes MTD and MoM comparisons.

2. *Total Funded Amount*  
   - Total amount disbursed as loans (MTD & MoM).

3. *Total Amount Received*  
   - Total payments received from borrowers (MTD & MoM).

4. *Average Interest Rate*  
   - Overall and MTD average interest rates (MoM tracking).

5. *Average Debt-to-Income Ratio (DTI)*  
   - Average borrower DTI (MTD & MoM).

---

✅ Good Loan vs Bad Loan KPIs

Good Loan Criteria:
- Loan Status: *'Fully Paid'* or *'Current'*

Good Loan Metrics:
- *Good Loan Application %*
- *Good Loan Applications*
- *Good Loan Funded Amount*
- *Good Loan Total Received Amount*

---

Bad Loan Criteria:
- Loan Status: *'Charged Off'*

Bad Loan Metrics:
- *Bad Loan Application %*
- *Bad Loan Applications*
- *Bad Loan Funded Amount*
- *Bad Loan Total Received Amount*

---

🧮 Loan Status Grid View

A grid view categorized by *Loan Status* displaying:

- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  
- MTD Funded Amount  
- MTD Amount Received  
- Average Interest Rate  
- Average DTI  

> This tab provides a granular view for performance comparison across different loan statuses.

---

📈 Dashboard 2: Overview

Visual exploration of loan metrics over time and across key demographic and geographic dimensions.

📅 Monthly Trends by Issue Date (Line Chart)
- Metrics: Loan Applications, Funded Amount, Amount Received  
- Objective: Understand seasonality and long-term trends.

🗺️ Regional Analysis by State (Filled Map)
- Metrics segmented by state  
- Objective: Identify high and low-performing regions.

🕒 Loan Term Analysis (Donut Chart)
- Segments: Loan Terms (e.g., 36 months, 60 months)  
- Objective: Compare volume and value across term types.

👷 Employee Length Analysis (Bar Chart)
- X-Axis: Employment Length  
- Objective: Analyze lending behavior by employment history.

🎯 Loan Purpose Breakdown (Bar Chart)
- X-Axis: Loan Purpose Categories (e.g., debt consolidation, education)  
- Objective: Identify common borrowing reasons.

🏠 Home Ownership Analysis (Tree Map)
- Hierarchy: Home Ownership (Own, Rent, Mortgage)  
- Objective: Visualize impact of ownership on loan metrics.

---

📋 Dashboard 3: Details

Objective:
To provide a *comprehensive and interactive table* with full loan details, borrower information, and performance metrics.

Features:
- Full record-level visibility  
- Search, sort, and filter options  
- Drill-through and bookmark toggles  
- Export-ready for reporting

---

🔁 Data & Refresh Details

- *Data Source: Bank loan dataset *(not publicly included in this repo)  
- *Refresh Frequency*: Configurable based on source and usage  
- *Implementation*: Native Power BI visuals and DAX-based KPIs  

---
