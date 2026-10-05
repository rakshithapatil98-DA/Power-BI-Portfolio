# AtliQ Hospitality Analysis

## 📌 Project Overview
This is an end-to-end Power BI dashboard project built on the AtliQ Hospitality dataset (Codebasics Resume Project Challenge), covering 3 months of hotel booking data across multiple cities and properties. The dashboard was designed to give AtliQ's revenue management team a single, interactive view of occupancy, revenue, pricing, and booking performance — replacing manual, error-prone Excel-based reporting with a live, filterable Power BI report.

The data model follows a star schema, built from:

fact_bookings — individual booking-level transactions
fact_aggregated_bookings — pre-aggregated daily booking/capacity data
dim_date — calendar table (week number, month-year, day type)
dim_hotels — property and city details
dim_rooms — room class information
Key Measures — a dedicated DAX measures table powering all KPIs

## 🎯 Business Problem Statement
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

## 🛠️ Tools Used
* Power BI Desktop — data modeling, DAX measures, report/dashboard design
* Power Query — data cleaning and transformation (joining fact and dimension tables, handling booking status, date mapping)
* DAX — custom measures (Revenue, Occupancy %, ADR, RevPAR, Realisation %, Cancellation Rate %, DSRN, Loss due to Cancellation)
* Star Schema Data Modeling — fact and dimension tables linked for efficient, scalable analysis

## 📊 Key KPIs
Revenue
Occupancy %
Average Daily Rate (ADR)
RevPAR
Realisation %
Booking %
Cancellation %
Average Rating
DSRN (Daily Sellable Room Nights)

## 📈 Dashboard
Overview
<img width="913" height="511" alt="Hospitality Dashboard" src="https://github.com/user-attachments/assets/796acee1-c9fb-487b-920c-929075f5aa8a" />

Performance Analysis:
The single-page dashboard includes:

KPI Card Strip — Revenue, Occupancy %, ADR, Cancellation Rate %, DSRN, Loss due to Cancellation at a glance
Occupancy % & ADR Trend by Week — line chart tracking pricing vs. occupancy over time
Revenue by City — clustered bar chart comparing city-level performance
Occupancy % by City and Avg Rating by City — bar charts for performance benchmarking
Properties by Key Metrics — detailed table (Revenue, Occupancy %, Cancellation Rate %, RevPAR, Realisation %, Avg Rating) per property
Bookings % by Platform — bar chart showing channel-wise booking distribution
Occupancy by Day Type — donut chart (weekday vs. weekend patterns)
Avg Rating Gauge — quick visual read on overall guest satisfaction
Slicers — City, Property, Room Class, Booking Platform, Booking Status, Month-Year, Day Type — enabling full self-service filtering

## 🔍 Key Insights
Identified properties with higher and lower occupancy.
Compared revenue performance across cities.
Analyzed booking platform performance.
Identified trends in cancellations and customer ratings.
Compared room-category performance.

## 💡 Business Recommendations

Based on the analysis, management can focus on improving low-performing properties, optimizing room pricing, and improving booking-channel performance.

## 📁 Project Files
Live Project Link: https://app.powerbi.com/view?r=eyJrIjoiNjFhYzZjNjEtYzU3OC00NTcwLTlhMTUtYWYxNWRiNmRmYjJkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9
