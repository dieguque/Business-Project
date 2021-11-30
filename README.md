# Overselling Tickets in a New Airline

Diego Duque

## Abstract

The purpose of this project is to help a brand new airline to oversell flight tickets. The client is an airline that still has not started operations but the stakeholders are aware that some airlines overbook flights; so they want to know the profitability to oversell the flights since the first day of operations. A new airline like this lacks data so they are interested in learning about overbooking in the industry without historical data and using public data. This project will benefit any airline that does not have any criteria to oversell flight seats. It could be a brand new airline or any small or local airline.

## Design
The project goal is to provide data science tools to a brand new airline to overbook a flight. The are many factors that can help to improve overselling a flight but we will be limited with the free online data available. The data should be a starting point to oversell the flight.

## Data
All the datasets are from the Department of Transportation. This data contains domestic and international flights from January 2019 to July 2021, daily passengers in all the U.S. airports from January 2019 to March 2020, and the passengers boarded as well as passengers that were denied boarding by the U.S. largest airlines from 1990 to 2020.

[Passengers Boarded and Denied Boarding by the Largest U.S. Air Carriers:](https://www.bts.gov/content/passengers-boarded-and-denied-boarding-largest-us-air-carriersathousands-passengers)

[Commercial Aviation Departures:](https://data.bts.gov/Aviation/Commercial-Aviation-Departures/bpqk-hyst)

## Methodology

*Data Collection*

1. Gathered the data from the Department of Transportation by downloading by cvs files.

*Data Manipulation*

2. Used Vlookup function on Google Sheet to filter the data due to there some rows not being needed.
3. Used pivot table on GoogleSheat to calculate averages

*Data Visualization*

4. Calculated the weekday people screened in the U.S. airports using Tableu.
5. Other charts created using Google Sheets were created for the Exploratory Data Analysis.


## Tools
[Google Sheets](https://docs.google.com/spreadsheets/d/1x9_CqGwHeDd0mhpFVB7V0mFU6cn2hEgf_rSGuoO1-Q4/edit?usp=sharing)
Pivot Table
Vlookup
Line Charts
Sort and filter tool

[Tableu](https://public.tableau.com/views/CommercialAviationDepartures/ExploratoryDataAnalysis1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
Filtering and plotting

## Summary and Findings
The results show that in an airplane with 128 seats and an average of 90% people make it to the flight, you can overbook 14 seats. 

<img src=https://github.com/dieguque/Business-Project/blob/bec118b5d7a2fb8a72cccfcacd91323a655d0440/charts/Overselling%20Tickets%20in%20a%20New%20Airline.jpg>

Assuming the plane ticket is $512 (Miami - Cleveland in 2019) and the voucher fee is $200 (lowest amount in the industry) we get the efficient frontier is to oversell only 6 tickets instead of 14 tickets.

<img src=https://github.com/dieguque/Business-Project/blob/df372875a062e79ff259d0eb33049dca6c767cd6/charts/15773976956951.jpeg>

<img src=https://github.com/dieguque/Business-Project/blob/df372875a062e79ff259d0eb33049dca6c767cd6/charts/1577396350429.jpeg>


### More resultas available on the [Google Presentation](https://docs.google.com/presentation/d/1GQiyY4E52p0qHrbkRfC8lPzneE6mHTxxgFXKi8EDUgE/edit?usp=sharing)
