# Data Analytics Internship Project – Tula Capital

This repository contains my completed Power BI project submitted as part of the application for the Data Analytics Internship at Tula Capital.

## 📊 Project Overview

The task involved analyzing trade data from three different strategy files. Using Power BI, I created an interactive dashboard that provides both high-level summaries and detailed views of strategy performance.

### 🔧 Tools & Technologies Used
- **Power BI**
- **DAX**
- **Power Query**
- **Chart and Slicers**
- **Drill Through**

---

## 📁 Dataset

The dataset consists of **3 CSV files**, each representing trades from a different strategy:
- Columns: `symbol`, `entry_datetime`, `exit_datetime`, `entry_type`, `pnl`

Each file was merged and a `strategy_name` column was added to identify the source strategy.

---

## 📈 Report Pages

### 📌 Page 1: Strategy Summary
- **Table** with:  
  - `strategy_name`  
  - `Total PnL`  
  - `Win Count` (PnL > 0)  
  - `Loss Count` (PnL < 0)
- **Drillthrough** functionality to Page 2 using `strategy_name`

### 🔍 Page 2: Detailed Report (Drillthrough)
- Filters data based on selected `strategy_name`
- **New columns added**:  
  - `cumulative_pnl` (Running total by `entry_datetime`)  
  - `entry_hour` (Hour of `entry_datetime`)
- **Visuals**:  
  - KPI cards: Total PnL, Win Count, Loss Count  
  - Line Chart: Cumulative PnL over time  
  - Bar Chart: PnL by Hour of Day  
  - Table: All trade details with slicer for `entry_datetime`

---

## 🚀 Key Learnings

- Creating end-to-end BI solutions using Power BI
- Data transformation using Power Query
- Building interactive dashboards and drillthrough reports
- Applying DAX for calculations and time-series analysis
- Designing visual reports for business insights

---

## 📬 Submission

This project was submitted to Tula Capital along with my resume as part of the application for the Data Analytics Internship role.

---

## 📄 Files in This Repository

- `TulaCapital_TradeDashboard.pbix` – Final Power BI report file
- `strategy1.csv`, `strategy2.csv`, `strategy3.csv` – Original datasets
- `README.md` – Project documentation (this file)
