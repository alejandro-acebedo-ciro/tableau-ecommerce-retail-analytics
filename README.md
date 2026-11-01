# E-Commerce Retail Performance & Product Discovery Dashboard

An end-to-end interactive retail analytics solution built in Tableau Desktop and published to Tableau Public. This project evaluates historical sales dynamics, category profitability, regional margin distribution, time-series seasonal demand forecasting, and parameter-driven "what-if" discount scenario modeling across **$2.3M+ in retail transactions**.

**[Launch Interactive Tableau Public Dashboard](https://public.tableau.com/app/profile/alejandro.acebedo.ciro/viz/RetailPerformanceAnalyticsForecasting/Retail_Dashboard)**

---

## Executive Summary & Key Business Insights

- **Revenue & Profit Drag Isolation:** Evaluated performance across 17 sub-categories, identifying severe profit erosion in high-volume categories like **Tables** ($207K in total sales resulting in a **$56K net loss** due to aggressive discounting).
- **Predictive Demand Forecasting:** Built a 13-month exponential smoothing time-series model projecting seasonal Q4 surges (+ $38K demand spike projected for Nov 2024).
- **What-If Discount Sensitivity:** Designed a dynamic parameter control allowing stakeholders to simulate discount thresholds and project real-time margin restoration.
- **Geographic Profit Allocation:** Visualized state-level profitability via spatial heatmaps, isolating primary revenue drivers (California, New York) versus loss-making deficit regions (Texas, Illinois, Pennsylvania).

---

## Data Architecture & Tech Stack

- **Business Intelligence Tool:** Tableau Desktop / Tableau Public
- **Data Modeling & Analytics:** Packaged Data Extract (`.hyper`), Custom Calculated Fields, Dynamic Parameters, Trend Line Forecasting
- **Dataset Source:** `Store Dataset for Project.xlsx` (Included in repository)

---

## 📁 Repository Structure

```text
tableau-ecommerce-retail-analytics/
│
├── README.md                                          # Executive Overview & Methodology
├── Store Dataset for Project.xlsx                    # Raw Source Dataset
└── E-Commerce Retail Performance Dashboard.twbx      # Packaged Tableau Workbook
