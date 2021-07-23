# Overbooking in a new airline

Diego Duque

## Abstract

The purpose of this project is to help a brand new airline to oversell flight tickets. The client, is an airline that still has not started operations but the stakeholders are aware that some airlines overbook flights so they want to oversell their flights since their first day of operations. A new airline like this lacks of data so they are interested in learn about the overbooking in the industry without historical data and using public data. This project will benefit any airline that does not have any criteria to oversell flight seats. It could be a brand new airline or any small or local airline (not nationwide).

## Design
The project goal is to provide data science tools to a brand new airline to overbook a flight. The are many factors that can help to improve overselling a flight but we will be limited with the free online data available. That should be a starting point to oversell the passengers flight.

## Data
All he datasets are from the Department of Transportation. This data contains domestic and international flights from January 2019 to July 2021, daily passengers in all the US airport from January 2019 to March 2020, and the passenger boarded and denied boarding by the US largest carriers from 1990 to 2020.

Passengers Boarded and Denied Boarding by the Largest U.S. Air Carriers: https://www.bts.gov/content/passengers-boarded-and-denied-boarding-largest-us-air-carriersathousands-passengers
Commercial Aviation Departures: https://data.bts.gov/Aviation/Commercial-Aviation-Departures/bpqk-hyst

## Methodology
*Data Collection*
1. Gathered the data from the Department of Transportation by downloading by cvs files.

*Data Manipulation*
2. Used Vlookup function on Google Sheet to filter the data due there were some rows that were not needed.
3. Used pivot table on GoogleSheat to get averages

*Data Visualization*
4. Calculated the weekday people screened in the US airports using Tableu.
5. Other charts created using Google Sheets were created for the Exploratory Data Analysis.


## Tools
Google Sheets
Pivot Table
Vlookup
Line Charts
Sort and filter tool

Tableu
Filtering and plotting
## Summary
The results showed in an airplane with 128 seats and 90% people taking the flight you can overbook 14 seats. But the efficient frontier is to oversell only 6 tickets because there is always an overbook voucher.

People misses more flights on Tuesdays and in general, you can build fancy models for overbooking that can lead to more revenue.

## Results