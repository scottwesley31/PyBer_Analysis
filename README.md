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

Overall it's evident that the same trend is repeated; urban city types generate the largest values for fares, despite being spread out over 4 months. This is followed by the suburban and then the rural lines which sit below the urban line consecutively.

The following table breaksdown the fare data by weekly amounts for each city type:
![Weekly_DataFrame](https://user-images.githubusercontent.com/107309793/179642026-0d44f6b8-c7c4-45ac-9b98-6db20594370a.png)

Breaking down the months:

### 2019-01-06 to 2019-02-03
Rural: increase from 187.92 to 333.08
Suburban: increase from 721.60 to 1042.79
Urban: increase from 1661.68 to 2086.94

### 2019-02-03 to 2019-03-03
Rural: Decrease from 333.08 to 175.14
Suburban: Decrease from 1042.79 to 858.46
Urban: Increase from 2086.94 to 2218.20

### 2019-03-03 to 2019-04-07
Rural: Increase from 175.14 to 501.24
Suburban: Increase from 858.46 to 1010.73
Urban: Increase from 2218.20 to 2356.70

### 2019-04-07 to 2019-04-28
Rural: Decrease from 501.24 to 191.85
Suburban: Increase from 1010.73 to 1357.785
Urban: Decrease from 2356.70 to 2238.29

## Summary
