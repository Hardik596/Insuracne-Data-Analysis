# Prism Insurance Analytics Dashboard (Power BI)

## Project Overview

This project presents an interactive **Insurance Analytics Dashboard** built using Power BI for **Prism Insurance Pvt. Ltd.** The dashboard provides a comprehensive view of premium collection, claim performance, policy activity, and customer distribution.

It enables business stakeholders to monitor financial health, understand risk patterns, track claim behavior, and make data-driven decisions to improve operational efficiency and profitability.

---

## Business Objectives

* Analyze total **Premium, Claim, and Coverage Amounts**.
* Identify high-performing and high-risk **Policy Types**.
* Monitor **Active vs Inactive Policies**.
* Evaluate **Claim Status distribution** (Pending, Settled, Rejected).
* Understand claim trends across different **Age Groups**.
* Provide dynamic filtering for Policy Number, Claim Number, and Customer.

---

## Key Metrics (KPIs)

* **Total Premium Amount:** 5.98M
* **Total Claim Amount:** 16.91M
* **Total Coverage Amount:** 600.55M
* **Customer Distribution:**

  * Male: 5003
  * Female: 5001

---

## Dataset Description

The dataset contains insurance-related transactional data including:

* Customer ID & Gender
* Policy Number & Policy Type
* Claim Number
* Premium Amount
* Claim Amount
* Coverage Amount
* Claim Status (Pending / Settled / Rejected)
* Policy Status (Active / Inactive)
* Age Group

---

## Data Preparation (Power Query)

* Cleaned and standardized column formats.
* Removed null and duplicate records.
* Converted financial fields to numeric data types.
* Categorized customers into Age Groups.
* Structured data for efficient filtering and aggregation.

---

## Dashboard Features

### 1. Premium Analysis

* **Premium Amount by Policy Type**

  * Travel policies generate the highest premium.
  * Followed by Health, Auto, Life, and Home.

---

### 2. Policy Activity Monitoring

* **Active vs Inactive Policies (Donut Chart)**

  * Active Policies: ~57%
  * Inactive Policies: ~43%

Helps in understanding customer retention and engagement.

---

### 3. Claim Status Insights

* Visual distribution of:

  * Rejected Claims (~4.4K)
  * Settled Claims (~3.4K)
  * Pending Claims (~2.3K)

This helps identify operational bottlenecks and risk areas.

---

### 4. Claim Analysis by Age Group

* Adults generate the highest claim amount.
* Followed by Elders and Young Adults.
* Useful for risk assessment and premium strategy planning.

---

### 5. Policy-wise Claim Breakdown

Tabular view showing claim amounts by Policy Type across:

* Pending
* Rejected
* Settled

Helps identify high-risk policy categories.

---

### 6. Interactive Filtering

Users can dynamically filter the dashboard by:

* Policy Number
* Claim Number
* Customer ID

Enables detailed investigation at a granular level.

---

## Key Insights

* Travel and Health policies are major revenue contributors.
* Claim amount significantly exceeds premium collection, indicating potential risk exposure.
* A high number of rejected claims suggests stricter validation or customer dissatisfaction.
* Adults represent the highest claim risk segment.
* Active policy ratio indicates moderate customer retention.

---

## Tools & Technologies

* Power BI Desktop
* Power Query (ETL & Data Cleaning)
* DAX (Measures & KPIs)
* Excel / CSV (Data Source)

---

## Business Value

This dashboard helps insurance companies:

* Monitor financial performance
* Identify high-risk customer segments
* Improve claim management
* Optimize policy strategies
* Enhance customer retention
