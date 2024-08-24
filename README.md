# Driver Lifetime Value
## Overview
This project is a take-home data science assignment aimed at calculating the Lifetime Value (LTV) of drivers for Lyft. By exploring and analyzing the provided datasets, we aim to uncover insights into the projected lifetime value of drivers and make actionable recommendations for Lyft's business.

## Objective
The primary objective is to estimate a driver's Lifetime Value to Lyft and provide actionable insights based on data analysis. The questions we aim to answer include:

What are the main factors that affect a driver’s lifetime value?
What is the average projected lifetime of a driver?
Do all drivers act alike, or are there specific segments that generate more value for Lyft?
What recommendations can be made for the business?
Project Structure
1. Data Exploration
Data Overview: We will begin by exploring the three datasets to understand the structure and relationships between them.
driver_ids.csv: Contains data related to driver information and onboarding.
ride_ids.csv: Contains information about individual rides, such as distance, duration, and prime time.
ride_timestamps.csv: Contains event-based timestamps for each ride, allowing us to track ride progress.
2. Data Analysis
Lifetime Value Calculation:
Calculate the value a driver brings to Lyft based on fare structure (Base Fare, Cost per Mile, Cost per Minute, etc.).
Driver Segmentation:
Identify potential clusters or segments of drivers based on patterns in the data.
Lifetime Estimation:
Calculate the average driver lifetime based on the data.
Segment Analysis:
Analyze if specific segments of drivers generate more value than others.
3. Business Recommendations
Provide actionable insights for Lyft based on the data analysis, with suggestions on how to maximize driver retention and improve overall driver lifetime value.
Datasets
driver_ids.csv:

driver_id: Unique identifier for a driver.
driver_onboard_date: Date of onboarding.
ride_ids.csv:

driver_id: Unique identifier for a driver.
ride_id: Unique identifier for a ride.
ride_distance: Distance of the ride in meters.
ride_duration: Duration of the ride in seconds.
ride_prime_time: Prime time multiplier for the ride.
ride_timestamps.csv:

ride_id: Unique identifier for a ride.
event: Describes the type of event (requested, accepted, arrived, picked_up, dropped_off).
timestamp: Time of the event in UTC.
Assumptions
All rides occurred in San Francisco.
All timestamps are in UTC.
The fare structure is based on the following:
Base Fare: $2.00
Cost per Mile: $1.15
Cost per Minute: $0.22
Service Fee: $1.75
Minimum Fare: $5.00
Maximum Fare: $400.00
Expected Outcomes
Driver LTV Estimation: A detailed report on how lifetime value varies across drivers, including projections of their average driving lifetimes.
Actionable Insights: Insights into the main drivers of lifetime value and recommendations for Lyft to enhance driver retention and profitability.
