# Hotel_Data_Analysis
Hotel Data Analysis Using Power BI
1. Introduction
The hospitality industry generates vast amounts of data, and leveraging business intelligence tools like Power BI can provide valuable insights into operations, customer behaviour, and financial performance.
This report presents an interactive Power BI dashboard that analyses hotel booking data, helping stakeholders make data-driven decisions. Key insights include occupancy trends, revenue analysis, guest demographics, and operational efficiency metrics.
2. Objectives
The goal of this project is to:
•	Visualize key hotel performance metrics such as Occupancy Rate, ADR (Average Daily Rate), and Revenue.
•	Identify booking trends to optimize pricing and marketing strategies.
•	Analyse guest demographics to improve customer experience.
•	Track operational performance metrics such as cancellations, lead time, and peak booking periods.
•	Enhance interactivity through slicers, drill-throughs, and automated reporting for better decision-making.
3. Data Preparation & Processing
The dataset used in this analysis consists of hotel booking records with key attributes such as:
•	Hotel Type: Resort Hotel or City Hotel
•	Arrival Date: Date of check-in
•	Guest Details: Market segment, country of origin
•	Booking Details: Lead time, length of stay, cancellation status
•	Financial Data: ADR, total revenue
Key steps in data preparation:
•	Cleaned missing values and handled outliers.
•	Transformed data using Power Query (e.g., extracting year, month from arrival dates).
•	Created calculated columns and measures using DAX (e.g., Occupancy Rate, Revenue Per Available Room).

4. Dashboard & Key Findings
The dashboard consists of several key interactive visuals, including:
📊 KPI Scorecards:
•	Occupancy Rate: (69.37%)
•	Average Daily Rate (ADR): (£102.44 per night)
•	Total Revenue: (£92,440,000)
📈 Trend Analysis:
•	Peak booking months: July and August have the highest occupancy.
•	Cancellation rates: Higher in online bookings compared to corporate bookings.
•	Booking lead time: Most bookings are made less than half a year in advance.
🌍 Guest Demographics:
•	Most frequent travellers come from the Portugal, UK and France.
•	OTA (Online Travel Agencies) bookings tend to have longer stays compared to other bookings.
📉 Operational Metrics:
•	City hotels have both higher occupancy rates and ADR compared to resort hotels.
•	Cancellations increase significantly during off-peak seasons.
•	Longer lead times correlate with lower cancellation rates.

5. Interactivity & Automation
To enhance usability, I have:
•	Added Slicers: Users can filter by hotel type, booking status, country, or market segment.
•	Implemented Drill-through Pages: Clicking on a hotel name provides in-depth insights.
•	Applied Row-Level Security (RLS): Ensuring managers see only their assigned hotel's data.
•	Automated Report Delivery with Power Automate: Sending weekly reports via email.
