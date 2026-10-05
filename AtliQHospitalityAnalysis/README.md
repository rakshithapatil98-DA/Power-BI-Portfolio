# AtliQ Hospitality Analysis

## 📊 Live Dashboard
🔗 [View Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjFhYzZjNjEtYzU3OC00NTcwLTlhMTUtYWYxNWRiNmRmYjJkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

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
* Revenue
* Occupancy %
* Average Daily Rate (ADR)
* RevPAR
* Realisation %
* Booking %
* Cancellation %
* Average Rating
* DSRN (Daily Sellable Room Nights)

## 📈 Dashboard
Overview :
<img width="913" height="511" alt="Hospitality Dashboard" src="https://github.com/user-attachments/assets/796acee1-c9fb-487b-920c-929075f5aa8a" />

Performance Analysis :
The single-page dashboard includes:

* KPI Card Strip — Revenue, Occupancy %, ADR, Cancellation Rate %, DSRN, Loss due to Cancellation at a glance
* Avg Rating Gauge — quick visual read on overall guest satisfaction
* Occupancy % & ADR Trend by Week — line chart tracking pricing vs occupancy over time
* Revenue by City,Occupancy % by City and Avg Rating by City — clustered bar chart comparing city-level performance
* Properties by Key Metrics — detailed table (Revenue, Occupancy %, Cancellation Rate %, RevPAR, Realisation %, Avg Rating) per property    and city
* Bookings % by Platform — bar chart showing platform-wise booking distribution
* Occupancy by Day Type — donut chart (weekday vs weekend patterns)showing day type occupancy
* Slicers — City, Property, Room Class, Booking Platform, Booking Status, Month, Day Type — enabling full self-service filtering

## 🔍 Key Insights
* Property-level occupancy: AtliQ Palace in Delhi recorded the highest occupancy rate of 66.3%, while AtliQ Grands in Bangalore had the lowest occupancy rate of 44.3% during the 3-month analysis period, indicating a significant variation in property-level performance.
* City-wise revenue performance: Mumbai generated the highest revenue, followed by Bangalore, Hyderabad, and Delhi, maintaining a consistent revenue ranking across the analysis period.
* Booking platform performance: The Other booking platforms contributed the largest share at 40.89%, followed by MakeYourTrip at 20%. Direct Offline bookings contributed only 5%, indicating an opportunity to strengthen direct booking channels and reduce dependency on third-party platforms.
* Weekday vs. weekend occupancy: Weekday occupancy (62.64%) was significantly higher than weekend occupancy (55.85%), suggesting an opportunity to improve weekend demand through targeted promotions, packages, and pricing strategies.
* Room category revenue: The Elite room category generated the highest revenue at ₹553M, followed by Premium at ₹456M, Presidential at ₹372M, and Standard at ₹305M. This indicates that higher-category rooms are making a stronger contribution to overall revenue.

## 💡 Business Recommendations

* AtliQ Grands, Bangalore recorded the lowest occupancy at **44.3%**, along with a low average customer rating of **2.37/5**and a cancellation rate of **24.5%**. The combination of low occupancy, customer ratings, and cancellations indicates a need to investigate customer experience, service quality, and booking cancellations at this property.
* **Weekend Demand Optimization:** The dashboard shows that **weekend occupancy (55.85%) is 6.79 percentage points lower than weekday occupancy (62.64%)**. This indicates relatively weaker weekend demand. To improve room utilization, management could introduce **targeted weekend offers, stay packages, and demand-based pricing**, while monitoring occupancy and ADR to ensure that promotional strategies translate into incremental revenue rather than simply reducing room rates.
* **Increase Direct Booking Contribution:** Direct Online and Direct Offline bookings account for only **15% of total bookings**, compared with a substantially higher contribution from third-party platforms. This indicates an opportunity to increase the property's direct booking share through website-exclusive rates, loyalty benefits, targeted campaigns, and direct-booking incentives. A higher direct booking mix could improve customer ownership, strengthen loyalty, and potentially reduce commission-related costs associated with third-party platforms.
* **Optimize pricing and promotions across room categories:** Continue using demand-based pricing and targeted promotions to maximize revenue from higher-performing room categories. At the same time, analyze the lower performance of Standard rooms and use targeted offers, competitive pricing, and upgrade opportunities to improve their occupancy and revenue contribution.
