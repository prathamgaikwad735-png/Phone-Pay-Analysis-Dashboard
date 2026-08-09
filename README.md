# PhonePe Transaction Analysis Dashboard
## An interactive Power BI dashboard that analyzes PhonePe digital payment transactions across India — covering transaction trends, user segments, service categories, and payment status patterns to support data-driven business decisions.

## Key Business Questions
As digital payments continue to grow rapidly in India, platforms like PhonePe process millions of transactions every day across services such as money transfer, recharges, insurance, and loans. With this scale comes a critical business challenge: not every transaction succeeds. Failed and pending transactions directly affect revenue, user trust, and operational efficiency.
Without a clear view into where, when, and among which users these failures and delays are concentrated, it becomes difficult for the business to prioritize fixes, allocate support resources, or improve service reliability. This dashboard is built to answer:
- Which services (Money Transfer, Loans, Insurance, Recharge) have the highest failure or pending value?
- Which age segments (Gen Z, Millennials, Gen X, Boomers) drive the most successful vs. failed vs. pending transactions?
- Are failures/delays concentrated on specific months or specific days (weekday vs. weekend)?
- Who are the highest-value users, and which segments should be prioritized for retention?


## Process / Approach
1.	Data Understanding — Reviewed the raw transaction dataset (transaction ID, user ID, age segment, service type, amount, status, date, weekday/weekend flag).
2.	Data Cleaning (Power Query) — Handled missing values, standardized date and status fields, and created calculated columns needed for segmentation (age group, weekday/weekend).
3.	Data Modeling (DAX) — Built measures for Total Transactions, Total Value, Unique Users, and Success Rate; created relationships to support dynamic filtering by Month and Payment Status.
4.	Dashboard Design (Power BI) — Designed a single-page layout with top-level KPIs, trend charts, segment breakdowns, and a dedicated insights panel, so the story reads top-to-bottom without extra clicks.
5.	Validation — Cross-checked KPI totals against filtered views (Failed / Pending / Successful) to confirm the numbers reconcile correctly.
6.	Insight Extraction — Interpreted the visuals to surface the business insights summarized below.




## Dataset Used
- <a href="https://github.com/prathamgaikwad735-png/Phone-Pay-Analysis-Dashboard/blob/main/Phone%20Pay%20Analysis.pbix">Dataset</a>

## Overview
As digital payments continue to grow rapidly in India, platforms like PhonePe handle millions of transactions every day. This dashboard transforms raw transaction data into meaningful business insights around customer behavior, service performance, and transaction trends.

## Key Metrics (KPIs)
<img width="624" height="85" alt="image" src="https://github.com/user-attachments/assets/6d7b749c-912f-4b37-b71b-2c3199a257f3" />

## Dashboard Modules
- Transaction Trend Analysis — month-wise transaction patterns
- Age Segment Contribution — Gen Z, Millennials, Gen X behavior
- Service Transaction Analysis — Money Transfer, Loans, Health, Car/Bike services, etc.
- Top Users Analysis — highest contributing users
- Weekday vs Weekend Usage Analysis — activity comparison
- Dynamic Filters — Month and Payment Status (Success / Failed / Pending)

# Dashboard Views
## Overall Dashboard
Full picture — KPIs, transaction trend, age segment split, service value analysis, top users, and weekday vs weekend usage.

<img width="698" height="384" alt="image" src="https://github.com/user-attachments/assets/fff34433-2ba3-4d74-9ff1-968d7f92a9f8" />

## Failed Payment Analysis
Filtered on Failed status — 10K transactions worth ₹39.32M. Money Transfer drives the highest failed value; Gen X and Millennials contribute the most failures; weekdays see more failures than weekends.

<img width="698" height="386" alt="image" src="https://github.com/user-attachments/assets/d8b50b93-dfef-4395-b906-77f3be9e7881" />

## Pending Payment Analysis
Filtered on Pending status — 2K transactions worth ₹101.9M. Loan services top the pending value chart; June and July peak in pending volume

<img width="698" height="380" alt="image" src="https://github.com/user-attachments/assets/e22654bd-1052-4561-a530-1c844ce457a0" />

## Successful Payment Analysis
Filtered on Successful status — 288K transactions worth ₹3.33bn at a 100% success rate within this filter. Money Transfer remains the most-used service; July and August are the strongest months

<img width="698" height="394" alt="image" src="https://github.com/user-attachments/assets/c1a575ff-9f04-4135-8522-c7f9af0e8677" />

# Key Business Insights
1.	Money Transfer is the most popular and highest-performing service on the platform.
2.	Millennials are the most active user segment across all transaction statuses.
3.	Gen X users contribute significantly to transaction value, especially in vehicle-related services.
4.	Weekdays consistently record higher transaction activity (failed, pending, and successful).
5.	July and August are the strongest performing months for successful transactions.
6.	Loan-related services contribute the highest pending transaction value, indicating a need for process optimization.
7.	
## Failed Payment Analysis — Detail
-	April has the lowest failed transactions; August and September also show relatively fewer failures.
- Gen X and Millennials contribute the most to failed transactions.
- Money Transfer has the highest failed transaction value.
- Failed payments are significantly higher on weekdays.
## Pending Payment Analysis — Detail
- June and July have the highest number of pending payments.
-	Millennials and Gen X contribute the most to pending transactions.
- Loan Services have the highest pending transaction value.
- Pending payments are also higher during weekdays.
## Successful Payment Analysis — Detail
- February has comparatively fewer successful transactions; July and August record the highest.
-	Millennials and Gen Z are the largest contributors to successful transactions.
-	Money Transfer is the most frequently used service.
-	Successful transactions are highest during weekdays.

## Key questions this dashboard answers:
-	Which services (Money Transfer, Loans, Insurance, Recharge) have the highest failure or pending value?
-	Which age segments (Gen Z, Millennials, Gen X, Boomers) drive the most successful vs. failed vs. pending transactions?
-	Are failures/delays concentrated on specific months or specific days (weekday vs. weekend)?
-	Who are the highest-value users, and which segments should be prioritized for retention


## Tech Stack
-	Power BI Desktop — data modeling, DAX measures, and dashboard design
-	Power Query — data cleaning and transformation

## Conclusion
This dashboard provides a comprehensive analysis of PhonePe transaction data, helping understand customer behavior, transaction trends, service performance, payment status patterns, and user segment contribution — supporting better business decisions and service optimization.














