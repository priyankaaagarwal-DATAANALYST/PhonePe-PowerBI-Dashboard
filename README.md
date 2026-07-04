# 📱 PhonePe Payment Insights Dashboard

## 🎯 Project Overview

A highly interactive, visually striking Power BI analytics dashboard built to monitor transaction behaviors, user growth metrics, and revenue dynamics for PhonePe ("powering Bharat"). This tool transforms raw fintech logs into actionable insights around transaction success rates, age demographics, and product service popularity.

---

## 🛠️ Tech Stack

The dashboard utilizes advanced Power BI functionalities and design practices:

* 📊 **Power BI Desktop** – Core development platform for visualization and reporting layout.
* 📂 **Power Query** – Used to clean, shape, and structure transactional records.
* 🧠 **DAX (Data Analysis Expressions)** – Implemented to create high-performing time-intelligence measures (MoM growth) and power **Dynamic Text Cards**.
* 🎨 **Advanced Tooltips** – Custom report page tooltips designed to give deep contextual breakdowns without cluttering the main view.

---

## 📂 Data Source

* **Source:** PhonePe pulse / simulated digital wallet transaction data.
* **Structure:** High-volume transaction ledgers detailing unique user counts, transaction values ($bn$), timestamps, payment statuses (Successful, Pending, Failed), and consumer demographics.

---

## 💡 Features & Highlights

### • Business Problem

In a rapidly expanding digital payment ecosystem, product managers and executives need to monitor transactional health in real time. Spotting whether specific services are failing, identifying which age demographics drive the highest volume, or figuring out exactly when usage peaks during the week is highly complex without an aggregated analytics view.

### • Goal of the Dashboard

* Provide an immediate operational snapshot of monthly transaction health.
* Enable granular drill-downs via custom hover-interactions (tooltips) for specialized metrics.
* Drive automated business conclusions directly on the user interface through smart text generation.

### • Walkthrough of Key Visuals & Advanced Elements

#### 📈 Strategic KPIs & Dynamic Trends (Top Ribbon)

* **Total Transactions:** 300K with a green dynamic MoM Growth indicator (**8.97%**).
* **Total Value:** 3.47bn with a dynamic MoM Value Growth indicator (**8.98%**).
* **Unique Users:** 108K accompanied by a mini trend sparkline.
* **Successful Rate:** Sitting at a high **96.0%** platform efficiency benchmark.

#### 💬 Dynamic Text AI Insights (Lower Right Panel)

* A dedicated **Insights** block that automatically updates text narratives based on current filters.
* *Live Readout Examples:*
> "On Weekdays the no of transactions are maximum"
> "Loans service gives the highest transaction value"


#### 🔄 Interactive Charts

* **Transactions Over Time (Combo Chart):** Tracks total transaction values versus transaction volumes across a 12-month timeline.
* **Age Segment Contribution (Donut Chart):** Breaks down the customer base into generational pillars—**Gen X** (37.58%), **Millennials** (37.07%), **Gen Z** (20.78%), and **Boomers** (4.57%).
* **Top 5 Users & Weekend vs Weekday Usage:** Bar and donut visuals evaluating user spending leaders and weekly habits (**Weekday 71.6%** vs **Weekend 28.4%**).

## 🛠️ Advanced Analytical Enhancements

### 💡 Dynamic Report Page Tooltips

Instead of default black-box statistics, hovering over specific metrics reveals rich secondary charts configured as hidden report-page tooltips:

1. **Service Type Breakdown (`Tooltip 1.png`)**
* Triggered when looking at transaction totals to show **Total transaction values by Service Type**. It highlights specific service dominance like *Credit Score* (~0.5bn), *To Mobile*, *FASTag Recharge*, *DTH*, and *Cable TV*.


2. **Generational Spending Power (`Tooltip 2.png`)**
* Triggered to display **Total transaction values by Age segment**, normalizing spending habits to a 100% comparative scale across *Gen X*, *Millennials*, *Gen Z*, and *Boomers*.

![Dashboard Preview](https://github.com/priyankaaagarwal-DATAANALYST/PhonePe-PowerBI-Dashboard/blob/main/Dashboard%20Overview.png)


