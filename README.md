# PyBer Analysis
Module 5

## Overview of the Analysis
### Purpose
An inital analysis was completed and presented on ride-sharing data provided by the company PyBer. This analysis included a bubble chart comparing average fare to total number of rides per city, 3 different box-and-whisker plots to compare number of rides, fare, and number of drivers each against city type, and 3 different pie charts to compare percent of total fares, percent of total rides, and percent of total drivers each against city type. The CEO has requested a table (DataFrame) that summarizes all of the data by city type, as well as a multiple-line chart of total fares by city type. The line chart will breakdown fares by date, resulting in conclusions based on timing.

## Results
The summary DataFrame resulting from analyzing all of the ride-sharing data by city type is as follows:
![Summary_DataFrame](https://user-images.githubusercontent.com/107309793/179505711-fb48df28-5462-408d-90c3-cd05c41bf186.png)

Going through each column, the following conclusions can be made:
### Total Rides
The city type with the largest number of total rides is urban, followed by suburban and then rural (1625, 625, and 125 respectively). This isn't surprising since the majority of persons using PyBer will likely reside in a densely populated area requiring relatively short distanced rides.
### Total Drivers
Following a similar trend, the city type with the largest number of total drivers is urban, followed by suburban, and rural (2405, 490, and 78). To meet the demand of rides requested in each city type, a larger supply of total drivers is needed. The majority of drivers will work in a densely populated area to make more money.
### Total Fares
Continuing the same trend, urban cities generated the largest sum of total fares at $39,854.38 (compared to suburban at $19,356.33 and rural at $4,327.93). Being that there were 1,625 total urban rides, it makes sense that the overall total fares is the highest.
### Average Fare per Ride
The opposite trend is seen in the Average Fare per Ride column; the rural type have the largest average at $34.62, followed by suburban at $30.97, and then urban at $24.53. This trend makes sense assuming that the rides given in rural areas required longer distances and therefore pricier fares.
### Average Fare per Driver
The same trend is captured in the Average Fare per Driver column as the Average Fare per Ride column; rural type has the largest average at $55.49, then suburban at $39.50, and lastly urban at $16.57. Even though the rural areas did not have a large quantity of drivers, thier overall average fare tended to be the highest likely again due to ride distance. Without data on ride distance; this is only an assumption.

The ride-sharing data was grouped by both city type and date and then used to generate the following multiple-line chart which covers the four month period of 1/1/2019-4/28/2019:
![Multiple_Line_Chart](https://user-images.githubusercontent.com/107309793/179510503-c50a3596-0062-40ea-98ba-4b511d8905ab.png)



## Summary
