# financial-fraud-detection-sql

**Status:** Work in Progress  
**Tech Stack:** SQL, Python, PostgreSQL, Tableau, Git
SQL &amp; Analytics pipeline for detecting financial fraud patterns and ledger discrepancies in PaySim dataset.

## Objective
SQL & Analytics pipeline for detecting financial fraud patterns, velocity anomalies, and ledger balance discrepancies using the PaySim mobile money transaction dataset.

## Features & Planned Analysis
- **Data Integrity & Cleaning:** Audit account balance discrepancies before and after transactions.
- **Fraud Pattern Identification:** Flag high-risk transactions (`TRANSFER` and `CASH_OUT`) exceeding threshold amounts.
- **SQL Analytics:** Utilize CTEs, window functions (`LAG`, `SUM OVER`), and aggregations to detect fraud velocity.
- **Dashboarding:** Interactive Tableau visualization for audit teams to track flagged accounts.
