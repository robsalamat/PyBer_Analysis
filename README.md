# PyBer_Analysis

## I. Overview of Project

### Background
As a data analyst for PyBer, a ride-sharing app company, we were tasked to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization  for the CEO using Pandas and Matplotlib.

### Objective
As an additional assignment, the CEO requested a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type.

## II. [Analysis and Results](PyBer_Challenge.ipynb)

### A. Summary DataFrame
![](analysis/Summary_DataFrame.PNG)

- The rural cities have the lowest number of rides, number of drivers and total fares; but they have the highest average fare per ride and average fare per driver.
- The urban cities have the highest number of rides, number of drivers and total fares; but they have the lowest average fare per ride and average fare per driver.
- The suburban cities are always in the middle for number of rides, number of drivers, total fares, average fare per ride and average fare per driver.
- The ratio drivers to rides: (rural=1:1.60), (suburban=1:1.27), (urban=1:0.68). The urban city type is the only one with a higher number of drivers versus total rides, which shows an oversupply of drivers relative to demand.



### B. Total Fare by City Type Chart

![](analysis/PyBer_fare_summary.png)

- In all parts of the timeline, the urban cities gave the highest total fares and the rural cities gave the lowest total fares.
- All three city types experience a peak on the 3rd week of February then abruptly goes down until the start of March.
- While the March performance fluctuations were highly volatile for the urban city type, it was much flatter for the suburban and rural type. Suburban was peaking going to the end of April while the other 2 were going down. Starting March, the three city types experience fluctuations that seem independent of each other.

## III. Summary and Recommendations

Based on the results, my recommendations to the CEO includes:

1) There are too many drivers compared to the rider demand in the Urban cities. This city type is our major source of revenue and we don't want want our drivers to leave our app because of the lack of business. We must stop getting new drivers for the mean time and spend more money on marketing to increase our ridership demand. We must come up with the best or minimum ratio for drivers:total_rides and aspire to maintain being above this. This will be the basis for future addition of drivers in the urban cities. 

2) The average fare per ride in the rural cities is very high, this means that the trips are much longer. Combined with the effect of less available drivers in the area. This will lead to longer wait times or worse, unavailability of drivers. We must look into the ratio of drivers:demand in the rural cities too. We must aim to add more drivers to prevent customer loss due to driver unavailability. 

3) For the reporting of the total fare vs timeline chart, it is very important that we must continue recording it vigilantly to make the available data bigger. The 4 months of data that we have can show some micro trends but it is not enough to realistically give us a good picture of when we can expect demand to go up or down. We dont even have a whole year's data that can show how different national holidays and changing pf the seasons can affect the different kind of cities. Once the data size gets bigger and more reliable, this will be used to decide what parts of the year we need to add drivers based on projected demand.

