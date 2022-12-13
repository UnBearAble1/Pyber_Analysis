# Pyber_Analysis

## Overview of the analysis

The purpose of this analysis is to show the average fares per ride and per drive against three different city settings including urban, suburban and rural areas. Additionally, the data was narrowed to include only the first four months of 2019 with each week’s fares combined into one total to be displayed for the ease of reading. Total fares for each of the three city types were visualized in a multiple line chart for the months in question to show the differences between the three with other information including total rides, total drivers, total fares, average fares per ride and average fares per driver analyzed in a simple table

## Results

Below are the results for various data points in the three regions over the four month period defined

### Total Rides
* Rural areas:    125
* Suburban areas: 625
* Urban areas:    1625

### Total Drivers
* Rural areas:    78
* Suburban areas: 490
* Urban areas:    2405

### Total Fares 
* Rural areas:    $4,327.93
* Suburban areas: $19,356.33
* Urban areas:    $39,854.38

### Average Fare per Ride
* Rural areas:    $34.62
* Suburban areas: $30.97
* Urban areas:    $24.53

### Average Fare per Driver
* Rural areas:    $55.49
* Suburban areas: $39.50
* Urban areas:    $16.57

As the above data demonstrates, urban areas have the highest amount of total rider, total drivers and total fares, however rural areas have the greatest average fares per ride and average fares per driver.

The multiple line plot of the total fares broken out by month shows a similar trend as the summary data, with urban areas having the highest total fare for each week's total.

![Total Fares by city type](https://github.com/UnBearAble1/Pyber_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
While the table shows a good overview of what city types are most heavily utilized and a quick analysis of the fares, the graph shows some interesting areas for further investigation to understand the driving factors behind the changes in total fares. For the next analysis, I would recommend the following:

* Further review of the month of March to understand the fluctuations in total fares in urban areas to understand if it was caused by decreased utilization of the service and drivers behind why. Was there a change in demand or if demand stayed the same, what was in the change in the rides that caused the change and then what actions can we take to improve usage.

* Similarly, at the end of April, total fares dropped heavily for urban and rural areas while increasing for suburban areas. It would be good to further revue key criteria for those times to see what caused the change in total fares to be addressed in the future.

* Additionally, in the data it is hard to see information about our riders. A further analysis should investigate should gather more data on our user answering questions such as: 
  * Are most of the riders using our service first time users? 
  * What percentage are frequent users and if they are frequent, what is their frequency? 
  * Are the fluctuations caused by changes in habits of frequent users? 
  * If most of our riders are first time users, what causes them to not use the service a second time?

* A final area for further analysis should be about the revenue per ride by city type. While the fares are good, how much does it cost the company to support service in each area? Knowing the revenue for supporting rides in each area we can get a better picture of where we want to keep investing and if we need to change rates ro need to promote more riders to meet desired revenue targets.
