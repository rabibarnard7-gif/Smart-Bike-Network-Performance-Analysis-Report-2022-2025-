🚴‍♂️ Smart Bike Network Performance Analysis (2022–2025)

A Power BI mini project that analyses global bike-sharing station performance across multiple countries and contracts. The report explores availability, capacity, utilization, banking facilities, and geographic distribution using 2022–2025 data.

📌 Project Overview

This analytics report provides a comprehensive view of bike-sharing stations worldwide.
It highlights real-time operational performance, station readiness, and long-term usage patterns, helping city planners and service operators make informed decisions.

⭐ Key Metrics (KPIs)

Total Bike Stations: 2,856

Total Bike Stands: 57K

Total Available Bikes: 20K

Total Available Bike Stands: 32K

Average Available Bikes/Station: 7

Bike Utilization: 34%

Stations With Banking: 336

No-Parking Stations (0 stands): 335

Stations With Zero Bikes (Critical): 705

📊 Key Insights
🔵 Bike Availability & Utilization

Utilization varies significantly by contract/city.

Top-performing cities: JCDecauxBike, Lund, Ljubljana

Low-availability areas indicate high demand or poor bike redistribution.

Hourly trends clearly show peak vs off-peak usage.

🟢 Station Operational Status

93% of stations are OPEN, indicating strong service uptime.

Stations with 0 bikes or 0 stands highlight critical redistribution needs.

🟣 Banking & Bonus Facility

Majority of stations are Ineligible for bonus incentives.

Banking-enabled stations show slightly higher utilization.

Payment & bonus facilities vary between contracts.

🔻 Geographic Distribution

Latitude/Longitude mapping shows dense station clusters across:
France, Belgium, Spain, Slovenia, Ireland.

City-level heatmaps reveal well-developed and under-serviced zones.

🟠 Contract-Wise Insights

Major operating contracts include Lyon, Toulouse, Brussels, Dublin, Valencia.

Stations with high stands but low bikes indicate oversubscription.

Cities like Amiens and Besancon show varying parking availability.

📈 Dashboard Visuals Used

Bike Utilization % by Contract

Total Bike Stands by Bonus Status

Open/Closed Station Status

Hourly Utilization Trend

Bikes & Stands by Contract

Banking Facility Distribution

Contract-wise Bikes vs Stands Scatter

Geographic (Lat–Long) Map

🛠️ Data Preparation (Power Query + Data Model)
🔗 Data Model Structure

Main Fact Table: Bike Station Sharing Data

Dimensions:

Calendar (Date & Hour-level analysis)

Contractors (City/Contract details)

Measures Table: Centralized DAX calculations

🧼 Power Query Transformations

Extensive cleaning was performed for quality and consistency:

Trimmed, Cleaned, and Standardized Text

Capitalized station/contract names

Replaced inconsistent values

Removed, Reordered & Split columns

Created Custom Columns and Conditional Columns

Extracted Hour for hourly trend modeling

These transformations ensured a clean, reliable data model.

📊 Dashboard Previews

Smart Bike Network Monitoring

![Smart  Bike Network Monitoring](https://github.com/user-attachments/assets/0cb494ea-fea3-4577-9637-418d059d3c6c)


Bike Stations Availability Analysis

![Bike Stations Availablity Analysis](https://github.com/user-attachments/assets/c60b1afc-3831-4e42-a8c4-e402ac541b9f)




🎯 Conclusion

This analytics project provides valuable insights into:

Bike distribution vs demand

Station usage patterns (hourly, yearly, contract-wise)

Operational efficiency across cities

Infrastructure readiness (stands, availability, banking)

These insights help organizations optimize:

Bike redistribution operations

Station expansion planning

Infrastructure upgrades

Contract-level performance management



🙌 Author

Rabi Barnard
Data Analyst | SQL | Power BI | Python
