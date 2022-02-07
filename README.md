# PyBer Analysis
Throughout this module we have been analyzing data for a ride-sharing company called PyBer. We were provided two files that we based our analysis on:
1. The first data set contains the cities along with their driver count and type (Urban, Suburban, or Rural):
   [City Data](https://github.com/haldud/pyber-analysis/blob/66698e262ebf800fcbeb70d7546f48cc3330381d/Resources/city_data.csv)
2. The second data set contains the unique ride data that includes the ride id, fare amount, and city:
   [Ride Data](https://github.com/haldud/pyber-analysis/blob/66698e262ebf800fcbeb70d7546f48cc3330381d/Resources/ride_data.csv)

## Overview
For our challenge, we were given a new assignment to analyze data by city type. We used Pandas and Matplotlib to combine the data from the city and ride data files.

For part 1 of our challenge, we identified the following statistics by city type:
- Total Rides
- Total Drivers
- Total Fares
- Average Fare per Ride
- Average Fare per Driver

For part 2, we combined the usage of several features within Pandas and Matplotlib to generate a multiple-line graph to show weekly fares by city type. This allows us to quickly identify the differences between the city types over the first few months of 2019.

## Results
All of our code and results can be viewed by examining the [Challenge](https://github.com/haldud/pyber-analysis/blob/3f6cc13753163e0f7682a30657a482cd09568ed5/PyBer_Challenge.ipynb) Jupyter notebook file.

The results for part 1 of our analysis are as follows:
- Total rides are five times greater in Suburban cities than Rural, and about 2.5 times greater in Urban than Suburban.
    | Type      |     Count |
    | --------- | --------: |
    | Rural     |       125 |
    | Suburban  |       625 |
    | Urban     |      1625 |
    
- Total drivers are a little more than six times greater in Suburban cities than Rural, and about five times greater in Urban than Suburban.
    | Type      | Total     |
    | --------- | --------: |
    | Rural     |        78 |
    | Suburban  |       490 |
    | Urban     |      2405  |
 
- Total fares are almost five times greater in Suburban cities than Rural, and about two times greater in Urban than Suburban.
    | Type      | Total       |
    | --------- | ----------: |
    | Rural     | $4,327.93   |
    | Suburban  | $19,356.33	|
    | Urban     | $39,854.38  |
  
 - Average fares are about four dollars less in Suburban cities than Rural, and about six dollars less in Urban than Suburban.
    | Type      |       Total |
    | --------- | ----------: |
    | Rural     |      $34.62 |
    | Suburban  |      $30.97 |
    | Urban     |      $24.53 |
  
 - Average fare per driver are about 16 dollars less in Suburban cities than Rural, and about 23 dollars less in Urban than Suburban.
    | Type      |       Total |
    | --------- | ----------: |
    | Rural     |      $55.49 |
    | Suburban  |      $39.50	|
    | Urban     |      $16.57 |

For part 2 of our analysis, below is the multiple-line graph to show weekly fares by city type. We can see that there are no obvious trends in fare changes for each city type. We can also tell that the urban fare totals are about twice as large as suburban - they are typically about $1,000 more for each week's bucket. Suburban fare totals are usually two to three times larger than rural. Rural city totals are not exceeding $500.

![Multi-line Graph of Weekly Fares by City Type](https://github.com/haldud/pyber-analysis/blob/4987cf4b89b7eacd0d8f5c5e94c359abe1730a86/analysis/PyBer_fare_summary.png)

## Summary
The multi-line graph paints a good picture of the disparities between rural, suburban, and urban total fares. The analysis in the first part allowed us to identify the primary reasons for the disparities. My recommendations to the CEO are below. It is important to note that there very well may exist other reasons for the disparities, but those are not identified in the data set we were provided.

1. Increase the total number of rides and drivers in rural cities. Suburban cities would most likely benefit from the same. An increase in number of drivers in rural and suburban will hopefully increase the number of total rides.
2. Improve the ratio of total drivers to rides in urban areas. It would be difficult to recommend lowering the number of drivers, but there are fewer rides than drivers in urban areas. Ideally, the number of rides can be increased with the existing number of drivers.
3. Increase the fare per ride amounts for urban areas. The average per ride is more than $6 lower than in suburban cities and about $10 lower than in rural cities.
