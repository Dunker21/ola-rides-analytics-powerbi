# 🚕 OLA Ride Analytics Dashboard — Power BI

> A comprehensive, multi-page business intelligence dashboard built in Power BI to analyze **40,540+ OLA rides** across July 2024 — uncovering booking trends, revenue patterns, cancellation drivers, and customer satisfaction metrics that help operations teams make smarter, faster decisions.

---

## 📌 Project Overview

OLA generates thousands of rides every day across multiple vehicle categories. Without structured analytics, spotting what's working (and what's not) is nearly impossible. This dashboard transforms raw booking data into **clear, actionable insights** — enabling business stakeholders to monitor KPIs in real time, identify revenue leakage, and reduce cancellations.

**Tool Used:** Microsoft Power BI Desktop  
**Dataset Period:** 01 July 2024 – 30 July 2024  
**Vehicle Categories Covered:** Prime Sedan, Prime SUV, Prime Plus, Mini, Auto, Bike, E-Bike

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 📦 Total Bookings | **40,540** |
| 💰 Total Booking Value | **₹14 Million** |
| ✅ Successful Rides | **25,210 (62.18%)** |
| ❌ Total Cancellations | **11,290 (27.85%)** |
| ⭐ Avg. Driver Rating | **~4.00 / 5** |
| ⭐ Avg. Customer Rating | **~3.99 / 5** |
| 🏆 Top Vehicle by Booking Value | **Prime Sedan — ₹3.28M** |
| 💳 Top Payment Method | **Cash** (followed by UPI) |

---

## 🗂️ Dashboard Pages

The dashboard is organized into **5 dedicated pages**, each designed for a specific audience and decision:

### 1️⃣ Overall — Executive Summary
A high-level snapshot for leadership. Displays total bookings, total booking value, and the booking status breakdown in a pie chart. A time-series line chart shows daily ride volume fluctuations across the month, helping spot demand patterns and low-traffic periods.

### 2️⃣ Vehicle Type — Fleet Performance
A detailed comparison table across all 7 vehicle types, showing:
- Total Booking Value
- Success Booking Value
- Average Distance Travelled
- Total Distance Travelled

> **Business Insight:** Prime Sedan leads with ₹3.28M in total booking value and 91K km total distance. Bikes and E-Bikes also clock 93K km — indicating high utilization in the two-wheeler segment.

### 3️⃣ Revenue — Payment & Distance Analysis
Breaks down revenue by payment method (Cash, UPI, Credit Card, Debit Card) using a bar chart. A daily ride distance chart reveals consistent 18K–20K km covered per day. A Top 5 Customer leaderboard (by booking value) highlights the platform's highest-value riders.

> **Business Insight:** Cash remains the dominant payment method, significantly ahead of UPI — signaling an opportunity to push digital payment adoption for faster settlements.

### 4️⃣ Cancellation — Root Cause Analysis
Drills into 11,290 cancellations with dual pie charts separating **Customer-driven** vs **Driver-driven** cancellations and their specific reasons:

**Cancelled by Customer (4,080 rides):**
- Driver not moving toward pickup — 29.88%
- Change of plans — 25.94%
- Driver asked to cancel — 19.71%
- Wrong address — 14.93%
- AC not working — 9.54%

**Cancelled by Driver (7,210 rides):**
- Customer-related issue — 34.66%
- Personal & car-related issues — 29.45%
- More than permitted passengers — 19.88%
- Customer was coughing/unwell — 16%

> **Business Insight:** Nearly 30% of customer cancellations happen because the driver isn't moving toward the pickup — a fixable operational problem through stricter driver compliance monitoring and real-time alerts.

### 5️⃣ Ratings — Service Quality Monitor
Displays average Driver Rating and Customer Rating broken down per vehicle type, enabling quality benchmarking across the fleet.

> **Business Insight:** Ratings are tightly clustered between 3.98–4.02, meaning service quality is consistent but there is headroom to push the top performers higher. Bike drivers score the lowest (3.98) and could be the target of driver incentive programs.

---

## 🖥️ Screenshots

### Overall Dashboard
![Overall Dashboard](screenshots/overall.png)

### Vehicle Type Analysis
![Vehicle Type](screenshots/vehicle_type.png)

### Revenue & Payment Breakdown
![Revenue](screenshots/revenue.png)

### Cancellation Analysis
![Cancellation](screenshots/cancellation.png)

### Ratings Dashboard
![Ratings](screenshots/ratings.png)

> 📁 **How to add screenshots:** Create a `screenshots/` folder in your repo root and upload each dashboard page image with the filenames used above.

---

## 💡 Business Impact

This dashboard directly helps OLA's operations and strategy teams in the following ways:

- **Reduce Revenue Leakage** — With 27.85% cancellations, even a 5% reduction in cancellation rate could recover **~₹700K+ in booking value** per month.
- **Optimize Fleet Allocation** — Vehicle-level distance and revenue data enables smarter deployment decisions (e.g., shift Auto supply to high-demand zones given its lower avg distance of 6.21 km vs 15+ km for others).
- **Improve Driver Compliance** — Root cause analysis shows 29.88% of customer cancellations are caused by drivers not moving toward pickup — a measurable, fixable SLA problem.
- **Payment Strategy** — UPI trails Cash significantly; targeted cashback campaigns for UPI could reduce cash handling costs.
- **Quality Benchmarking** — Ratings page lets ops teams identify which vehicle categories need driver coaching or incentive nudges.

---

## 🛠️ Technical Highlights

- **Dynamic Date Slicer** — All pages respond to a synchronized date range filter (01 Jul – 30 Jul 2024), enabling period-over-period analysis.
- **Multi-page Navigation** — Custom sidebar with icons for seamless navigation across all 5 report pages.
- **KPI Cards** — Key metrics are surfaced as prominent stat cards for quick executive scanning.
- **Consistent Theming** — OLA brand colors (black + green) applied throughout for professional presentation.
- **Drill-down Visuals** — Pie charts, line charts, bar charts, and matrix tables all built natively in Power BI without external plugins.

---

## 📁 Project Structure

```
OLA-PowerBI-Dashboard/
│
├── OLA.pbix                  # Main Power BI file
├── README.md                 # Project documentation
└── screenshots/
    ├── overall.png
    ├── vehicle_type.png
    ├── revenue.png
    ├── cancellation.png
    └── ratings.png
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `OLA.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Use the date slicer on each page to filter by your desired period.
4. Navigate between pages using the left sidebar or the tab bar at the bottom.

---

## 👨‍💻 Author

**[Your Name]**  
Data Analyst | Power BI Developer  
📧 [your.email@example.com]  
🔗 [LinkedIn Profile](https://linkedin.com) | [Portfolio](https://yourportfolio.com)

---

## ⭐ If this project helped you or inspired your own work, give it a star!
