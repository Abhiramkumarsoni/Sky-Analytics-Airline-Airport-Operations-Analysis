# Travel & Hospitality : Navigating the Complexities of Airline and Airport Operations (EXCEL)
 Analyzed ~70K flight records to uncover patterns in delay causes, cancellation trends, and airline/airport performance using Excel-based dashboards.
 
# EXCEl Project Link 
https://1drv.ms/x/c/cac9b8acdc512f53/EQrwFTqkwkFEnUnLXkbqKroBq5iZlLUu1o3OcSS0ac7UkA?e=6Xsbfj


## Background

SkyNet Analysis Inc. is a leading consultancy firm specializing in aviation analytics. With the aviation industry's rapid expansion and the increasing complexity of global air travel, SkyNet plays a critical role in providing data-driven insights to airlines, airports, and regulatory bodies. The company has access to extensive datasets that cover a wide range of information, including flight schedules, delays, airline operations, and airport traffic details. These datasets offer a unique opportunity to explore and understand the multifaceted nature of the aviation industry, from operational efficiency and customer satisfaction to logistical challenges and environmental impact.

## Objective

The primary objective of this case study, titled "Sky Analytics: Navigating the Complexities of Airline and Airport Operations," is to deeply analyze and interpret the extensive datasets encompassing flights, airlines, and airports - namely "flights.csv", "airlines.csv", and "airports.csv". The analysis aims to uncover critical insights into flight operations, delay patterns, airline efficiency, and airport traffic dynamics. By exploring these datasets, the study seeks to identify key factors influencing operational efficiency, understand the intricacies of flight scheduling and delays, and evaluate the performance metrics of airlines and airports. The ultimate goal is to provide strategic recommendations to enhance operational effectiveness, improve customer experiences in air travel, and contribute to the overall advancement of the aviation industry's standards and practices.

## Data Sources

### Flights Dataset (`flights.csv`)

This dataset contains detailed flight information, including timings, delays, and other flight-specific data. Key columns analyzed include: YEAR, MONTH, DAY, DAY\_OF\_WEEK, AIRLINE, FLIGHT\_NUMBER, TAIL\_NUMBER, ORIGIN\_AIRPORT, DESTINATION\_AIRPORT, SCHEDULED\_DEPARTURE, DEPARTURE\_TIME, DEPARTURE\_DELAY, TAXI\_OUT, WHEELS\_OFF, WHEELS\_ON, SCHEDULED\_TIME, ELAPSED\_TIME, AIR\_TIME, DISTANCE, TAXI\_IN, SCHEDULED\_ARRIVAL, ARRIVAL\_TIME, ARRIVAL\_DELAY, DIVERTED, CANCELLED, CANCELLATION\_REASON, AIR\_SYSTEM\_DELAY, SECURITY\_DELAY, AIRLINE\_DELAY, LATE\_AIRCRAFT\_DELAY, WEATHER\_DELAY.

### Airlines Dataset (`airlines.csv`)

This dataset provides information about various airlines, with columns: IATA\_CODE and AIRLINE.

### Airports Dataset (`airports.csv`)

This dataset contains information about various airports, with columns: IATA\_CODE, AIRPORT, CITY, STATE, COUNTRY, LATITUDE, LONGITUDE.


Methodology & Process:

Performed data cleaning and feature engineering to create metrics like total delay, delay category, on-time flag, and fleet utilization

Applied normalization across time and geography to ensure comparative accuracy

Developed key KPIs such as:

Delay by Cause

On-time Performance

Cancellation Rate

Peak Delay Periods

Utilized Pivot Tables, filters, and conditional logic to assess airline operations and performance

Designed an interactive Excel Dashboard to visualize insights and comparisons

# Key Insights Achieved:

Top Delayed Airlines:
American Airlines (AA) – 23.19 min
Delta Airlines (DL) – 21.22 min
ExpressJet (EV) – 20.48 min

Best On-Time Performance:
Delta Airlines (DL) – 70.13%
Frontier Airlines (F9) – 47.21% (lowest)

Primary Delay Causes:
Late aircraft and airline internal issues
Geographical Insight:

Texas (TX) had the highest airport density

Fleet Utilization:
WN had the highest (22.78%), AA had the lowest

Top 5 Busiest Airports:
ATL, ORD, DFW, LAX, DEN (each >79K flights)

Highest Cancellation Rate:
Airline MQ – 9.2%, mostly due to weather (Reason = B)

Flight Deviation Accuracy:
UA – most deviation (least accurate)
HA – least deviation (most accurate)

Limitation:

Dataset covered only 2 months, so seasonal trends couldn’t be analyzed effectively

Business Outcome:
Delivered a comprehensive Excel dashboard that helped identify performance gaps, optimize airline scheduling, and improve airport operational efficiency. Insights enabled data-driven decisions to improve on-time performance and fleet management strategies.

Tools: Excel, Pivot Tables, Feature Engineering, Data Cleaning, Dashboarding
