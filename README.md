# Car Insurance Claims Analysis Dashboard

This Power BI project analyzes car insurance claims data to provide insights into claim trends, customer demographics, and incident characteristics. It includes summary statistics, breakdowns by gender, severity, type, and time, and visual tools for decision-making by insurance analysts.

## 📊 Dashboard Overview

### Page 1: **Car Insurance Analysis Summary**

This main page provides a high-level overview of claim activities:

- **YTD Summary**
  - **Claim Amount**: 53M
  - **Avg Total Claim Amount**: 53K
  - **Total Premiums Paid**: 21M

- **Current Month Summary**
  - **Claim Amount by Month**: 5.15M
  - **Avg Total Claim Amount by Month**: 0.05M
  - **Total Premiums Paid by Month**: 2.02M

- **Visual Insights**
  - **Total Claim Amount by Gender**
    - Female: 29M (54.29%)
    - Male: 24M (45.71%)
  - **Total Claim Amount by Incident Severity**
    - Major Damage, Total Loss, and Minor Damage contribute almost equally
    - Trivial Damage is negligible
  - **Total Claim Amount by Incident Type**
    - Highest: Multi-Vehicle and Single Vehicle Collisions
  - **Trend: Total Claim Amount by Year**
    - Sharp drop observed post-2015

- **Interactive Filters**
  - Year
  - Gender
  - Education Level
  - Incident State
  - Age Category

---

### Page 2: **Incident Details Table**

This page provides a detailed view of individual claims with dynamic KPIs:

- **KPI Cards**
  - Total Claim Amount by:
    - Gender: 62.97K 
    - Severity: 51.60K 
    - Age Group: 51.60K 
    - Vehicle Make: 51600 
  
- **Incident Table Columns**
  - Location (Street, City, State)
  - Incident Type and Severity
  - Auto Make
  - Demographics: Age Group, Gender, Education Level
  - Year and Hour of Incident
  - Number of Injuries
  - Claim and Premium Amounts

- **Totals**
  - Total Injuries: 391
  - Total Claim Amount: 25,971,520
